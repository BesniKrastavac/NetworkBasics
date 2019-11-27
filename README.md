# NetworkBasics

Hubs – when client machine send data to hub, this data is propagated to every machine connected on hub
Switch – send data to a specific machine
LAN – local area network (computers connected on some small geographic location)
Internet – a bunch of lans connected using routers 
Network adapters – network cards, make possible to communicate via network (using RJ45 port. In those ethernet cables are plug in) wireless use antenna
WAP – wireless access points – data is transmitted across a wired network, but client machines are connected with switches (hubs, routers etc.) using antenna 
Data transfer – serial transfer (one bit at the time)
Data transfer rate in bits per second (Mega bits) – bit rate
Big amount of data is divided into segments. Each segment is wrapped with package and frame with additional information. This is all in binary.
Ip address (192.168.1.1) can be broken in two parts by subnet masks: network id 192.168.1, host id 1
There is 4 octets (8 bit) in ip address, so ip address is 32 bits
Subnet mask 255.255.255.0
Types of lans: WiredLans, WirelessLans and VirtualLans (based on function – physical location not important)
Perimeter networks – allows users to access perimeter network but not the lan which is connected to perimeter network
Network topology – defines physical connections of hosts (bus, star…
Ethernet – standard that defines how is data send and received between devices. When ethernet Is not used, the token ring is used
Devices that use ethernet standard transmits frames.
CSMA/CD, only one computer can send data at a time, so collision can be avoided.
Client server model – server provides data for client
Pear to pear – doesn’t have a server. 
OSI model:
-	Physical layer - communication subnetwork – cables, jacks, hubs, topologies, serial data transfer, analog/digital encoding (bits)
-	Data link layer - communication subnetwork – network interfaces cards, (frames) (makes sure that data is transferred properly) (layer 2 switching)
-	Network layer - communication subnetwork (layer 3 switching)
-	Transport layer – make sure that messages are delivered error free in sequence (segments or messages)
-	Session layer
-	Presentation layer
-	Application layer
Modular structure (independent layer protocols)
Layer 2 switching:
-	100base-t (ethernet standard – 100 mb/s, base band, twisted-pair cabling)
-	MAC addresses (media access control) six octets in hex (example: 00:a2:f1:23:32:9c) first three references  manufacturer and other three the address.
-	Switches use MAC addresses to establish point to point connection.
-	Layer 2 switch is common type switch
-	Switch store MAC addresses in its memory 
Layer 3 switching:
-	Translates logical addresses into to physical addresses
-	Ip protocol is network layer protocol
-	Routers ip switches
-	Ip addresses and subnets
-	Packets
-	Layer 3 switches are using ip addresses for switching
Layer 4:
-	Connection oriented communications – with acknowledgment and confirmation (TCP protocol – web browsing)
-	Connectionless communications – no … (UDP – movie or audio)
-	http default port 80
Layer 5:
-	session layer
-	netbios protocol
Layer 6:
-	presentation layer
-	responsible for security, data compression, data encryption
Layer 7
-	application layer
-	where message creation begins
-	ftp, smtp
TCP/IP model (only 4 layers, no physical layer)
-	application layer
-	transport layer
-	internet layer
-	network interface
Cables:
-	twisted pair (8 wires – 4 pairs, limit to 100 meters)
-	fiber optic (transfer data using light)
Ultra fast cable, glass fiber
Wireless repeater: repeat the signal to extend range
Wireless bridge: using different technologies to to connect devices
Ways to connect wirelessly:
-	Add-hoc mode wireless communication – pear to pear network, each device with the other
-	Infrastructure mode wireless communication – clients connect to wap (wireless access point, ssid is used to connect)
Protect wireless data with encryption protocols.
Internet protocol IP: network layer, ip addresses help devices to send and receive data
-	Ip addresses consists of 4 octets (127.0.0.1) one octet = one byte
-	There are public (exposed on the internet) and private (not exposed)
-	There are static and dynamic ip addresses.
Network address translation - modifying while in transit.
Default gateway – provides default route for TCP/IP hosts 
DNS – domain name system – translates name into ip address. Type name, returns ip
Subnetting – dividing network into smaller logical subnetworks
Ipv4:
-	Classless inter-Domain routing(CIDR)
Ipv6:
-	Solves many limitations of ipv4 (ipv4 32bit system, ipv6 128bit-system, ipv6 allows a lot more different addresses)
-	Are represented as 8 groups of 4 hexadecimal digits
-	Example: 2001:4860:0000:2001:0000:0000:0000:0068
Ipv4 can be translated to ipv6

Commands for cmd:
Ipconfig – current config
Ping – check another ip
Tracert – trace the data path
Netstat – active tcp connections
Pathping – combination of ping and tracert

DHCP – protocol that enables obtaining ip addresses automatically
DHCP sessions use DORA process. Discovery, offer, request, acknowledge
Rds – remote desktop services (one of the ways to connect to other computer)
DNS – is a part of tcp/ip reference model
WINS – also name resolution service
Static routing – the same route every time (if some router on route is down, connection cannot be established)
Dynamic routes – new routes are added automatically. 
Dynamic routing protocol – routing information protocol, open shortest path first…
Wide area network – connect multiple lan. (example: internet)
Packet switching (wan data travel – data is broken into little pieces, transferred, at the destination reassembled. )
Internet – worldwide system of connected computers (devices use tcp/ip protocol)
World wide web – enormous system of interlinked hypertext documents, current version is 2.0
Intranet – private network inside internet
Extranet – it is similar, but it is available
Virtual private network – virtual connection with private network. A tunnel is created for communication to pass through. Uses data encapsulation and encryption
VPN protocols – point to point, layer two tunneling protocol
Security devices and zones – firewall – protect network, inspect for malicious data, perform filtering. There are hardware and software firewalls
