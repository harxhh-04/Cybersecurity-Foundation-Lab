# Cybersecurity Foundation Lab Setup

## Overview
This project demonstrates the setup of a cybersecurity lab environment using Kali Linux and Metasploitable 2.  
The goal is to practice Linux, networking concepts, and security tools inside a safe virtual environment.

---

## Lab Environment

Virtualization Software:
- VirtualBox

Virtual Machines:
- Kali Linux (Attacker Machine)
- Metasploitable 2 (Vulnerable Target Machine)

Network Configuration:
- Host-Only Adapter
- Isolated network between Kali and Metasploitable

---

## Tools Used

- Nmap
- Wireshark
- Netcat
- OpenSSL

---

## Tasks Performed

### 1. Lab Setup
- Installed VirtualBox
- Imported Kali Linux VM
- Installed Metasploitable 2
- Configured Host-Only Network

### 2. Network Verification
- Checked IP address using `ifconfig`
- Verified connectivity using `ping`

### 3. Network Scanning
Used Nmap to scan the vulnerable machine.

Example command: nmap -sV <target_ip>


This shows open ports and services running on the system.

---

### 4. Packet Capture
Used Wireshark to capture network packets.

Steps performed:
- Started Wireshark capture
- Generated traffic using ping
- Filtered packets using `icmp`

---

### 5. Linux Practice
Basic Linux commands practiced:
pwd
ls
mkdir testlab
cd testlab
touch file.txt
chmod 777 file.txt


---

### 6. Cryptography Demonstration

Generated hashes using MD5 and SHA256.

Example:
echo "cybersecurity lab" | md5sum
echo "cybersecurity lab" | sha256sum


Also tested file encryption using OpenSSL.

---

## Screenshots

### Kali IP
![Kali IP](screenshots/2 — Start Both Machines kali.png)

### Ping Test
![Ping](screenshots/3 — Test Connectivity.png)

### Nmap Scan
![Nmap](screenshots/4 — Run Nmap Scan.png)

### Wireshark Capture
![Wireshark](screenshots/5 — Wireshark Capture.png)

## Key Learnings

- Virtual lab setup
- Linux command fundamentals
- Network scanning techniques
- Packet analysis
- Cryptography basics

---

## Disclaimer

This lab was created strictly for educational purposes.  
All testing was performed inside an isolated virtual environment.
