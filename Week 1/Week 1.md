Task 06: Network Security Monitoring and Analysis
Title

Network Security Monitoring and Analysis

Overview

This project focuses on understanding security assessment concepts, VAPT methodology, risk analysis, and documentation practices. The assessment was performed in a controlled lab environment using a vulnerable system (Metasploitable) and security tools such as Kali Linux and OpenVAS.

The objective of this task is to simulate a real-world security assessment process, identify vulnerabilities, analyze risks, and document findings in a structured manner.

1. Understanding Security Assessment

A security assessment is a systematic process used to identify vulnerabilities, misconfigurations, and weaknesses in systems, networks, and applications.

Objectives
Identify security vulnerabilities
Evaluate existing security controls
Reduce risk exposure
Improve overall security posture
Types of Security Testing
Vulnerability Assessment (VA)
Penetration Testing (PT)
Compliance Testing
2. VAPT Methodology

The project follows a structured VAPT methodology consisting of the following phases:

1. Planning Phase
Define scope and objectives
Identify target system (Metasploitable)
Setup lab environment
2. Discovery Phase
Perform network scanning using Nmap
Conduct vulnerability scanning using OpenVAS
Identify open ports, services, and CVEs
3. Attack (Exploitation) Phase
Exploit identified vulnerabilities using Metasploit
Validate vulnerabilities with real-world attack simulation
4. Post-Exploitation Phase
Assess level of access gained
Verify system compromise
Analyze impact
5. Reporting Phase
Document findings
Include severity, CVSS scores, and remediation
3. Tools Used
Kali Linux
Nmap
OpenVAS (GVM)
Metasploit Framework
4. Security Standards & Compliance

The assessment aligns with industry standards:

ISO 27001
Risk management
Access control
Security policies
GDPR
Data protection
Privacy and confidentiality
OWASP Top 10
Broken Access Control
Injection vulnerabilities
Outdated components
CIS Benchmarks
Secure configurations
Disable unnecessary services
Enforce strong passwords
5. Risk Assessment

Risk assessment was performed using:

CVSS Scoring
Critical: 9.0 – 10.0
High: 7.0 – 8.9
Medium: 4.0 – 6.9
Low: 0.1 – 3.9
Risk Matrix
Likelihood vs Impact
Helps prioritize vulnerabilities
Example Risks
vsFTPd Backdoor → Critical
Default Credentials → Critical
Anonymous FTP → Medium
6. Common Vulnerabilities Identified
Network-Level Vulnerabilities
Open ports and services
Remote execution services (rsh, rexec)
Remote Code Execution (RCE)
vsFTPd backdoor
DistCC vulnerability
Weak Credentials
Default MySQL credentials
Anonymous FTP login
Outdated Software
End-of-life operating system
Vulnerable PHP version
Misconfigurations
Unencrypted services
HTTP methods enabled
7. Documentation Fundamentals

Proper documentation ensures:

Clear communication of findings
Risk prioritization
Compliance verification
Tracking remediation
Documentation Tools
Google Docs / MS Word
Dradis CE
CherryTree
Spreadsheets
8. Evidence Collection

Evidence collected includes:

Nmap scan results
OpenVAS scan reports
Metasploit exploitation output
System access proof

Screenshots should be:

Clear
Relevant
Properly labeled
9. Key Learnings
Importance of structured VAPT methodology
Real-world impact of vulnerabilities
Risk-based prioritization
Importance of patch management
Role of proper documentation
10. Conclusion

The assessment revealed multiple critical vulnerabilities in the target system, including backdoors, weak credentials, and outdated software. These issues demonstrate how insecure configurations can lead to full system compromise.

Applying proper remediation strategies such as patching, disabling unnecessary services, and enforcing strong authentication can significantly improve system security.

11. References
NIST Cybersecurity Framework
OWASP Top 10
ISO 27001
CIS Benchmarks
