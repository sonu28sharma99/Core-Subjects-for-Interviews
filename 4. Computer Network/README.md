<details> <summary><b>
1.	DEFINE NETWORK 
</b></summary><br>
<b>Network</b>   :  
An inter-connection of multiple devices known as host, that are connected using multiple paths for the purpose of sending/receiving data.
</details>

---

<details> <summary><b>
2.	WHAT DO YOU MEAN BY NETWORK TOPOLOGY, AND EXPLAIN TYPES OF 	THEM 
</b></summary><br>
<b>Network Topography<b>:  
Layout arrangement of different devices in a network.

<b>Types of Topography<b>:

1.  _<b>Star<b>_  -- Star topology is a network topology in which all the nodes are connected to a single device known as a central device
2.  _<b>Ring<b>_  -- Ring topology is a network topology in which nodes are exactly connected to two or more nodes and thus, forming a single continuous path for the transmission.
3.  _<b>Bus<b>_  -- Bus topology is a network topology in which all the nodes are connected to a single cable known as a central cable or bus.
4.  _<b>Mesh<b>_  -- Mesh topology is a network topology in which all the nodes are individually connected to other nodes.
</details>

---

<details> <summary><b>
3.	DEFINE BANDWIDTH, NODE AND LINK ? 
</b></summary><br>
<b>Bandwidth<b>:  
Bandwidth is defined as the potential of the data that is to be transferred in a specific period of time. It is the data carrying capacity of the network or transmission medium.
</details>

---

<details> <summary><b>
4.	EXPLAIN TCP MODEL .. 
</b></summary><br>
<b>TCP/IP Model<b>:  
It is a compressed version of the OSI model with only 4 layers. It stands for Transmission Control Protocol/Internet Protocol. The layers are:

-   Process/Application Layer
-   Host-to-Host/Transport Layer
-   Internet Layer
-   Network Access/Link Layer
</details>

---

<details> <summary><b>
5.	LAYERS OF OSI MODEL 
</b></summary><br>
<b>Layers in OSI model<b>:  
It is a 7 layer architecture with each layer having specific functionality to perform. All these 7 layers work collaboratively to transmit the data from one person to another across the globe.

1.  _<b>Physical Layer<b>_  :

-   It is the lowest layer of the OSI reference model.
-   It is used for the transmission of an unstructured raw bit stream over a physical medium.
-   Physical layer transmits the data either in the form of electrical/optical or mechanical form.
-   The physical layer is mainly used for the physical connection between the devices, and such physical connection can be made by using twisted-pair cable, fibre-optic or wireless transmission media.

2.  _<b>DataLink Layer<b>_  :

-   It is used for transferring the data from one node to another node.
-   It receives the data from the network layer and converts the data into data frames and then attaches the physical address to these frames which are sent to the physical layer.
-   It enables the error-free transfer of data from one node to another node.

3.  _<b>Network Layer<b>_  :

-   Network layer converts the logical address into the physical address.
-   The routing concept means it determines the best route for the packet to travel from source to the destination.
-   Functions of Network Layer :
    -   Routing: The network layer determines the best route from source to destination. This function is known as routing.
    -   Logical addressing: The network layer defines the addressing scheme to identify each device uniquely.

4.  _<b>Transport Layer<b>_  :

-   It delivers the message through the network and provides error checking so that no error occurs during the transfer of data.
-   It provides two kinds of services:
    -   Connection-oriented transmission:  
        In this transmission, the receiver sends the acknowledgement to the sender after the packet has been received.
    -   Connectionless transmission:  
        In this transmission, the receiver does not send the acknowledgement to the sender.

5.  _<b>Session Layer<b>_  :

-   The main responsibility of the session layer is beginning, maintaining and ending the communication between the devices.
-   Session layer also reports the error coming from the upper layers.
-   Session layer establishes and maintains the session between the two users

6.  _<b>Presentation Layer<b>_  :

-   The presentation layer is also known as a Translation layer as it translates the data from one format to another format.
-   At the sender side, this layer translates the data format used by the application layer to the common format and at the receiver side, this layer translates the common format into a format used by the application layer.
-   Functions of Presentation Layer :
    -   Character code translation
    -   Data conversion
    -   Data compression
    -   Data encryption

7.  _<b>Application Layer<b>_  :

-   Application layer enables the user to access the network.
-   It is the topmost layer of the OSI reference model.
-   Application layer protocols are file transfer protocol, simple mail transfer protocol, domain name system, etc.
-   The most widely used application protocol is HTTP(Hypertext transfer protocol ). A user sends the request for the web page using HTTP.
</details>

---

<details> <summary><b>
6.	SIGNIFICANCE OF DATA LINK LAYER
</b></summary><br>
2.  _<b>DataLink Layer<b>_  :

-   It is used for transferring the data from one node to another node.
-   It receives the data from the network layer and converts the data into data frames and then attaches the physical address to these frames which are sent to the physical layer.
-   It enables the error-free transfer of data from one node to another node.
</details>

---

<details> <summary><b>
7.	DEFINE GATEWAY, DIFFERENCE BETWEEN GATEWAY AND ROUTER .. 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
8.	WHAT DOES PING COMMAND DO ? 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
9.	WHAT IS DNS, DNS FORWARDER, NIC, ? 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
10.	WHAT IS MAC ADDRESS ? 
</b></summary><br>
<b>Media Access Control (MAC) Address<b>:  
MAC Addresses are unique 48-bits hardware number of a computer, which is embedded into network card (known as Network Interface Card) during the time of manufacturing.  
MAC is a type og physical address which is used to communicate or transfer the data from one computer to another computer
</details>

---

<details> <summary><b>
11.	WHAT IS IP ADDRESS, PRIVATE IP ADDRESS, PUBLIC IP ADDRESS, APIPA ? 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
12.	DIFFERENCE BETWEEN IPV4 AND IPV6
</b></summary><br>
_<b>Differences between IPv4 and IPv6<b>_:


| IPv4      | IPv6 |
| ----------- | ----------- |
| IPv4 has a 32-bit address length      | IPv6 has a 128-bit address length       |
| Address representation of IPv4 is in decimal   | Address Representation of IPv6 is in hexadecimal |
| It Supports Manual and DHCP address configuration   | It supports Auto and renumbering address configuration |
| In IPv4 Encryption and Authentication facility not provided   | In IPv6 Encryption and Authentication are provided |
</details>

---

<details> <summary><b>
13.	WHAT IS SUBNET ? 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
14.	FIREWALLS 
</b></summary><br>
<b>Firewall<b>:  
The firewall is a network security system that is used to monitor the incoming and outgoing traffic and blocks the same based on the firewall security policies. It acts as a wall between the internet (public network) and the networking devices (a private network). It is either a hardware device, software program, or a combination of both. It adds a layer of security to the network
</details>

---

<details> <summary><b>
15.	DIFFERENT TYPE OF DELAYS 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
16.	3 WAY HANDSHAKING 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
17.	SERVER-SIDE LOAD BALANCER
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
18.	RSA ALGORITHM 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
19.	WHAT IS HTTP AND HTTPS PROTOCOL ? 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
20.	WHAT IS SMTP PROTOCOL ? 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
21.	TCP AND UDP PROTOCOL, PREPARE DIFFERENCES
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
22.	WHAT HAPPENS WHEN YOU ENTER “GOOGLE.COM” (VERY VERY FAMOUS 	QUESTION) 
</b></summary><br>
_<b>What happens when you hit an URL<b>_: (<b>THIS IS THE MOST IMP QUESTION OF ALL<b>)

-   A URL may contain a request to HTML, image file or any other type.
-   If the content of the typed URL is in the cache and fresh, then display the content.
-   Else find the IP address for the domain so that a TCP connection can be set up. Browser does a DNS lookup.
-   Browser needs to know the IP address for a URL so that it can set up a TCP connection. This is why browser needs DNS service. The browser first looks for URL-IP mapping browser cache, then in OS cache. If all caches are empty, then it makes a recursive query to the local DNS server. The local DNS server provides the IP address.
-   Browser sets up a TCP connection using three-way handshake.
-   Browser sends a HTTP request.
-   Server has a web server like Apache, IIS running that handles incoming HTTP request and sends an HTTP response.
-   Browser receives the HTTP response and renders the content.

<b>NB<b>: I have tried to list down some very important topics from Computer Networks (from interview point), which I have personally faced or I got from some sources. CN is a subject which is comparatively less asked in interviews but may play a very vital role in your selection.  
</details>

---

<details> <summary><b>
23.	HUB VS SWITCH 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
24.	VPN, ADVANTAGES AND DISADVANTAGES OF IT 
</b></summary><br>
Well, you asked for it!
</details>

---

<details> <summary><b>
25.	LAN
</b></summary><br>
Well, you asked for it!
</details>
