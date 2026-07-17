### Assignment:

###### Draw a diagram of a modern CI/CD software pipeline (Plan, Code, Build, Test, Release, Deploy). For each stage, write a 1-sentence description of a security control you would add to ensure the code remains secure (e.g., "Code Stage: Implement an IDE plugin that warns developers if they use

###### insecure functions like MD5 hashing").

###### 

###### ans) Secure CI/CD Pipeline



###### +---------+    +---------+    +---------+    +---------+    +-----------+    +---------+

###### |  PLAN   | -> |  CODE   | -> |  BUILD  | -> |  TEST   | -> |  RELEASE  | -> | DEPLOY  |

###### +---------+    +---------+    +---------+    +---------+    +-----------+    +---------+

###### &#x20;    |               |              |              |               |               |

###### Threat         IDE Security    Dependency      SAST/DAST     Digital         IAM Roles,

###### Modeling        Plugin          Scanning         Testing     Signatures       Monitoring



###### |   CI/CD Stage   | Security Control                                                                                                                                              

###### 

###### |     Plan        | Perform threat modeling and define security requirements before development begins to identify potential risks 

###### &#x20;                   early.

###### &#x20;                                                      

###### |    Code         | Implement an IDE security plugin that warns developers when they use insecure functions such as MD5 hashing or 

###### &#x20;                   hardcoded credentials.                     

###### 

###### |    Build        | Use Software Composition Analysis (SCA) tools to detect vulnerable third-party libraries and dependencies during the 

###### &#x20;                   build process.                                      

###### 

###### |   Test          | Integrate Static Application Security Testing (SAST) and Dynamic Application Security Testing (DAST) to 

###### &#x20;                   automatically identify security vulnerabilities before release. 

###### 

###### |   Release       | Digitally sign build artifacts and verify their integrity to ensure only trusted software is released. 

###### &#x20;                                                                    

###### |   Deploy        | Deploy using least-privilege IAM roles, enable continuous security monitoring, and scan the production environment 

###### &#x20;                   for misconfigurations.                                   



