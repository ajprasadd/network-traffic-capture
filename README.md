# Network Traffic Capture and Analysis

📌 Project Overview
This project demonstrates capturing live network packets using **Wireshark**, filtering them by protocol, and analyzing their details.  
The purpose is to understand common network protocols and observe typical traffic patterns during normal internet usage.

---

 🎯 Objectives
- Capture live network packets from the active network interface.
- Identify at least **three different protocols**.
- Analyze packet details and summarize observations.
- Save the capture as a `.pcap` file for documentation.



 🛠 Tools Used
- **Wireshark v4.x** (Open-source network packet analyzer)
- Operating System: *[Your OS Name]*
- Internet connection for generating traffic



 📄 Steps Followed
1. Installed Wireshark on the system.
2. Started packet capture on the **active network interface** (Wi-Fi/Ethernet).
3. Generated network activity by:
   - Browsing websites
   - Pinging a known server
4. Stopped the capture after ~1 minute.
5. Applied protocol filters in Wireshark:
   - `http` → HTTP traffic
   - `dns` → DNS queries/responses
   - `tcp` → TCP packets
6. Saved capture as **`network_capture_task5.pcap`**.
7. Documented findings in a short report.

---

 📡 Protocols Identified

| Protocol | Purpose | Observation |
|----------|---------|-------------|
| **HTTP** | Transfers web content between client and server | Observed GET requests and HTTP/1.1 responses between local machine and remote server |
| **DNS**  | Resolves domain names into IP addresses | Queries to `8.8.8.8` for `google.com` and corresponding responses |
| **TCP**  | Ensures reliable, ordered data transfer | Observed TCP 3-way handshake (SYN, SYN-ACK, ACK) and segment data |


 📊 Summary
- **Total Packets Captured:** 17857
- Observed standard network behavior: HTTP for web browsing, DNS for name resolution, TCP as transport.
- All packets appeared normal with no suspicious or malformed traffic.



📂 Files in This Repository
Captured packet file
Summary report of findings
This documentation file

