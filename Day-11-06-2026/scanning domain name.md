### Lab experiment:

##### 

##### Ques) Using Nmap command scan any domain name?

##### 

##### Ans) Perform command:

###### &#x20;      1. nmap name.com - simple scan.

###### &#x20;      2. nmap --top-ports 100 name.com - scan common 100 ports.

###### &#x20;      3. nmap -sV name.com - service version . 

##### &#x20;

##### &#x20; # Result:

###### &#x20;           > port 80/tcp is opened and providing http services.

###### &#x20;           > port 443/tcp is opened and providing https services.

###### &#x20;           > port 8080/tcp is opened and providing http-proxy.

###### &#x20;           > port 8443/tcp is opened and providing https-alt.     

<img width="835" height="721" alt="Screenshot_2026-06-12_02_21_04" src="https://github.com/user-attachments/assets/45437bb7-14c8-4601-9b2e-c6b46821b869" />
