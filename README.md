# 🛡️ Codex Cybersecurity Roadmap

## 🔰 Basics
- Software & Hardware Fundamentals
- I/O Memory, Physical Ports
- Basic Troubleshooting
- OS Installation (Windows/Linux)
- Basic Networking Concepts
- Basic CLI Commands (Linux/Windows)

---

## 🌐 Networking Fundamentals
- OSI Model (Layer 1 to 7)
- IP Addressing (Public/Private, Subnetting, Classes)
- DHCP, DNS, NAT
- Layer 4 Protocols: TCP, UDP
- Common Ports & Services ([HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP), [FTP](https://www.w3schools.com/whatis/whatis_ftp.asp), [SMTP](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol))
- Routers, Switches, NAT, MAC Addressing
- Security Protocols: [SSL](https://en.wikipedia.org/wiki/Transport_Layer_Security), [TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security), [HTTPS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
- [VPN](https://www.cloudflare.com/en-gb/learning/network-layer/what-is-a-vpn/), [Proxies](https://www.imperva.com/learn/application-security/proxy/), Web Proxies

---

## 🖥️ OS Fundamentals
- OS Architecture
- File Systems & Permissions
- Users, Groups, Privilege Management
- Processes & System Calls
- Kernel, Memory Management
- OS Hardening Techniques
- Networking in OS

---

## 🖥️ Virtualization
- Setup & Configure VMs ([VMware](https://www.vmware.com/), [VirtualBox](https://www.virtualbox.org/))
- NAT, Bridged, Host-Only Network Configs
- IP Assignment in VMs
- Troubleshooting VMs
- Setup Active Directory Labs

---

## 💻 Programming & Scripting
- [Python](https://www.python.org/)
- [Bash Scripting](https://ryanstutorials.net/bash-scripting-tutorial/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## 📜 Cybersecurity Standards
- [NIST](https://www.nist.gov/), [OWASP](https://owasp.org/), [SANS](https://www.sans.org/), [ISO/IEC 27001](https://www.iso.org/isoiec-27001-information-security.html)
- [PCI-DSS](https://www.pcisecuritystandards.org/), [CIS Controls](https://www.cisecurity.org/controls/)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)

---

## 🌍 Cyber Laws & Compliance
- [GDPR](https://gdpr-info.eu/), [CCPA](https://oag.ca.gov/privacy/ccpa), [HIPAA](https://www.hhs.gov/hipaa/index.html), [FISMA](https://csrc.nist.gov/topics/risk-management/fisma)
- Cybercrime & Intellectual Property Laws

---

## 🛡️ Red Team Topics
- Reconnaissance ([OSINT](https://osintframework.com/))
- Scanning & Enumeration
- Exploitation
- Post Exploitation
- Privilege Escalation
- Persistence & Lateral Movement

### 🔐 Active Directory Concepts
- Domains, OUs, GPOs, DCs
- AD Enumeration Tools

### 🔐 Authentication Protocols
- NTLM, Kerberos, LDAP, SSO, EAP, SAML

### 🔍 Vulnerability Management
- CVE, [CVSS](https://www.first.org/cvss/), CWE

### 🧠 Human Factors
- Phishing, Vishing, Smishing
- Spamming, Shoulder Surfing
- Dumpster Diving, Tailgating
- Impersonation

---

## 🔵 Blue Team Topics
- Threat Intelligence (Malware Analysis, Insider Threats)
- Threat Detection & Prevention
- [Zero Trust Architecture](https://www.csoonline.com/article/3563183/what-is-zero-trust-a-model-for-more-effective-security.html)
- [Cyber Kill Chain](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html)

### 🧠 OSINT Techniques
- SOCMINT, GEOINT, HUMINT
- Web Intelligence, Technical Intelligence

### 🛡️ Security Solutions
- Firewall, IDS, IPS
- EDR, Anti-virus
- DMZ Architecture
- Differences & Use Cases

### 📈 SIEM Tools
- [Splunk](https://www.splunk.com/), [IBM QRadar](https://www.ibm.com/qradar), [LogRhythm](https://logrhythm.com/), [AlienVault](https://www.alienvault.com/), [SolarWinds](https://www.solarwinds.com/)

### 🔬 Digital Forensics
- Isolation, Imaging, Steganography
- Reverse Engineering
- Log, Disk & Memory Analysis
- Data Recovery

### 🧰 Forensic Tools
- [FTK Imager](https://accessdata.com/product-download/ftk-imager-version-4-5), [Autopsy](https://www.sleuthkit.org/autopsy/), [Wireshark](https://www.wireshark.org/)
- [Cellebrite](https://www.cellebrite.com/), [EnCase](https://www.opentext.com/products/encase), [VirusTotal](https://www.virustotal.com/)

---

## 🔐 Cryptography
- Hashing: [Bcrypt](https://en.wikipedia.org/wiki/Bcrypt), [SHA](https://en.wikipedia.org/wiki/Secure_Hash_Algorithms)
- Symmetric & Asymmetric Encryption
- [PKI](https://www.cloudflare.com/learning/ssl/what-is-public-key-infrastructure/)
- Key Management
- Digital Signatures
- Hashing vs Encryption

---

## ☁️ Cloud & Modern Tech
- Cloud: [AWS](https://aws.amazon.com/), [Azure](https://azure.microsoft.com/)
- IaaS, PaaS, SaaS Models
- Serverless Computing
- Cloud Security
- Containers: [Docker](https://www.docker.com/), [Kubernetes](https://kubernetes.io/)
- Microservices Architecture
- Quantum Computing Basics

---

## 🧪 Practical Labs
- Local Lab Setup (VMs, AD, Kali)
- Online Platforms:
  - [Hack The Box](https://www.hackthebox.com/)
  - [TryHackMe](https://tryhackme.com/)
  - [VulnHub](https://www.vulnhub.com/)
  - [PicoCTF](https://picoctf.org/)

---

## 🌐 Web Security & Bug Bounties
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- Web Vulnerabilities: Recon, Fuzzing, Brute Forcing
- Tools:
  - [Burp Suite](https://portswigger.net/burp)
  - [Nmap](https://nmap.org/)
  - [Metasploit](https://www.metasploit.com/)
  - [Snort](https://www.snort.org/)
  - [Nikto](https://cirt.net/Nikto2)
  - [John the Ripper](https://www.openwall.com/john/)
  - [Aircrack-ng](https://www.aircrack-ng.org/)
  - [OpenVAS](https://www.openvas.org/)
  - [Netcat](https://linux.die.net/man/1/nc)

---

## 🌐 Common Security Websites
- [VirusTotal.com](https://www.virustotal.com/)
- [Exploit-DB.com](https://www.exploit-db.com/)
- [URLScan.io](https://urlscan.io/)
- [Shodan.io](https://www.shodan.io/)
- [CyberChef](https://gchq.github.io/CyberChef/)
- [RevShells.com](https://www.revshells.com/)

---

## 🏁 Career Essentials
- Resume Tips: Projects, CTFs, Internships, Hall of Fame
- [GitHub](https://github.com/) Projects
- Capture The Flag: [ctftime.org](https://ctftime.org/)

---

## 📜 Certifications
### Red Team:
- [OSCP](https://www.offensive-security.com/pwk-oscp/)
- [CPENT](https://www.eccouncil.org/train-certify/cpent/)
- [eJPT](https://ine.com/pages/ejpt-certification)
- [CEH](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)
- [PenTest+](https://www.comptia.org/certifications/pentest)
- [GPEN](https://www.giac.org/certification/penetration-tester-gpen/)

### Blue Team:
- [CompTIA Security+](https://www.comptia.org/certifications/security)
- [GSEC](https://www.giac.org/certification/security-essentials-gsec/)
- [CEH](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)

### Risk & Compliance:
- [CISSP](https://www.isc2.org/Certifications/CISSP)
- [CISA](https://www.isaca.org/credentialing/cisa)
- [CISM](https://www.isaca.org/credentialing/cism)

