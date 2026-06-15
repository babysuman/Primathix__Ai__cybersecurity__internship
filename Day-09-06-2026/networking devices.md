# \#Common Networking devices:



* ### Networking devices:

###### &#x20;       >  Network Devices are the physical appliances required for communication and interaction between computers on a computer network.

###### 

###### &#x20;       > Enable communication by transmitting and receiving data between devices.

###### &#x20;

###### &#x20;       > Allow devices to connect to networks efficiently and securely.

###### 

###### &#x20;       > Improve network performance by reducing congestion and managing traffic.

###### &#x20;

###### &#x20;       > Extend network coverage and solve signal loss or attenuation problems.

#### 

1. #### Switch:

###### &#x20;           > A switch is a high-speed networking device that connects devices (computers, printers, servers) within a Local Area Network (LAN).

###### &#x20;           > Unlike hub, switch learns the MAC address of every connected device.

###### &#x20;           > It sends data only to the specific port where the destination device is connected.

###### &#x20;           > Reduces collisions and improves security and speed.



#### 2\. Hub:

###### &#x20;         > It is a central connection point for devices in a LAN.

###### &#x20;         > It takes an incoming signal on one port and blindly broadcasts it to all other ports without knowing the recipient.

###### &#x20;         > High network traffic collisions and security risks (everyone sees everyone's data).

###### &#x20;         > It is a obsolete device, replaced by Switches.



#### 3\. Routers:

###### &#x20;            > It is a networking device that connects multiple networks and directs data packets between them using IP addresses.

###### &#x20;            > It uses IP Addresses to determine the best path for data packets to travel.

###### &#x20;            > It maintains a Routing Table to make these decisions.

###### &#x20;            > Routers stop broadcast traffic, isolating networks from each other.



#### 4\. Bridge:

###### &#x20;            > This connects two separate LAN segments to make them appear as one.

###### &#x20;            > Filters traffic based on MAC addresses to keep local traffic local, reducing congestion.

###### &#x20;            > Largely replaced by Switches (which are essentially multi-port bridges).



#### 5\. Gateways:

###### &#x20;             > It is a hardware device or software node that acts as an entry/exit point between two distinct networks using different    

###### &#x20;               protocols, translating data to ensure compatibility.

###### &#x20;             > It can convert protocols, data formats, or architectures (e.g., connecting a TCP/IP network to a legacy Mainframe network).

###### &#x20;             > An Internet Gateway translates your private LAN requests into public internet requests.



#### 6.Repeater:

###### &#x20;             > It regenerates signals to extend the range of a network.

###### &#x20;             > It receives a weak signal (due to attenuation over long cables), amplifies it, and retransmits it.

###### &#x20;             > Extending Wi-Fi range or Ethernet cables beyond 100 meters.



#### 7.Modem (Modulator-Demodulator):

###### &#x20;                      > This bridges the gap between digital computer data and analog signals, allowing devices to connect to the internet via

###### &#x20;                        telephone, cable, or fiber lines.

###### &#x20;                      > Connects your home network to the ISP (Internet Service Provider).

###### &#x20;                      > Converts digital signals from your computer into analog signals for telephone/cable lines (Modulation) and vice-versa

###### &#x20;                        (Demodulation).



#### 8\.  Access Point (AP):

###### &#x20;                      > It is a networking hardware device that allows Wi-Fi-enabled devices, such as laptops and smartphones, to connect to a

###### &#x20;                        wired network.

###### &#x20;                      > Acts as a bridge between wired Ethernet and wireless Wi-Fi devices.

###### &#x20;                      > An AP only provides Wi-Fi signal and it does not route traffic or assign IP addresses.





## \# TCP and UDP differences:

|**Features**|**TCP(transmission control protocol)**|**UDP(user datagram protocol)**|
|-|-|-|
|1. Reliability|High (guarantees delivery via retransmission).|Low (no guarantee of delivery).|
|2.Speed|Slower (higher overhead and error checking).|Faster (minimal overhead).|
|3.Connection Type|Connection-oriented (requires a handshake to begin).|Connectionless (sends data directly to the recipient).|
|4.ordering|Arrives in the exact order they were sent.|Packets can arrive out of order.|
|5.Error Checking|Extensive (lost packets are resent).|Minimal (drops corrupted packets without asking to resend).|
|6.Broadcasting and multicasting|Does not support broadcasting or multicasting.|Supports broadcasting and multicasting.|
|7. Use for|Applications where accuracy is critical and no data can be missing.|Time-sensitive applications.|
|8.Example|Web browsing, emails, downloading files.|Live video streaming, online gaming.|



