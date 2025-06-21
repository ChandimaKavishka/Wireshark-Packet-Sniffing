🧪 Packet Sniffing and Analysis with Wireshark

This project demonstrates how to use **Wireshark** to capture, filter, and analyze real-time network packets. The goal is to understand how data travels over a network and uncover potential security risks.


🎯 Objective

To explore network behavior using Wireshark by:
- Capturing real-time traffic
- Filtering packets based on protocol
- Identifying DNS, HTTP, and other protocols
- Detecting any insecure traffic (e.g., unencrypted logins)


🛠️ Tools Used

- 💻 Operating System: Windows/Linux/Mac
- 🌐 Internet Browser: Chrome / Firefox
- 📦 Network Tool: [Wireshark](https://www.wireshark.org)

🔍 Analysis Summary

🧪 Protocols Found
- Ethernet
- IPv4
- TCP / UDP
- DNS
- HTTP

🌐 IP Addresses Observed
- Local IP (e.g.192.168.21.80)
- External IPs (e.g., Google's 142.250.67.163)

📡 DNS Queries (Top Examples)
- google.com
- nverssl.com

🔐 Security Observations
HTTP packets were detected (unencrypted)
POST requests found — may expose login credentials in plain text

 ⚠️ This highlights how attackers can steal credentials if HTTPS is not used.


📝 What I Learned

-How to capture real-time packets on a network
-The role of DNS, TCP, HTTP in network communication
- How attackers exploit insecure connections
- Importance of encryption (HTTPS) for web security
- How Wireshark can be used for network troubleshooting and cyber defense


