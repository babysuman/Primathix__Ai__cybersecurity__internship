# \# Assignment:



### &#x20;                "The Journey of a Click"

##### The Prompt:

##### &#x20;         Imagine you are sitting at your laptop at home. You open your browser, type https://www.netflix.com, and press    

##### &#x20;         Enter.

##### 

##### Ques) Write a 1-page detailed explanation of exactly what happens in the background, step-by-step, from the moment you press    

##### &#x20;     Enter to the moment the movie selection screen appears.



##### Ans)When I sit at my laptop and type https://www.netflix.com into my web browser and press Enter, many things happen behind    

##### the scenes before the Netflix movie selection screen appears.



1. #### DNS resolution:

###### &#x20;   >Browser cache : the browser check if it already knows IP address from recent visits.

###### &#x20;   > OS cache: if not found then OS check its own local cache file.

###### &#x20;   > Recursive resolver: if not found, computer ask from internet service provider's dns server :"where is Netflix.com?"

###### &#x20;   > Root name server: the ISP server doesn't know, then it ask from global servers.

###### &#x20;   > TLD(top level server):the request come to TLD server for .com and send request to who manage Netflix.com

###### &#x20;   > Authoritative name server: the ISP asks to google public dns server and send IP address of www.netflic.com.





#### 2\. TCP/IP Connection establishment:

###### &#x20;     Now that the browser knows the server's IP address, it must establish a connection using the TCP/IP protocol. This is done through the TCP Three-Way Handshake:



###### > Syn: My computer send syn message to Netflix server.

###### > syn-ack: the Netflix server replies with syn-ack (synchronize acknowledge) message.

###### >Ack: my computer send an ack message back.



#### 3.HTTPs/TLS request:

###### Since the website uses HTTPS, the connection must be secured using TLS (Transport Layer Security).

###### >Hello: Browser says "let talks".

###### >certificate: server send its digital certificate.

###### >key exchange: they use complex math to agree on a secret , temporary key.

###### >A secure encrypted session is established.



#### 4.HTTP request:

###### > After the secure connection is ready, the browser sends an HTTP GET request to Netflix's server.

###### >The GET method is used because the browser is requesting data from the website.



#### 5.Response:

###### > The Netflix server processes the request and sends back an HTTP response.The server returns the status code:200 OK

###### >200 OK means:The request was successful and the requested content is being sent to the browser.



#### 6.Loading Netflix page:

###### > The server send html, css , javascript files. images and others resource. The browser downloads these files and begin rendering webpage.



#### 



##### 







