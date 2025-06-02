In this task, I used Wireshark to capture live network traffic from my active Wi-Fi interface. The captured packets show communication between various devices and services using different network protocols.

Key observations from the capture include:

ARP (Address Resolution Protocol) packets were used to identify the MAC addresses of devices on the local network.

IGMPv3 (Internet Group Management Protocol) packets indicated devices joining multicast groups.

TCP (Transmission Control Protocol) packets showed connections to port 443, which is commonly used for secure HTTPS communication.

DNS (Domain Name System) queries were sent to resolve domain names like assets.msn.com.

DHCP (Dynamic Host Configuration Protocol) was used to request IP address configuration from the network.

The capture demonstrates real-time traffic flow and includes at least three different protocols: ARP, TCP, and DNS. This exercise improved my understanding of how data is transmitted over networks and how Wireshark can be used for troubleshooting and protocol analysis.
