#cybersecurity #section4 

A unique identifier on the network card.
EUI/MAC-48 are 48bits (original design).
	The first 24 are the manufacturer identifier.
	The last 24 are unique and identify the host.

<span class="yellow-bg"> | 58 | 8D | 09 </span> | <span class="blue-bg"> A5 | 54 | BA </span>
<span class="yellow-bg">UOI (Organization Unique Identifier)</span>  <span class="blue-bg">UAA/Device Identifier</span>

<span class="yellow-bg"> | 58 | 8D | 09 </span> | <span class="blue-bg"> FF | FE | A5 | 54 | BA </span>
<span class="yellow-bg">UOI (Organization Unique Identifier)</span>  <span class="blue-bg">UAA/Device Identifier</span>

First deployed for production in the ARPANet in 1983, ARPANet later became the internet.
IPv4 is a connection less protocol for use on packet-switched networks.

IPv4 has around 4.2 billion IP addresses and of those ~4 billion are usable internet addresses.
	**IPv4** has 4,294,967,296 addresses where 
	**IPv6** has 340,282,366,920,938,463,463,374,607,431,768,211,456

When we send traffic, we use both the Source IP and Port as well as Destination IP and Port.
The **IP addresses** can be seen as the number of an apartment building.
	The **Port number** is your apartment number.

## PORTS

**Well-known Ports:**
	0 - 1023: Mostly used for protocols.
**Registered Ports:**
	1024 - 49151: Mostly used for vendor specific applications.
**Dynamic, Private or Ephemeral Ports:**
	49152 - 65535: Can be used by anyone for anything.

## **Common Ports:**

| PORT | Type    | Definition                                                           |
| ---- | ------- | -------------------------------------------------------------------- |
| 20   | TCP     | FTP data transfer.                                                   |
| 21   | TCP     | FTP control.                                                         |
| 22   | TCP/UDP | Secure Shell (SSH).                                                  |
| 23   | TCP     | Telnet unencrypted text communications                               |
| 25   | TCP     | Simple Mail Transfer Protocol (SMTP), can also use Port 2525         |
| 110  | TCP     | Post Office Protocol, version (POP3)                                 |
| 143  | TCP     | Internet Message Access Protocol (IMAP)                              |
| 80   | TCP/UDP | Hypertext Transfer Protocol (HTTP), can also use port 8008 and 8080. |
| 443  | TCP     | Hypertext Transfer Protocol over TLS/SSL (HTTPS)                     |
| 137  | UDP     | NetBIOS name Service, used for name registration and resolution.     |
| 138  | TCP/UDP | NetBIOS Datagram Service                                             |
| 3383 | TCP/UDP | Microsoft Terminal Server (RDP)                                      |

