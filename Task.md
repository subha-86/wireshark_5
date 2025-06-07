# Objective:
Capture live network packets and identify basic protocols and traffic types.

# Detailed objective:
The objective of this experiment is to gain hands-on experience with network traffic analysis using Wireshark, a widely-used packet analyzer tool. By capturing and examining real-time network traffic on a local machine, the goal is to develop an understanding of how different network protocols operate, how data is transmitted over networks, and how to recognize common types of traffic such as HTTP, DNS, and TCP.  
This activity will involve:
- Setting up Wireshark to monitor an active network interface,
- Generating typical network traffic by interacting with internet services (e.g., browsing a website or using the ping command),
- Filtering and identifying packets based on protocols
- Exporting the captured data as a .pcap file,
- And finally, analyzing and documenting the observed protocols, their purpose, and key details of sample packets.


# Tools and Description:

### Wireshark   
Wireshark is a network protocol analyzer — a powerful tool used to capture and inspect data packets traveling across a network. It's widely used by network administrators, cybersecurity professionals, and developers to troubleshoot network issues, analyze traffic, and detect suspicious activity.
#### Key Features of Wireshark:
- Packet Capture: Captures live network traffic in real time.
- Detailed Analysis: Breaks down packets to show protocol layers (Ethernet, IP, TCP, HTTP, etc.).
- Filtering: Lets you apply filters to see only specific types of traffic (e.g., http, ip.addr == 192.168.1.1).
- Color Coding: Highlights packets with different colors for quick identification.
- Exporting: Save captured data in .pcap format for later analysis.

### Common Use Cases:
- Troubleshooting: Find out why a network connection is slow or failing.
- Security Auditing: Detect malicious packets or unauthorized traffic.
- Learning: Study how different network protocols work.
- Reverse Engineering: Analyze unknown or custom protocol behavior.






