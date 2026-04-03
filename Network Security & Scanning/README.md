# 🔐 Task 2: Network Security & Scanning

## 📌 Objective
This project demonstrates network reconnaissance, scanning, vulnerability assessment, packet analysis, and firewall configuration using Kali Linux.

---

## 🛠 Tools Used
- Nmap
- OpenVAS (GVM)
- Wireshark
- hping3
- iptables

---

## 🧪 Lab Setup
- Attacker Machine: Kali Linux
- Target Machine: Metasploitable2
- Network: Host-only adapter

---

## 🔍 Steps Performed

### 1. Reconnaissance
- Used `whois` and `nslookup`
- Discovered active hosts using Nmap ping scan

### 2. Port & Service Scanning
- Identified open ports and services using Nmap
- Detected OS and service versions

### 3. Vulnerability Scanning
- Scanned target using OpenVAS
- Identified critical and high vulnerabilities

### 4. Packet Analysis
- Captured traffic using Wireshark
- Analyzed HTTP, FTP, and DNS packets
- Extracted credentials from FTP traffic

### 5. Firewall Configuration
- Configured iptables rules
- Blocked specific ports
- Verified using Nmap scan

---

## 📊 Results
- Multiple open ports detected (21, 22, 80, etc.)
- Vulnerabilities identified in services
- FTP credentials captured in plain text
- Firewall successfully blocked port access

---

## 🎯 Conclusion
This task helped in understanding real-world network security concepts including scanning, vulnerability assessment, and traffic analysis.

---

## 📁 Project Files
- `/report` → Detailed report
- `/screenshots` → Evidence images
- `/commands` → Commands used

---

## 🎥 Demo Video
(Add your LinkedIn video link here)

---

## 🔗 Author
Your Name
