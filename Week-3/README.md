# Week 3 – VAPT Capstone Project

## Overview
This project demonstrates a complete Vulnerability Assessment and Penetration Testing (VAPT) cycle performed in a controlled lab environment using Metasploitable2 and DVWA. The objective was to identify vulnerabilities, exploit them, validate system compromise, and provide remediation strategies based on real-world attack scenarios.

---

## Tools Used
- Kali Linux
- Nmap
- OpenVAS
- Metasploit Framework
- sqlmap
- Burp Suite
- OWASP ZAP
- Wireshark

---

## Workflow Summary
1. Lab environment setup (Kali + Metasploitable2 + DVWA)  
2. Connectivity verification using ping  
3. Host discovery using Nmap  
4. Port scanning and service enumeration  
5. Vulnerability assessment (OpenVAS, sqlmap, Burp Suite, ZAP)  
6. Web application testing (SQL Injection, XSS)  
7. Risk analysis using CVSS scoring  
8. Exploitation using Metasploit (vsftpd backdoor)  
9. Post-exploitation (root access validation, file access)  
10. Evidence collection (SHA256 hashing, Wireshark capture)  
11. Documentation and reporting  

---

## Key Findings
- SQL Injection (Critical)  
- Cross-Site Scripting (Medium)  
- vsftpd 2.3.4 Backdoor (Critical)  
- Telnet (Insecure Protocol)  
- Outdated Services (Apache, MySQL, Samba)  

---

## Exploitation Summary
A critical vulnerability in vsftpd 2.3.4 was successfully exploited using Metasploit, resulting in root-level access. Post-exploitation confirmed full system compromise by accessing sensitive files such as `/etc/passwd` and `/etc/shadow`.

---

## Remediation Highlights
- Use parameterized queries for SQL  
- Implement input validation and output encoding  
- Disable insecure services (FTP, Telnet)  
- Apply security patches and updates  
- Enable firewall and monitoring systems  

--
