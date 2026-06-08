## \#Docker:

##### &#x20;           Docker is a set of products that uses operating system-level virtualization to    

##### &#x20;           deliver software in packages called containers. Docker automates the deployment    

##### &#x20;           of applications within lightweight containers, enabling them to run consistently   

##### &#x20;           across different computing environments.

&#x20;

###### &#x20;            >The core software that runs and manages these containers is called Docker Engine.

###### 

###### 

### \# History:

###### &#x20;    > Solomon Hykes started the Docker project in France as an internal project within dotCloud, a  

###### &#x20;      platform-as-a-service company.

###### &#x20;    > Docker was first released in 2013 and continues to be developed by Docker, Inc. The platform     

###### &#x20;      includes both free and paid tiers.

#### 

#### \# Design:

###### &#x20;          Containers are isolated from one another and bundle their own software, libraries and 

###### &#x20;  configuration files; they can communicate with each other through well-defined channels. Because  

###### &#x20;  all of the containers share the services of a single operating system kernel, they use fewer resources 

###### &#x20;  than virtual machines.

###### 

###### &#x20;  Docker can package an application and its dependencies in a virtual container that can, in principle,    

###### &#x20;  run on any Linux, Windows, or macOS computer. This enables the application to run in a variety of    

###### &#x20;  locations, such as on-premises, in public (see decentralized computing, distributed computing, and     

###### &#x20;  cloud computing) or private cloud.



#### \# Component:

###### &#x20;                 The Docker software as a service offering consists of three components:



* ##### Software:

###### &#x20;           The Docker daemon, called dockerd, is a persistent process that manages Docker containers and handles container objects.



* ##### Object:

###### &#x20;          Docker objects are various entities used to assemble an application in Docker. The main classes of Docker objects are images,    

###### &#x20;          containers, and services.



* ##### Register:

###### &#x20;         A Docker registry is a repository for Docker images. Docker clients connect to registries to download ("pull") images for use or      

###### &#x20;         upload ("push") images that they have built.







#### \# Docker bachend process: 

###### &#x20;                  Docker Engine is the core open-source technology for building and containerizing your applications. It uses a client-server 

###### &#x20;                  architecture to manage all Docker objects, like images, containers, and networks.

###### 

###### &#x20;                 > The three main parts of the Docker Engine are:

###### 

###### &#x20;                1. The server: A long-running daemon process (dockerd) that handles all the important tasks, such as creating, running, and  

###### &#x20;                               destroying containers.

###### &#x20;                2. APIs: Interfaces that allow programs, including Docker CLI, to communicate with and instruct the daemon.

###### &#x20;                3. The CLI client: The Docker command-line tool, which is the primary way for users to interact with the platform.              

