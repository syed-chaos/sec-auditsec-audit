# 🛡️ SEC AUDIT — System Security Auditor

```text
 _____ __   __ _____  _____ 
/ ____|\ \ / /|  ___||  __ \
| (___  \ V / | |__  | |  | |
 \___ \  | |  |  __| | |  | |
 ____) | | |  | |___ | |__| |
|_____/  |_|  |_____||_____/ 

  ____  _   _    _    ___  ____  
 / ___|| | | |  / \  / _ \/ ___| 
| |    | |_| | / _ \| | | \___ \ 
| |___ |  _  |/ ___ \ |_| |___) |
 \____||_| |_/_/   \_\___/|____/
Made by SYED._.CHAOS 
⚠️ Use only on systems you own or have explicit permission to audit.

📌 What is this?

SEC AUDIT is a Python-based security auditing tool for Kali Linux and other Debian-based systems. It scans your own PC across 10 security categories and gives you a score out of 100, a grade, and a detailed list of weak points with fix commands. 

🔍 What it checks
#	Category	Max Score
1	🔥 Firewall Status	10
2	🌐 Open / Risky Ports	10
3	🔐 SSH Configuration	15
4	👤 User Accounts	10
5	📁 File Permissions (SUID/World-Writable)	10
6	🔄 Pending System Updates	15
7	⚙️ Running Services	10
8	💽 Disk Encryption	10
9	📋 Logging & Auditing	10
10	🧠 Kernel Hardening (sysctl)	10
💻 Requirements
Requirement	Details
OS	Kali Linux / Debian / Ubuntu
Python	3.6 or higher
Privileges	Run as root (sudo) for full scan
Library	pyfiglet (for big banner)
📦 Installation

Step 1 — Clone the repository:
Bash

git clone [https://github.com/syed-chaos/sec-audit.git](https://github.com/syed-chaos/sec-audit.git)
cd sec-audit

Step 2 — Install required library:
Bash
pip install pyfiglet --break-system-packages


Step 3 — Give execute permission:
Bash
chmod +x security_auditor.py

🚀 Usage
Bash
sudo python3 security_auditor.py

    ⚠️ Always run with sudo for deeper and more accurate scan results.

👤 Author

SYED._.CHAOS - GitHub: @syed-chaos 

📄 License

This project is licensed under the MIT License — free to use, modify, and distribute with credit.
Plaintext

MIT License
Copyright (c) 2026 SYED._.CHAOS
