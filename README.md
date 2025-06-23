# 🛡️ Cyber Security Internship – Task 1: Port Scanning

This repository contains my completed work for **Task 1** of the Cyber Security Internship.

---

## 🎯 Objective
To perform a local network scan using **Nmap** to identify open and filtered ports, and understand potential security risks.

---

## 🔧 Tools Used
- **Nmap** (version 7.97)
- **Zenmap GUI** (for visual scans)
- **OS**: Windows
- **Target IP**: `192.168.1.103`

---

## 📁 Files Included

### 📝 [`Task 1.txt`](Task%201.txt)
Includes:
- Commands used
- Nmap scan outputs
- Explanations for each scan

### 📸 [`/screenshots`](screenshots/)
Captured output of each scan using Zenmap GUI:

| File Name                              | Description                          |
|----------------------------------------|--------------------------------------|
| `Screenshot 2025-06-23 175838.png`     | TCP SYN scan (`-sS`)                |
| `Screenshot 2025-06-23 181130.png`     | Fast scan (`-F`)                    |
| `Screenshot 2025-06-23 182306.png`     | Full port scan (`-p -`)             |
| `Screenshot 2025-06-23 182742.png`     | TCP Connect scan (`-sT`)            |

---

## 💻 Commands Used and Summary

nmap -F 192.168.1.103
nmap -p- 192.168.1.103
nmap -sS 192.168.1.103
nmap -sT 192.168.1.103

## 📚 Learning Outcomes
- Learned about open ports, TCP scanning, filtered ports.
- Understood how tools like Nmap and Wireshark are used in reconnaissance.
- Gained practical exposure in identifying network vulnerabilities.

---

## 🔗 Submission
GitHub repo link: _[https://github.com/AkashPawar122/task-1.git]_
