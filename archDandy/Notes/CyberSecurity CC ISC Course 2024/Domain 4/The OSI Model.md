#section4 #cybersecurity 
#### **The OSI Model (Open Systems Interconnect):** 
A layered network model that standardizes the communication functions of a telecommunication or computing system regardless of their underlying internal structure and technology.
This model has 7 layers:

| Osi Layer          | Protocol Data Unids (PDU) | TCP/IP Model            |
| ------------------ | ------------------------- | ----------------------- |
| Physical layer     | BITS                      | Link and Physical Layer |
| Data Link layer    | FRAMES                    | Link and Physical Layer |
| Network layer      | PACKETS                   | Internetwork Layer      |
| Transport layer    | SEGMENTS                  | Transport Layer         |
| Session layer      | DATA                      | Application Layer       |
| Presentation layer | DATA                      | Application Layer       |
| Application layer  | DATA                      | Application Layer       |

	**7-1** All people seem to need data processing.
	**1-7** Please Do Not Throw Sausage Pizza Away.
___
**Layer 1 - Physical layer:**
	Wires, Fiber, Radio waves, hub, part of NIC, connectors.
	**Cable types** 
		- Copper TP (Twisted Pair) Least secure, eavesdropping, interference, easy tap into, but also cheap.
		- Fiber Optic si the Most secure
	**Topologies:**
		Bus, Star, Ring, Mesh partial/full.
	**Threats:**
		Data emanation, theft, eavesdropping, sniffing, interference.
___
**Layer 2 - Data Link Layer:**
	Transports data between 2 nodes connected to same network.
		LLC - Logical Link Control - error detection
	MAC address (BIA) - a unique identifier on the network card.
		* 48-bit hexadecimal first 24 manufacturer identifier, last 24 unique.
		* 64-bit hexadecimal first 24 manufacturer identifier, last 40 unique.
		* **Threats** - MAC Spoofing, MAC Flooding.
	**ARP (Address Resolution Protocol)** Layer 2/3
	**CSMA/CD** - Ethernet - minimized with switches vs. hubs.
	**CSMA/CA** - Wireless
	**Token passing** - Similar to the talking stick, not really used anymore.
___
**Layer 3 - Network Layer:**
	Expands to many different nodes (IP) - The Internet is IP based.
	**Protocols:**
		IP, ICMP, IPSEC, IGMP, IGRP, IKE, ISAKMP, IPX
	**Threats:** Ping of Death, Ping Floods, Smurf - spoof source and directed broadcast, IP modifications, DHCP attacks,...
___
**Layer 4 -  Transport layer:**
	**SSL/TLS** Layer 4 to 7.
	**UDP (User Datagram Protocol):**
		Connectionless protocol, unreliable, VOIP, Live video, gaming, "real-time".
	**Attack: Fraggle attack**  
		works the same way as smurf but may be more successful since it uses UDP and not ICMP.
	**TCP (Transmission Control Protocol):**
		Reliable, Connection orientated, Guaranteed delivery, 3 way handshake, slower/more overhead, data reassembled.
	**Attacks: SYN floods**
		half open TCP sessions, client sends 1,000s of SYN request, but never the ACK.
___
 **Layer 5 - Session Layer:**
	 Establishes connection between 2 applications: 
	 Setup > Maintenance > Tear Down.
	 **Threats to level** 
		 Virus, worms, Trojans, buffer overflow, applications or OS vulnerabilities.
___
**Layer 6 - Presentation Layer:**
	- Only layer with no protocols.
	- Formatting, compressing, encryption (file level).
	**Threats to level** 
		Virus, worms, Trojans, buffer overflow, applications or OS vulnerabilities.
___
**Layer 7 - Application Layer:**
	Presents data to user (applications/websites).
	HTTP, HTTPS, FTP, SMTP, IMAP, POP, and many more.
	**Threats to level** 
		Virus, worms, Trojans, buffer overflow, applications or OS vulnerabilities.
___
![[OSI model - Open Systems Interconnection Reference model.canvas|OSI model - Open Systems Interconnection Reference model]]
