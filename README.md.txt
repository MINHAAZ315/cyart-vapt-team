# Week 2 - Vulnerability Assessment and Penetration Testing (VAPT)

## Project Overview
This project demonstrates a complete Vulnerability Assessment and Penetration Testing (VAPT) process performed on a Metasploitable2 target machine in a controlled lab environment. The assessment involved reconnaissance, service enumeration, vulnerability scanning, exploitation, post-exploitation, and final reporting.

---

## Objective
The objective of this assessment was to identify vulnerabilities in the target system, validate them through exploitation, and provide remediation recommendations to improve system security.

---

## Target Information
- Target Machine: Metasploitable2
- Target IP Address: 192.168.77.128
- Testing Environment: Kali Linux Virtual Machine

---

## Tools Used
- Nmap
- Nikto
- OpenVAS
- Metasploit Framework
- Kali Linux

---

## VAPT Phases Performed

### 1. Reconnaissance
- Host discovery using Nmap ping scan

### 2. Port Scanning
- Identified open ports and exposed services

### 3. Service Enumeration
- Detected service versions

### 4. Vulnerability Assessment
- Manual vulnerability scanning
- Automated vulnerability scanning

### 5. Exploitation
- Exploited VSFTPD 2.3.4 backdoor vulnerability

### 6. Post Exploitation
- Verified root access
- Enumerated system files

### 7. Reporting
- Documented findings
- Recommended remediations

---

## Key Findings
- VSFTPD 2.3.4 Backdoor Vulnerability
- Outdated Apache Server
- Outdated PHP Version
- HTTP TRACE Enabled
- Directory Listing Enabled
- Exposed phpMyAdmin
- TLS Logjam Vulnerability
- SMB Misconfiguration
- OpenVAS identified 124 vulnerabilities

---

## Exploitation Result
Successfully gained root shell access using Metasploit by exploiting the VSFTPD backdoor vulnerability.

---

## Remediation Recommendations
- Update outdated services
- Disable unnecessary ports
- Restrict sensitive administrative interfaces
- Disable insecure HTTP methods
- Strengthen SMB configurations
- Apply regular vulnerability patching

---

## Repository Structure
```bash
Week-2/
├── Documentation/
├── Notes/
├── Screenshots/
├── Workflow/
└── README.md