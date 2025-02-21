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

## IPv4 (Internet Protocol version 4)
addresses:
	IPv4 addresses are made up of 4 octets (dotted-decimal notation) and broken further down in a 32bit integer binary.
		_It is easier to remember “google.com” than it is to remember 66.102.12.231 or 2607:f8b0:4007:80b::200e_
## IPv6 (Internet Protocol version 6)
- IPv6 is 128bit in hexadecimal numbers (uses 0-9 and a-f).
- 8 groups of 4 hexadecimals, making addresses look like this:
	_fd01:fe91:aa32:342d:74bb:234c:ce19:123b_
- IPSec is built in, not bolted on like with IPv4


**Public IP Addresses** (Internet routable addresses):
- Used to communicate over the internet between hosts.
**Private Addresses** (RFC 1918- Not routable on the internet): Other notable IP spaces:

| 10.0.0.0    | 10.255.255.255  | 16777216 | 127.0.0.0/8 Loopback IPs  |
| ----------- | --------------- | -------- | ------------------------- |
| 172.16.0.0  | 172.31.255.255  | 1048576  | 169.254.0.0/16 Link-Local |
| 192.168.0.0 | 192.168.255.255 | 65536    | 255.255.255.255 Broadcast |
