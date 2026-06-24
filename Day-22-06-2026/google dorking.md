## \# Google dorking:

##### &#x20;  1. site:

###### &#x20;        > Restricts the search to a specific domain. (e.g.,site:example.com)

###### 

##### &#x20;  2. filetype:

###### &#x20;        > Searches for a specific file extension. (e.g., filetype:pdf or filetype:sql)

###### 

##### &#x20;  3. intitle:

###### &#x20;        > Looks for specific words in the webpage's title tab.

###### 

##### &#x20;  4. inurl:

###### &#x20;   > Looks for specific words inside the web address itself.

###### 

##### &#x20;   \*\* Scary Real-World Examples (Instructor Demo):

##### &#x20;  1. Finding Confidential Documents:

###### &#x20;         > site:targetcompany.com filetype: pdf "confidential" OR "internal use only"

###### 

##### &#x20;  2. Finding Database Dumps (Passwords):

###### &#x20;         > filetype: sql "INSERT INTO" "password" "email" (This looks for SQL database backups accidentally left on public web servers!)

###### 

##### &#x20;  3.Finding Exposed Webcams:

###### &#x20;         > intitle: "Live View / - AXIS" (This queries Google for unsecured, internet-facing security cameras).

###### 

##### &#x20;  4. Finding Exposed Directories:

###### &#x20;         > intitle: "index of" "passwords.txt" (This looks for web servers where the administrator forgot to disable directory listing,   

###### &#x20;                      exposing raw files).



&#x20;

#### \# related assignment:

##### &#x20;   1) find username and password and version from sql

&#x20;         

###### &#x20;    Ans)  $Id: mysql-tables.sql,v 1.5 2003/09/13 22:50:20 kevin Exp             

##### &#x20;         > Tables formed:                

###### &#x20;             a) conference\_global

###### &#x20;             b) conference 

###### &#x20;             c) papers 

###### &#x20;             d) invited\_speakers 

###### &#x20;             e) registrants

###### &#x20;             f) reviewers

###### &#x20;             g) reviewer\_proposals

###### &#x20;             h) reviews 

###### &#x20;             i) comments

###### &#x20;             j) links

###### &#x20;             k) scheduler\_locations

###### &#x20;             l) scheduler\_locations\_rooms

###### &#x20;             m) scheduler\_session\_times

###### &#x20;             n) scheduler\_themes

###### &#x20;             o) scheduler\_presentations

###### &#x20;             p) scheduler\_chairs

###### &#x20;             q) scheduler\_functions

##### &#x20;  

|username(admin\_login)|password(admin\_password)|
|-|-|
|admin|21232f297a57a5a743894a0e4a801fc3|



##### 

##### 

##### &#x20;2) find ip address of webcam.

###### &#x20;  Ans)ip address- 2a00:1230::5049:602c





##### &#x20;3) find confidential file .

###### Ans)site:"mit.edu" filetype:pdf "confidential" OR "internal use only"

