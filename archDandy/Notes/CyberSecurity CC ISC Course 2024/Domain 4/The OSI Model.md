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

**Layer 1 - Physical layer:**
	Wires, Fiber, Radio waves, hub, part of NIC, connectors.
	**Cable types** 
		- Copper TP (Twisted Pair) Least secure, eavesdropping, interference, easy tap into, but also cheap.
		- Fiber Optic si the Most secure
	**Topologies:**
		Bus, Star, Ring, Mesh partial/full.
	**Threats:**
		Data emanation, theft, eavesdropping, sniffing, interference.

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

