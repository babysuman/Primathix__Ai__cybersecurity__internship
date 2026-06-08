# \# Digital forensic tool:

1. ### FTK Imager tool:

###### &#x20;         > FTK Imager is a widely used, free digital forensics tool used to create exact, bit-for-bit copies (forensic images) of digital

###### &#x20;           storage media. It captures every piece of data—including deleted files and unallocated space—without altering the original evidence.



### Why to use ?

###### > It has a simple user interface and advanced searching capabilities.

###### > FTK supports EFS decryption.

###### > It produces a case log file.

###### > It has significant bookmarking and salient reporting features.

###### > FTK Imager is free.





#### \#How it works:

###### Step 1: Download and install the FTK imager on your machine.

###### 

###### Step 2: Click and open the FTK Imager, once it is installed. You should be greeted with the FTK Imager dashboard.

###### 

###### Step 3: In the menu navigation bar, you need to click on the File tab which will give you a drop-down, like given in the image below, just click on the first one that says, Add Evidence Item.

###### 

###### Step 4: After that, there will be a pop-up window that will ask you to Select the Source of the Evidence. If you have connected a physical hard drive to the laptop/computer you are using to make the forensic image, then you will select the Physical Drive here. Click on Next. Now, Select the Physical Drive that you would like to use. Please make sure that you are selecting the right drive, or you will waste your time exporting a forensic image of your own OS drive.

###### 

###### Step 5: Now, we will export the forensic images. 

###### &#x20;       Right-click on the Physical Drive that you would like to export in the FTK Imager window. Select Export Disk Image here.

###### &#x20;       Click the Add button for the Image Destination.

###### &#x20;       Select the Type of Forensic Image you would like to export. Select .E01 and Click Next.

###### &#x20;       After that, you will have to enter information regarding the case now. You can either leave them blank or keep it general, this part is      

###### &#x20;       totally upon you.

###### &#x20;       Next, you will need to Choose the Destination that you would like to export the forensic image and Name the Image.



### 2\. Volatility tool:

###### &#x20;                            > It is an open-source memory forensics framework used primarily in cybersecurity for incident response and malware 

###### &#x20;                              analysis. It allows investigators to analyze a snapshot of a computer's volatile data (RAM) to extract running 

###### &#x20;                              processes, active network connections, clipboard contents, and passwords.

#### \# Why to use ?

###### &#x20;  > Malware Detection: Identifies hidden processes, rootkits, and malicious code injected into memory.

###### &#x20;  > Artifact Extraction: Recaves deleted files, screenshots, and SSL keys directly from RAM.

###### &#x20;  > OS Support: Capable of parsing memory dumps across Windows, Linux, and macOS systems.



#### 

### \*\* DNS(Domain Name Server):

###### &#x20;    > The Domain Name System (DNS) is the "phonebook of the Internet." It automatically translates human-readable domain names (like     

###### &#x20;      example.com) into machine-readable numerical IP addresses (like 192.0.2.1), allowing your browser to load Internet resources.

###### 

#### \#how DNS work:

###### &#x20;> The Query: Your device asks a DNS resolver (usually provided by your Internet Service Provider) for the IP address.

###### &#x20;> Root \& TLD Servers: If the resolver doesn't know the address, it queries a "Root" server, which points it to a Top-Level Domain (TLD) server 

###### &#x20;  (like .com or .org).

###### &#x20;> Authoritative Server: The TLD server directs the query to the Authoritative Name Server, which holds the exact IP address for that specific  

###### &#x20;  domain.

###### &#x20;> Resolution: The IP address is sent back to your browser, establishing the connection.



