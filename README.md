Wireshark Lab - README File
🧠 Objective
To perform packet capture, analyze different network protocols using Wireshark, and understand key networking concepts through practical observation.
🧩 Steps Performed
1.	1. Installed Wireshark on Windows.
2.	2. Started packet capture on active network interface (Wi-Fi).
3.	3. Browsed multiple websites and executed ping commands to generate traffic.
4.	4. Stopped capture after 1 minute.
5.	5. Filtered packets using protocols like DNS, TCP, HTTP, and ICMP.
6.	6. Identified at least three different protocols in the capture.
7.	7. Exported the capture as a .pcap file (wireshark_task_windows.pcap).
8.	8. Summarized findings and analyzed packet details.
📊 Findings Summary
Protocol	Description	Packet Count	Example Info
DNS	Domain Name Resolution	10	Query: myntra.com → 104.74.11.45
TCP	Reliable transport connection	80	192.168.0.105:50632 → 104.74.11.45:443
HTTP/HTTPS	Web browsing traffic	40	Encrypted HTTPS session established
ICMP	Ping requests and replies	8	Echo request/reply with 8.8.8.8
ARP	Address resolution	5	Who has 192.168.0.1? Tell 192.168.0.105
📘 Interview Questions
9.	1. What is Wireshark used for?
Wireshark is a network protocol analyzer used to capture and inspect data packets for troubleshooting and analysis.
10.	2. What is a packet?
A packet is a small unit of data transmitted over a network, containing a header and payload.
11.	3. How to filter packets in Wireshark?
By using display filters like 'http', 'dns', or 'ip.addr == 192.168.1.10' in the filter bar.
12.	4. What is the difference between TCP and UDP?
TCP is connection-oriented and reliable, while UDP is connectionless and faster but unreliable.
13.	5. What is a DNS query packet?
A request sent from client to DNS server to resolve a domain name to an IP address (usually UDP port 53).
14.	6. How can packet capture help in troubleshooting?
It helps detect issues like dropped packets, latency, and unauthorized traffic.
15.	7. What is a protocol?
A set of rules that define how data is transmitted over a network (e.g., HTTP, TCP, DNS).
16.	8. Can Wireshark decrypt encrypted traffic?
Yes, but only if you have the encryption keys (e.g., TLS/SSL session keys or Wi-Fi passphrase).
🔑 Key Concepts
• Packet Capture – Recording network data packets using Wireshark.
• Protocol Analysis – Inspecting protocols and communication flow for errors or issues.
• TCP/IP – Core model governing network communication.
• Network Troubleshooting – Diagnosing network performance or security issues using packet data.
• Filtering – Narrowing down traffic to focus on specific protocols, IPs, or ports.
