# \# Assignment :

### 1\.  research about enum4linux or smbclient tool and dig axfr @<dns server> <domain.com>



### &#x20;   A) enum4linux:

###### &#x20;              > Enum4linux is a Kali Linux tool used to enumerate Windows and Samba systems over SMB and NetBIOS protocols. It extracts   

###### &#x20;                valuable data like user accounts, shares, group memberships, OS details, and password policies. It acts as a wrapper around    

###### &#x20;                standard Samba utilities (e.g., smbclient, rpcclient, net, nmblookup).



#### &#x20; #Basic syntax:

###### &#x20;                       | enum4linux \[options] <target\_ip> |



#### &#x20; #Common Options:

###### &#x20;       -a: Do all simple enumeration (Userlist, Shares, Group policy, Password Policy).

###### &#x20;       -U: Get user list.-S: Get share list.

###### &#x20;       -G: Get group and member list.-P: Get password policy information.

###### &#x20;       -o: Get OS information.

###### &#x20;       -r: Enumerate users via RID cycling (useful if blank guest sessions are disabled).

###### &#x20;       -u <username> -p <password>: Provide credentials for an authenticated scan.



#### &#x20;  # enum4linux in SMB enumeration(server message block):

###### &#x20;                  > enum4linux assists with SMB (Server Message Block) by acting as an automated wrapper that extracts hidden configurations

###### &#x20;                    from the protocol. It combines several separate tools—like smbclient, rpcclient, net, and nmblookup—into a single command   

###### &#x20;                    to thoroughly probe the target over ports 139 and 445.



##### &#x20;   "Exploiting Null Sessions"

###### &#x20;    The Mechanism: It automatically checks if the target server allows unauthenticated connections.

###### &#x20;    The Value: If a Null Session is active, enum4linux logs into the SMB server with a completely blank username and password "". This lets it   

###### &#x20;               extract deeply sensitive server data without needing credentials.



### &#x20;  B) smbclient tool:

###### &#x20;                           > smbclient is a command-line tool included in the Samba suite that allows you to interact with SMB/CIFS shares on   

###### &#x20;                             remote servers. It functions similarly to an FTP client, letting you browse directories, list contents, and 

###### &#x20;                             download or upload files.



#### &#x20;         # Basic Syntax:

###### &#x20;                          | smbclient //<target\_ip>/<share\_name> \[options] |

&#x20;        

#### &#x20;         #Common Options:

###### &#x20;                       -U <username>: Specify the user account to connect with.

###### &#x20;                       -N: No password (suppresses the password prompt, useful for anonymous/guest logins).

###### &#x20;                       -L: List all available shares on the target IP without connecting to a specific one.

###### &#x20;                       -p <port>: Change the target port (default is 445).

###### &#x20;                       -c <command>: Run a specific command directly from your terminal and exit immediately.



### &#x20;  C) dig axfr @<dns server> <domain.com>:

###### &#x20;                      > The dig axfr command attempts a DNS Zone Transfer (AXFR). It asks a specific DNS server to copy the entire database of   

###### &#x20;                        records for a domain.To run it, replace <dns server> with the target's primary name server (e.g., ns1.example.com or 

###### &#x20;                        its IP) and <domain.com> with the zone.

#### &#x20;       

#### &#x20;     "DNS Enumeration (Port 53 - Domain Name System):"

###### &#x20;         > What it is: The internet's phonebook.

###### &#x20;         > The Exploit: A Zone Transfer Attack. Normally, DNS servers only give you the IP for one domain you ask for. But if misconfigured, an     

###### &#x20;                 attacker can ask for a "Zone Transfer," and the server will dump its \*entire database, revealing hidden internal subdomains.



##### &#x20;  # How It Works \& Security Implications:

###### &#x20;     > Purpose: AXFR is designed to replicate DNS records efficiently between primary and secondary (backup) name servers so administrators   

###### &#x20;                only have to edit records in one place.

###### &#x20;     > Security Risk: If a DNS server incorrectly allows zone transfers for unauthorized requesters, it creates a severe vulnerability.   

###### &#x20;                      Attackers can instantly map out an entire internal network, finding subdomains, mail servers, and hidden infrastructure.

###### &#x20;     > Modern Defense: Publicly facing DNS servers are configured by default to reject AXFR requests from non-whitelisted IPs using TSIG   

###### &#x20;                       (Transaction Signatures) or Access Control Lists (ACLs).









&#x20;      

