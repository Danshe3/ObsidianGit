#section4 #cybersecurity 
## ARP (Address Resolution Protocol):
- Translates IP Addresses into MAC Addresses.
	- OSI Data/Network Layer or Network/Internet Layer.

[^1]<span class="red-bg">ARP (cache) Poisoning:</span> An attacker sends fake responses to ARP requests, often done repeatedly for critical ARP entries (Default Gateway).
[^1]<span class="red-bg">RARP (Reverse ARP):</span> is used by disk-less workstations to get IPs.

## ICMP (Internet Control Message Protocol):
- Used to help IP, for Ping (Echo request/reply) and TTL Exceeds in Trace-route.
- An ICMP Echo Request is sent to the IP, which then sends an ICMP reply back (or not).

**Tracer-route:** Uses ICMP to trace a network route.
	We send a message with TTL 1.
		The first router decrements the TTL to 0 and sends an ICMP Time Exceed message back, First Hop is now identified.

## HTTP and HTTPS - Transport HTML data.
**HTTP (Hypertext Transfer Protocol):** Uses TCP port 80 (8008 and 8080), unencrypted website data sent across the internet.
**HTTPS (HTTP Secure):** Uses TCP port 443 (8443), encrypted data sent over the internet.

## DHCP (Dynamic Host Configuration Protocol)
The common protocol we use to assign IPs. Controlled by a DHCP Server for your environment.


[^1]: <span class="red-bg">Red Highlights</span> are attacks, virus or hacking methods. 
