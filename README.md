## Web Vulnerability Assessment using DVWA and OWASP Top 10

### Overview
The objective of this project is to perform a web vulnerability assessment on DVWA and analyze the discovered issues based on the OWASP Top 10 standards. The project was performed in a safe and controlled lab environment to understand how weaknesses in web applications are discovered, analyzed and exploited using standard security tools.

### Lab Setup :
- Attacker Machine: Kali Linux
- Target Machine: Ubuntu running DVWA
- Environment: Internal network
DVWA was hosted on an Ubuntu server with intentionally insecure configurations. Kali Linux was used to perform testing using standard security tools.

### Tools Used:
- Kali Linux – Attacking machine
- Ubuntu Linux – Target machine hosting DVWA
- Firefox – Browser used for accessing and testing the web application
- Nmap – Network and service discovery
- Gobuster – Directory and file enumeration
- Nikto – Web server vulnerability scanning
- OWASP ZAP – Automated web vulnerability scanner
- wfuzz – Brute force attack testing
- Wireshark – Network traffic analysis

### Vulnerability Assessment Overview :
- Information Gathering: Basic details about the target such as active   services, URLs, and headers were identified.
- Scanning & Enumeration: Open ports, directories, server misconfigurations, and vulnerable endpoints were discovered.
- Exploitation: Vulnerabilities like SQL Injection, XSS, and Brute Force were safely exploited to demonstrate impact.
- OWASP ZAP: Automated scans confirmed issues such as injection flaws, weak authentication, and missing security headers.

### Project Documentation
- lab setup file
- information gathering file
- network scanning and analysis file
- vulnerabilities file 
- OWASP ZAP file

### OWASP Top 10 Mapping
- A02:2025 - Security Misconfiguration
- A04:2025 - Cryptographic Failures
- A05:2025 - Injection
- A07:2025 - Authentication Failures

### Learning outcomes:
- Understanding of common web application vulnerabilities
- Basic knowledge of OWASP Top 10 security risks
- Hands-on experience with tools like Nmap, Gobuster, Nikto, OWASP ZAP,  wfuzz, and Wireshark
- Improved awareness of secure web application practices

### Conclusion:
This project helped in understanding web application security by practically testing DVWA against OWASP Top 10 vulnerabilities, also enhanced understanding of common vulnerabilities, security testing tools, and ethical hacking techniques.
