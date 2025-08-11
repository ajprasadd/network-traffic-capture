Project Overview
This project involves capturing live network packets using Wireshark, identifying different network protocols, and analyzing their purpose and packet details. 
The goal is to observe normal network behavior and understand how various protocols interact during typical internet usage.

Objectives
Capture live network packets from the active network interface.
Identify at least three different protocols in the captured traffic.
Analyze packet details and summarize findings.
Save the captured traffic as a .pcap file for documentation.

Tools Used
Wireshark v4.x (Open-source network packet analyzer)
Operating System: windows OS

Steps Followed
Installed Wireshark on the system.
Started packet capture on the active network interface (Wi-Fi/Ethernet).

Generated network activity by:
Browsing websites
Performing a ping to a known server
Stopped the capture after ~1 minute.

Applied filters in Wireshark to identify specific protocols:
HTTP (http)
DNS (dns)
TCP (tcp)
Saved the capture as network_capture_task5.pcap.
Analyzed and documented protocol details.

Protocols Identified
Protocol	Purpose	Observation in Capture
HTTP	Transfers web content between client and server	GET request and HTTP response packets between local machine and remote web server
DNS	Resolves domain names to IP addresses	DNS queries to 8.8.8.8 for google.com and related responses
TCP	Provides reliable, ordered data transmission	Three-way handshake (SYN, SYN-ACK, ACK) and data packets for HTTP/DNS communication

Summary
Total Packets Captured: 17857
Observed normal network behavior without anomalies.
The TCP protocol was used as a transport layer for HTTP and DNS communications.
No suspicious or malformed packets were found.

Files Included
 Captured packet file
 Report summarizing analysis and findings
