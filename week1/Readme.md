# Week 1 – Security Assessment and Vulnerability Analysis

## Objective
The objective of this task was to understand the fundamentals of Vulnerability Assessment and Penetration Testing (VAPT), perform vulnerability scanning on a controlled lab environment, analyze risks, and document findings professionally.

---

# Theoretical Knowledge

## 1. Understanding Security Assessment
Security Assessment is the process of identifying weaknesses and security gaps in systems, applications, and networks.

### Types of Security Testing
- Vulnerability Assessment
- Penetration Testing
- Compliance Testing

### Tools Studied
- OpenVAS
- Nmap
- Nikto
- Kali Linux

---

## 2. VAPT Methodology

### Phases
1. Planning
2. Discovery
3. Enumeration
4. Vulnerability Analysis
5. Reporting
6. Remediation

### Frameworks Referenced
- OWASP Testing Guide
- NIST Security Framework

---

## 3. Security Standards & Compliance

### Studied Standards
- ISO 27001
- GDPR
- HIPAA

### OWASP Top 10
Reviewed common web vulnerabilities including:
- SQL Injection
- Cross-Site Scripting (XSS)
- Broken Authentication
- Security Misconfiguration

---

## 4. Risk Assessment Basics

### Risk Evaluation Methods
- CVSS Scoring
- Risk Matrix
- Severity Classification

### Severity Levels
- Critical
- High
- Medium
- Low

---

## 5. Common Vulnerabilities

### Network Vulnerabilities
- Open Ports
- Weak Services
- Misconfigurations

### Web Vulnerabilities
- SQL Injection
- XSS
- Directory Traversal

### Practice Labs
- Metasploitable
- OWASP Juice Shop

---

## 6. Documentation Fundamentals

### Reporting Components
- Executive Summary
- Methodology
- Findings
- Risk Assessment
- Remediation

### Documentation Tools
- CherryTree
- Markdown
- PDF Reports

---

# Practical Application

## Environment Setup

### Installed
- Kali Linux
- VMware Workstation
- Metasploitable VM

### Network Configuration
Configured both attacker and target systems in the same virtual network.

---

# Vulnerability Scanning

## Nmap Scan

### Command Used
```bash
nmap -sV 192.168.x.x
