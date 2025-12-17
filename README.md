# Ethical Hacking Labs: Website Cloning with SET and SMB Vulnerability Scanning

This repository documents two controlled ethical hacking labs performed in Kali Linux:

1. Website Cloning and Credential Harvesting using the Social Engineer Toolkit (SET)
2. SMB Vulnerability Scanning and Enumeration using enum4linux

All activities were conducted in a virtual lab environment for educational purposes only.

---

## Lab 1: Website Cloning with SET

### Objective
To demonstrate how social engineering attacks can be used to harvest user credentials by cloning a legitimate website login page.

### Tools Used
- Kali Linux
- Social Engineer Toolkit (SET)
- Firefox Browser
- DVWA Virtual Machine

### Summary
SET was used to clone the DVWA login page and host it locally on the attacker machine. When a user submitted credentials on the cloned page, the information was captured by SET and displayed in the terminal while the user was silently redirected to the legitimate site.

### Key Risk Demonstrated
- User susceptibility to phishing attacks
- Credential harvesting through cloned websites
- Lack of user awareness and URL inspection

Screenshots and commands are available in the `Website Cloning  with  SET and SMB Vulnerability Scanning./` file.

---

## Lab 2: SMB Vulnerability Scanning with enum4linux

### Objective
To identify SMB misconfigurations and information disclosure vulnerabilities through enumeration.

### Tools Used
- Kali Linux
- enum4linux
- nmap
- smbclient

### Summary
The enum4linux tool was used to enumerate users, shares, password policies, and system information from SMB-enabled hosts. In some cases, anonymous (null session) access was permitted, exposing sensitive information.

### Key Risks Demonstrated
- SMB null session enumeration
- User and share disclosure
- Weak password policies
- Poor SMB hardening

Screenshots and commands are available in the `Website Cloning  with  SET and SMB Vulnerability Scanning./` file.

---

## Disclaimer
These labs were performed strictly for academic purposes in an isolated environment. Unauthorized use of these techniques against live systems is illegal and unethical.

---

## Author
Cornelius Kibet  
MSc ICT Management
