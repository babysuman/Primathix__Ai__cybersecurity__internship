### \# Assignment 2:

##### Lab: Cloud Misconfiguration Hunt

##### 1\. Use a specialized OSINT tool like GrayhatWarfare (a search engine for public S3 buckets).

##### 2\. Search for common sensitive keywords like "backup", "passwords.txt", or "employee\_records".

##### 3\. Identify an open bucket (DO NOT download sensitive data, this is for observation only).

##### 4\. Note the URL structure and explain how a simple IAM policy change could have hidden this

##### data.



###### Ans)URL:https://ocs-asia.sgp1.digitaloceanspaces.com/apga//password.txt

###### &#x20;     The URL structure was:

###### &#x20;     https://<bucket-name>.<region>.digitaloceanspaces.com/<folder>/<file>

###### &#x20;     Bucket: ocs-asia

###### &#x20;     Region: sgp1 (Singapore)

###### &#x20;     Folder: apga

###### &#x20;     Object: password.txt

###### 

###### Observation: The object was hosted on a DigitalOcean Spaces bucket (an S3-compatible object storage service). DigitalOcean Spaces supports public and private objects depending on how the             

###### &#x20;            owner configures access.

###### 

###### &#x20;  Why was it accessible?

###### &#x20;  If a file can be accessed directly through its URL without logging in, it generally means the object or bucket has been intentionally or accidentally configured to allow public reads.    

###### &#x20;  DigitalOcean Spaces supports both public-read and private access controls.

###### 

###### &#x20;  How could this have been prevented?

###### &#x20;  The bucket owner could have:

* ###### &#x20;  Changed the object ACL from public-read to private.
* ###### &#x20;  Used a bucket policy to restrict public access.
* ###### &#x20;  Required authenticated or pre-signed requests for access.
* ###### &#x20;  Regularly reviewed storage permissions and access policies.

