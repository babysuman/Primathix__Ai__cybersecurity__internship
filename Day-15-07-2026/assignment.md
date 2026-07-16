#### Assignment: 

###### Cloud Threat Modeling Write a 1-page memo explaining the Shared Responsibility Model to a non-technical CEO. Explain why buying AWS does not mean the company is automatically secure, using the Capital One breach as a case study.



###### Ans)

###### To: Chief Executive Officer (CEO)

###### From: Cybersecurity Analyst

###### Date: 15 July 2026

###### Subject: Why Using AWS Does Not Automatically Make Our Company Secure.

###### 

###### Purpose:

###### This memo explains the Shared Responsibility Model in cloud computing and why purchasing Amazon Web Services (AWS) does not automatically guarantee the security of company data. It also highlights the Capital One data breach (2019) as an example of the risks involved.

###### 

###### What is the Shared Responsibility Model?

###### 

###### Cloud providers such as Amazon Web Services (AWS) protect the infrastructure that runs cloud services. However, customers are responsible for securing the data, applications, and configurations they place in the cloud.

###### 

###### Think of it like renting an apartment:

###### 

###### The landlord ensures the building is safe, secure, and maintained.

###### The tenant must lock the apartment door, protect valuables, and use the property responsibly.

###### 

###### Similarly, AWS secures the cloud infrastructure, while our company must secure what we store and run inside it.

###### 

###### AWS Responsibilities (Security of the Cloud)

###### 

###### AWS is responsible for:

###### 

* ###### Physical security of data centers
* ###### Networking infrastructure
* ###### Servers and storage hardware
* ###### Virtualization technology
* ###### Availability of cloud services
* 

###### Customer Responsibilities (Security in the Cloud)

###### &#x20; 

###### &#x20; Our company is responsible for:

###### 

* ###### Protecting customer and business data
* ###### Configuring cloud services correctly
* ###### Managing user accounts and access permissions
* ###### Encrypting sensitive information
* ###### Updating and patching applications
* ###### Monitoring for suspicious activity
* ###### Complying with security policies and regulations



##### Case Study: Capital One Data Breach (2019)

###### 

###### In 2019, Capital One suffered a major data breach affecting over 100 million customers and applicants in the United States and Canada.

###### 

###### What Happened?

###### 

###### An attacker exploited a misconfigured Web Application Firewall (WAF) in Capital One's AWS environment. This misconfiguration allowed unauthorized access to sensitive data stored in Amazon S3 buckets.

###### 

###### Why AWS Was Not Responsible

###### 

###### AWS infrastructure itself was not compromised. The breach occurred because of a customer-side configuration error. Under the Shared Responsibility Model:

###### 

###### AWS successfully protected its cloud infrastructure.

###### Capital One was responsible for securely configuring its cloud resources and managing access controls.

###### This incident demonstrates that even when using a highly secure cloud platform, incorrect security settings can lead to serious data breaches.

###### 

###### Key Lessons for Our Company:

###### 

###### To keep our cloud environment secure, we should:

* ###### Follow the principle of least privilege by giving users only the access they need.
* ###### Regularly review cloud configurations and permissions.
* ###### Encrypt sensitive data both at rest and in transit.
* ###### Enable multi-factor authentication (MFA) for all privileged accounts.
* ###### Continuously monitor cloud activity using security tools and logging.
* ###### Perform regular security assessments and penetration testing.
* ###### Train employees on cloud security best practices.

&#x20;  

