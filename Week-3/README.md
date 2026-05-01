 VAPT Project – Week 3 (Full VAPT Cycle)

# Overview
This project demonstrates a complete Vulnerability Assessment and Penetration Testing (VAPT) cycle performed on a controlled lab environment using DVWA and Metasploitable2.

The objective was to identify vulnerabilities, exploit them, perform post-exploitation activities, and provide remediation strategies.

---

# Tools Used
- Kali Linux
- Nmap
- OpenVAS
- Metasploit Framework
- Burp Suite
- sqlmap
- OWASP ZAP
- Wireshark

---

#  Methodology (PTES Based)
1. Reconnaissance
2. Scanning & Enumeration
3. Vulnerability Assessment
4. Exploitation
5. Post-Exploitation
6. Reporting & Remediation

---

# Key Activities

# Reconnaissance
- Discovered target IP using Nmap

# Scanning
- Identified open ports and services
- Detected vulnerable services

# Vulnerability Assessment
- OpenVAS scan revealed critical vulnerabilities
- SQL Injection tested using sqlmap
- XSS identified manually

# Exploitation
- Exploited vsftpd 2.3.4 backdoor using Metasploit
- Gained root-level access

# Post-Exploitation
- Enumerated system information
- Accessed sensitive files (`/etc/passwd`, `/etc/shadow`)
- Verified privilege escalation

# Evidence Collection
- Generated SHA256 hash for integrity

# Network Analysis
- Captured traffic using Wireshark

---

# Key Findings
- SQL Injection (Critical)
- Cross-Site Scripting (Medium)
- vsftpd Backdoor (Critical)
- Telnet Insecure Service
- SMB Misconfiguration

---

# Remediation Summary
- Use prepared statements for SQL queries
- Implement input validation & output encoding
- Disable unused services (FTP, Telnet)
- Apply security patches
- Use firewall and monitoring systems

---

# Repository Structure
