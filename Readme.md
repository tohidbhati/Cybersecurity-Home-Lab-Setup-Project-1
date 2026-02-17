🔐 Cybersecurity Home Lab – Multi-OS Environment
📌 Overview

This project documents the setup of a personal cybersecurity home lab designed to simulate real-world attack and defense scenarios using multiple Windows environments and an attacker machine.

The lab was built using virtualization and isolated networking to safely practice penetration testing techniques.

🛠️ Technologies Used

Kali Linux (Attacker machine)
<img width="1904" height="903" alt="Screenshot 2026-02-17 104507" src="https://github.com/user-attachments/assets/7dd8f1dd-ed81-4ca3-a42b-72377128b262" />
<img width="1904" height="853" alt="Screenshot 2026-02-17 104617" src="https://github.com/user-attachments/assets/9952884c-874b-4cae-b8af-8db5515d12e5" />

Windows XP
<img width="1919" height="1029" alt="Screenshot 2026-02-17 104712" src="https://github.com/user-attachments/assets/ca39daa0-85c9-4cdc-a5b2-7c583f983175" />

Windows 7

<img width="1894" height="1011" alt="Screenshot 2026-02-17 104934" src="https://github.com/user-attachments/assets/5ab90ac5-237f-4ec3-9bea-ebbf03d93268" />


Windows 10

<img width="1899" height="908" alt="Screenshot 2026-02-17 105201" src="https://github.com/user-attachments/assets/dcc41e14-4784-4589-bd08-65f7a7214f48" />

Metasploitable 2.0.0

<img width="1915" height="903" alt="Screenshot 2026-02-17 105113" src="https://github.com/user-attachments/assets/5c7de9a7-ee69-49ea-9f33-f54bcfee7b43" />

Windows Server 2016
<img width="1918" height="1027" alt="Screenshot 2026-02-17 105020" src="https://github.com/user-attachments/assets/c92c6986-1367-42f6-a02a-46dedfe377c2" />

VirtualBox
<img width="840" height="663" alt="Screenshot 2026-02-17 105957" src="https://github.com/user-attachments/assets/c6b361ae-708c-4e99-bc29-8e09b30541d1" />

Internal Network (NAT + Host-only configuration)

🧱 Lab Architecture

Attacker (Kali Linux)
⬇
Internal Virtual Network
⬇
Multiple Windows target systems

Static IP assignment

Isolated environment (no external exposure)

Snapshot-based recovery

🔍 Skills Practiced

Network scanning & enumeration

Service and OS fingerprinting

Vulnerability identification

Exploitation of legacy systems

Post-exploitation basics

Documentation & reporting

🧠 Key Learnings

Security differences between legacy and modern Windows systems

Attack surface analysis

Importance of patch management

Structured penetration testing workflow

🚀 Future Enhancements

Active Directory domain setup

SIEM integration

Vulnerable web apps (DVWA, Juice Shop)

Blue team monitoring scenarios
