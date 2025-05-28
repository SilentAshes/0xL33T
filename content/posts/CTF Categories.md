---
date: '2025-05-28T10:50:33+03:00'
draft: false
title: 'CTF Categories'
tags:
  - 0xAshes
  - Roadmap
author: 0xAshes
---

To play Capture the Flag (CTF) competitions you'll need to build on your foundational knowledge in cybersecurity and develop hands-on skills in offensive and defensive techniques.CTFs often include **both red team (offensive)** and **blue team (defensive)** elements. Here's a structured path:

---

## 🔰 Core Knowledge (Must-Have)

Before diving into CTFs, make sure you're solid on:

- **Networking:** TCP/IP, UDP, DNS, HTTP(S), ARP, ICMP, ports & protocols.
    
- **Operating Systems:**
    
    - **Linux:** Bash, file permissions, process management, cron, logs.
        
    - **Windows:** CMD, PowerShell, registry, event logs, services.
        
- **Security Concepts:** CIA triad, malware types, firewalls, IDS/IPS, SIEMs.
    
- **Programming/Scripting Basics:**
    
    - Python (most common), Bash, PowerShell.
        
    - Regex (used often in puzzles and log analysis).
        
- **Log Analysis:** Syslog, Windows logs, firewall/DNS logs, SIEM usage.
    

---

## 🧩 CTF-Specific Skills by Category

### 1. **Forensics / Blue Team** 

- Memory analysis (e.g. using **Volatility**).
    
- PCAP/network traffic analysis (with **Wireshark**, **tcpdump**).
    
- File carving and recovery.
    
- Log correlation (Sysmon, Apache, Windows Event Logs).
    
- DFIR tools: Autopsy, FTK Imager, CyberChef.
    

### 2. **Cryptography** 

- Common ciphers: Caesar, Vigenère, XOR, RSA basics.
    
- Hash cracking: MD5, SHA1, with tools like **Hashcat**, **John the Ripper**.
    
- Encoding vs encryption: base64, hex, rot13, URL encoding.
    

### 3. **Web Exploitation**

- SQL Injection, XSS, SSRF, LFI/RFI.
    
- Cookie manipulation, JWT analysis.
    
- Tools: Burp Suite, OWASP ZAP, Postman, curl.
    

### 4. **Reverse Engineering** 

- Static & dynamic binary analysis.
    
- Tools: Ghidra, IDA Free, Binary Ninja (community edition), x64dbg.
    
- Basic assembly: x86/x64.
    

### 5. **Binary Exploitation / Pwn**

- Buffer overflows, format string vulnerabilities.
    
- GDB, pwndbg, pwntools (Python library for pwn challenges).
    

### 6. **Misc / OSINT / Stego** 

- Open-source intelligence (OSINT): usernames, emails, metadata.
    
- Steganography: tools like **zsteg**, **steghide**, **binwalk**, **exiftool**.
    

---

## 🛠️ Tools You Should Be Familiar With

- **Linux command line** (grep, awk, sed, strings, file, hexdump).
    
- **CyberChef** (Swiss army knife for encoding/decoding).
    
- **Ghidra/IDA/OllyDbg/x64dbg** (reverse engineering).
    
- **Burp Suite**, **Wireshark**, **Metasploit**, **Nmap**, **John the Ripper**, **Hashcat**.
    
- **Docker** (many CTFs provide containerized environments).
    

---

## 🎯 Recommended Platforms to Practice

- [Hack The Box](https://www.hackthebox.com/)
    
- [TryHackMe](https://tryhackme.com/)
    
- [picoCTF](https://picoctf.org/) (beginner-friendly)
    
- [CTFtime](https://ctftime.org/) (find upcoming events)
    
- OverTheWire
    
- [CyberDefenders](https://cyberdefenders.org/) (blue-team focused challenges)
    

---

## 📚 Learning Resources

- **Books:**
    
    - _The Web Application Hacker’s Handbook_
        
    - _Practical Malware Analysis_
        
    - _Blue Team Field Manual (BTFM)_
        
    - _The Art of Memory Forensics_
        
- **Courses:**
    
    - TryHackMe: SOC Analyst, Blue Team Path, Advent of Cyber.
        
    - TCM Security: Practical SOC Analyst, Practical Network Penetration Tester.
        
    - SANS Courses (if you have budget): FOR500, SEC504, SEC401.
        
- **YouTube Channels:** LiveOverflow, John Hammond, IppSec, The Cyber Mentor.
    

---

## 👣 Final Advice

- Start with easier platforms (TryHackMe, picoCTF).
    
- Practice **report writing** — SOCs must communicate findings clearly.
    
- Join a **CTF team** or local cybersecurity group.
    
- Document what you learn (blogs, GitHub notes, or Obsidian).
    
- Participate in blue-team CTFs (like Splunk Boss of the SOC, CyberDefenders CTFs).
