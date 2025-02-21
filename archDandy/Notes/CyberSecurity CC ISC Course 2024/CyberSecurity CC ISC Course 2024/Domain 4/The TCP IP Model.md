#section4 #cybersecurity 

## **The TCP/IP Model (Internet Protocol Suite):**
- A conceptual model that provides end-to-end data communication.
- From lowest to highest:
	- **The link layer,** containing communication methods for data that remains within a single network segment.
	- **The internet layer,** connecting independent networks, thus providing inter networking.

| **TCP/IP Model<br>(DOD) Model** | Application Layer        |                          |                           | Transport Layer      | Link and Physical Layer |                        |
| ------------------------------- | ------------------------ | ------------------------ | ------------------------ | -------------------- | ----------------------- | ---------------------- |
| **OSI model**                   | Application<br>Layer (7) | Application<br>Layer (6) | Application<br>Layer (5) | Network<br>Layer (3) | Data Link<br>Layer (2)  | Physical <br>Layer (1) |

##### **The link and physical layer** 
has the networking scope of the local network connection to which a host is attached.
- Used to move packets between the Internet layer interfaces of two different hosts on the same network.
- The link and physical layer = OSI layer 1 - 2

##### **Internet/Internet-work layer (Continue):**
The Internet Protocol performs two basic functions:
- **Host addressing and identification:** This is done with a hierarchical IP addresses.
- **Packet Routing:** Sending the packets of data (datagrams) from the source to the destination by forwarding them to the next network router closer to the final destination.
- 
##### **The transport layer** 
establishes basic data channels that applicaitons use for task-specific data exchange.
- Data is sent connection-oriented (TCP) or connectionless (UDP).
- The transport layer = OSI layer 4.

##### **The application layer**
includes the protocols used by applications for providing user services or exchanging applications data over the network (HTTP, FTP, SMTP, DHCP, IMAP).
- The TCP/IP reference model distinguishes between **user protocols** and **support protocols.**
- The application layer = OSI layer 5, 6, and 7.

