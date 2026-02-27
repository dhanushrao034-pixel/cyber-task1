# cyber-task1
This project demonstrates basic network reconnaissance by scanning a local network for open ports using Nmap. The task identifies active devices, analyzes open ports and services, and highlights potential security risks. It helps understand TCP SYN scanning, IP ranges, and fundamental network security concepts.
# 🔐 Task 1 – Scan Your Local Network for Open Ports

## 📌 Objective
The objective of this task is to learn how to discover open ports on devices within a local network. This helps understand network exposure and basic network reconnaissance techniques.

---

## 🛠 Tools Used
- Nmap
- --
🌐 Network Information

Local IP Address: 192.168.1.5
Network Range: 192.168.1.0/24
---
⚙️ Procedure

Installed Nmap from the official website.

Found the local IP address using the command:
ipconfig
Identified the network range (192.168.1.0/24).

Performed a TCP SYN scan using the command:
nmap -sS 192.168.1.0/24
Observed the devices connected to the network and noted the open ports.

Saved the scan results using:
nmap -sS 192.168.1.0/24 -oN scan-results.txt
---
📊 Scan Results 
| IP Address  | Open Port | Service |
| ----------- | --------- | ------- |
| 192.168.1.1 | 80        | HTTP    |
| 192.168.1.5 | 445       | SMB     |
| 192.168.1.8 | 22        | SSH     |
---

⚠️ Security Risks of Open Ports

Unauthorized access to services

Exposure to malware or cyber attacks

Data leakage through vulnerable services

Possibility of network intrusion
---
🔒 Recommended Security Measures

Close unused ports

Enable firewall protection

Keep systems updated

Monitor network traffic regularly
---
🧠 Key Concepts Learned
ort Scanning

TCP SYN Scan

IP Address Ranges

Network Reconnaissance

Basic Network Security
---
✅ Conclusion

This task helped in understanding how attackers and security professionals identify open ports in a network. Using Nmap, it was possible to discover devices and services running on the network. The exercise provided practical knowledge of basic network security and reconnaissance techniques.
