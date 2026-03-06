# Week 2 - Vulnerability Scanning Lab

## Objective
Perform vulnerability scanning using Nmap, OpenVAS, and Nikto.

## Workflow

Step 1: Setup Lab Environment
- Install Kali Linux
- Configure target machine
- Ensure network connectivity

Step 2: Run Nmap Scan
Command:
nmap -sV -A 192.168.1.10

Step 3: Run Nikto Scan
Command:
nikto -h http://192.168.1.10

Step 4: Run OpenVAS Scan
- Start OpenVAS
- Create scan target
- Run vulnerability scan

Step 5: Analyze Results
- Identify critical vulnerabilities
- Note CVSS score
- Prioritize remediation

## Scan Result Table

Scan ID | Vulnerability | CVSS Score | Priority | Host
------ | ------------- | ---------- | -------- | ----
001 | SQL Injection | 9.1 | Critical | 192.168.1.10
002 | XSS | 7.4 | High | 192.168.1.10
