# Week 4 – Advanced Vulnerability Assessment and Penetration Testing

## Repository Overview

This repository contains the practical execution, documentation, screenshots, workflows, and final reporting for Week 4 of the CYART VAPT training program. The work focuses on advanced penetration testing methodologies, exploitation techniques, API security testing, privilege escalation, network protocol attacks, mobile application testing, and a complete end-to-end VAPT engagement conducted within a controlled lab environment.

The assessments were performed using Kali Linux against intentionally vulnerable systems including Metasploitable2, DVWA, Android APK targets, and simulated network services.

---

# Objectives

The primary objectives of this project were:

- Perform advanced vulnerability assessment and penetration testing activities
- Identify insecure configurations and vulnerable services
- Exploit web application and network vulnerabilities
- Simulate privilege escalation and persistence mechanisms
- Analyze mobile application security weaknesses
- Capture and analyze network traffic during attacks
- Document findings with remediation recommendations
- Produce professional penetration testing reports

---

# Tools and Technologies

| Tool | Purpose |
|------|---------|
| Kali Linux | Attack platform |
| Nmap | Network scanning and enumeration |
| OpenVAS | Vulnerability assessment |
| Metasploit Framework | Exploitation framework |
| Burp Suite | Web application testing |
| sqlmap | Automated SQL injection testing |
| Wireshark | Packet capture and traffic analysis |
| Responder | LLMNR/NBT-NS poisoning |
| Ettercap | Man-in-the-Middle attacks |
| LinPEAS | Linux privilege escalation enumeration |
| MobSF | Mobile application static analysis |
| Frida | Runtime instrumentation and hooking |
| Drozer | Android IPC testing |

---

# Practical Modules Completed

## 1. Advanced Exploitation Lab

Activities performed:
- Exploit chaining simulation
- Metasploit exploitation workflow
- Custom exploit documentation
- ASLR/ROP bypass study

Deliverables:
- Exploit logs
- Findings summary
- Remediation recommendations

---

## 2. API Security Testing Lab

Activities performed:
- SQL Injection testing
- Reflected XSS testing
- Burp Suite interception
- sqlmap database enumeration
- API manipulation workflow

Key findings:
- SQL Injection vulnerability
- Reflected Cross-Site Scripting
- Weak input validation

---

## 3. Privilege Escalation and Persistence Lab

Activities performed:
- LinPEAS enumeration
- SUID vulnerability identification
- Root privilege verification
- Cron-based persistence simulation

Key outcomes:
- Root shell access obtained
- Persistence workflow demonstrated

---

## 4. Network Protocol Attacks Lab

Activities performed:
- LLMNR poisoning using Responder
- ARP spoofing simulation using Ettercap
- Packet analysis using Wireshark

Key observations:
- Network traffic interception
- Poisoned responses detected
- Protocol-level attack visibility

---

## 5. Mobile Application Testing Lab

Activities performed:
- APK static analysis using MobSF
- Runtime instrumentation using Frida
- Android IPC testing workflow using Drozer

Key findings:
- Insecure application configuration
- Exported components exposure
- Runtime hooking demonstration

---

## 6. Capstone Project – Full VAPT Engagement

The capstone assessment simulated a complete penetration testing lifecycle including:

- Reconnaissance
- Service enumeration
- Vulnerability scanning
- Exploitation
- Post-exploitation
- Evidence collection
- Reporting and remediation

Vulnerabilities identified:
- SQL Injection
- Cross-Site Scripting
- vsftpd 2.3.4 Backdoor
- SMB weaknesses
- Insecure services

---

# Repository Structure

```text
Week4/
├── README.md
├── Report/
├── Screenshots/
├── Workflow/
├── Notes/
└── Evidence/
