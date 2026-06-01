# 🛡️ Cybersecurity Hub

> A personal knowledge base combining the best free cybersecurity learning resources, TryHackMe notes & writeups, HTB walkthroughs, exploit payloads, and hands-on project guides — all in one place, structured for actual use.

---

## 📁 Repository Structure

```
cybersec-hub/
├── 01-learning-roadmap/        # 500+ free THM rooms, organised by topic
├── 02-foundations/             # Full cybersecurity course notes (beginner → advanced)
├── 03-thm-notes/               # Personal notes from THM learning paths
│   ├── pre-security/
│   ├── complete-beginner/
│   ├── web-fundamentals/
│   ├── cyber-defense/
│   └── red-teaming/
├── 04-writeups-and-walkthroughs/
│   ├── thm-writeups/           # 120+ TryHackMe room writeups
│   ├── htb-walkthroughs/       # HackTheBox machine walkthroughs
│   ├── pentest-reports/        # Professional-style pentest reports (HTB)
│   └── portfolio/              # Incident response, threat hunting, vuln management
├── 05-payloads-and-exploits/   # 60+ payload categories (SQLi, XSS, SSRF, etc.)
├── 06-setup-and-tools/         # Kali Linux + TryHackMe VPN setup guide & scripts
└── 07-project-based-learning/  # Build real projects to reinforce skills
```

---

## 🗺️ Sections at a Glance

### `01-learning-roadmap` — Where to Start
A curated list of **500+ free TryHackMe rooms** organised by topic — networking, web hacking, AD, reverse engineering, and more. Use this as your north star when you're not sure what to tackle next.

### `02-foundations` — Core Concepts
A full structured cybersecurity course covering:
- Intro to Cyber Security (CIA triad, threat types, IDS)
- Networking fundamentals (IP, subnetting, TCP/UDP, ports)
- Linux fundamentals
- OWASP Top 10 (2021)
- Bug bounty basics

### `03-thm-notes` — Learning Path Notes
Personal notes taken while working through TryHackMe's official learning paths. Organised by path:
- **Pre Security** — Windows & Linux basics
- **Complete Beginner** — Nmap, Burp Suite, OWASP, networking, crypto
- **Web Fundamentals** — OWASP Zap, vulnerabilities, practice machines
- **Cyber Defense** — SOC, malware analysis, incident response, threat intel
- **Red Teaming** — AD attacks, evasion, post-exploitation, initial access

### `04-writeups-and-walkthroughs` — Hands-On Write-Ups
- **120+ TryHackMe writeups** covering everything from beginner rooms to Advent of Cyber
- **HackTheBox walkthroughs** — Active Directory, Windows, Linux machines
- **Professional pentest reports** (HTB Administrator, Escape) in PDF format
- **Portfolio pieces** — Incident response, threat hunting, vulnerability management, risk assessment

### `05-payloads-and-exploits` — Attack Reference
Comprehensive payload and technique reference covering **60+ vulnerability categories**:
SQL Injection, XSS, SSRF, SSTI, Command Injection, JWT attacks, OAuth flaws, File Inclusion, XXE, Deserialization, and much more. Each category has its own README with explanation, payloads, and tooling notes.

### `06-setup-and-tools` — Environment Setup
Step-by-step guide to connecting Kali Linux or Parrot Security to TryHackMe via VPN. Includes:
- VPN setup walkthrough
- iptables security hardening script (`safevpn-thm.sh`)
- Screenshots and a full PDF write-up

### `07-project-based-learning` — Build to Learn
A massive curated list of project-based tutorials organised by programming language. Learn by building real things — compilers, databases, OS kernels, web apps, games, and more.

---

## 🏁 Suggested Learning Path

```
Beginner
  └─▶ 02-foundations          (learn the theory)
  └─▶ 01-learning-roadmap     (pick your first rooms)
  └─▶ 06-setup-and-tools      (get your Kali environment ready)
  └─▶ 03-thm-notes/pre-security

Intermediate
  └─▶ 03-thm-notes/complete-beginner
  └─▶ 03-thm-notes/web-fundamentals
  └─▶ 04-writeups-and-walkthroughs/thm-writeups  (read before attempting)

Advanced
  └─▶ 03-thm-notes/red-teaming
  └─▶ 03-thm-notes/cyber-defense
  └─▶ 04-writeups-and-walkthroughs/htb-walkthroughs
  └─▶ 05-payloads-and-exploits  (use as reference during CTFs)
  └─▶ 04-writeups-and-walkthroughs/portfolio  (model your own reports)
```

---

## 📜 Credits & Original Sources

This repo combines, reorganises, and expands on the following open-source projects. Full credit to each original author:

| Section | Original Repo | Author / Maintainer |
|--------|--------------|---------------------|
| `01-learning-roadmap` | [TryHackMe-Roadmap](https://github.com/Hunterdii/TryHackMe-Roadmap) | [@Hunterdii](https://github.com/Hunterdii) |
| `02-foundations` | [cyber-security-full-course](https://github.com/MrM8BRH/cyber-security-full-course) | [@MrM8BRH](https://github.com/MrM8BRH) |
| `03-thm-notes` | [tryHackMe_notes](https://github.com/Berkanktk/tryHackMe_notes) | [@Berkanktk](https://github.com/Berkanktk) |
| `04-writeups-and-walkthroughs/thm-writeups` | [TryHackMe_Writeups](https://github.com/Kevinovitz/TryHackMe_Writeups) | [@Kevinovitz](https://github.com/Kevinovitz) |
| `04-writeups-and-walkthroughs/htb-walkthroughs` | [CTF-Walkthroughs](https://github.com/0xBEN/CTF-Walkthroughs) | [@0xBEN](https://github.com/0xBEN) |
| `05-payloads-and-exploits` | [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) | [@swisskyrepo](https://github.com/swisskyrepo) |
| `06-setup-and-tools` | [tryhackme-connectkali](https://github.com/fartaviao/tryhackme-connectkali) | [@fartaviao](https://github.com/fartaviao) |
| `07-project-based-learning` | [project-based-learning](https://github.com/practical-tutorials/project-based-learning) | [@practical-tutorials](https://github.com/practical-tutorials) |

All original licences are retained in their respective folders. This combined repo is for personal educational use.

---

## ⚠️ Legal Disclaimer

All content in this repository is for **educational and ethical hacking purposes only**. Only use these techniques on systems you own or have explicit written permission to test. Unauthorised access to computer systems is illegal.

---

## 📋 Full Content Index

### 📚 Foundation Documents (`02-foundations`)

| Document | Topic |
|---|---|
| `03-Introduction to Cyber Security/01-Whats is Cyber Security.md` | What is Cyber Security |
| `03-Introduction to Cyber Security/02-Carrers in Cyber Security.md` | Careers in Cyber Security |
| `03-Introduction to Cyber Security/03-Types of Hacker.md` | Types of Hackers |
| `03-Introduction to Cyber Security/04-Difference Between Cyber Threat and ATTACK.md` | Threats vs. Attacks |
| `03-Introduction to Cyber Security/05-Types of Cyber Attacks.md` | Types of Cyber Attacks |
| `03-Introduction to Cyber Security/06-Types of Cyber Threats.md` | Types of Cyber Threats |
| `03-Introduction to Cyber Security/07-What is IDS.md` | Intrusion Detection Systems |
| `03-Introduction to Cyber Security/08-CIA triad.md` | The CIA Triad |
| `04-Netwoking/01-What Is Networking.md` | Networking Fundamentals |
| `04-Netwoking/02-Types Of Networking.md` | Network Types |
| `04-Netwoking/03-What is IP Address.md` | IP Addressing |
| `04-Netwoking/04-classification of IP addresses.md` | IP Classification |
| `04-Netwoking/05-Ip Version.md` | IPv4 vs IPv6 |
| `04-Netwoking/06-Subnetting.md` | Subnetting |
| `04-Netwoking/07-Ports & Protocol.md` | Ports & Protocols |
| `04-Netwoking/08-TCP & UDP.md` | TCP & UDP |

---

### 📓 THM Notes (`03-thm-notes`)

#### Pre Security
Personal notes from the THM Pre Security learning path covering Windows and Linux basics.

#### Complete Beginner

| Topic | Notes |
|---|---|
| Burp Suite | `.txt` notes |
| Cryptography | Encryption — Crypto 101, Hashing Crypto 101, John the Ripper |
| Introductory Networking | `.txt` notes |
| Network Services | Network Services `.txt`, Network Services 2 `.txt` |
| Nmap | `.txt` notes |
| OWASP Top 10 | `.txt` notes |
| Web Fundamentals | `.txt` notes |
| Basic Computer Exploitation | Basic Pentesting, Kenobi, Steel Mountain, Vulnversity |
| Shells & Privilege Escalation | Common Linux Privesc, Linux PrivEsc |
| Windows Exploitation Basics | Active Directory Basics, Intro to Windows |

#### Web Fundamentals

| Topic | Notes |
|---|---|
| Burp Suite and OWASP Zap | Tool notes |
| Vulnerabilities | Web vulnerability notes |
| Web Fundamentals | Core web hacking concepts |
| Practice Makes Perfect | Challenge machines |

#### Cyber Defense

| Topic | Notes |
|---|---|
| Cyber Defense Intro | Active Directory Basics, Intro to ISAC, Wireshark 101 |
| Incident Response & Forensics | Autopsy, Disk Analysis & Autopsy, Investigating Windows, Redline, Volatility, Windows Forensics 1 & 2 |
| Malware Analysis | Basic Malware RE, History of Malware |
| Security Operations & Monitoring | SOC tooling and processes |
| Threat & Vulnerability Management | Yara |

#### Red Teaming

| Topic | Notes |
|---|---|
| Red Team Fundamentals | Core red team concepts |
| Initial Access | Phishing and initial foothold techniques |
| Host Evasions | AV evasion and defense bypass |
| Network Security Evasion | Traffic obfuscation techniques |
| Compromising Active Directory | AD attack chains |
| Post Compromise | Post-exploitation techniques |

---

### 🚩 THM Writeups (`04-writeups-and-walkthroughs/thm-writeups`)

#### Advent of Cyber

| Series | Link |
|---|---|
| 25 Days of Christmas (original) | [tryhackme.com/room/25daysofchristmas](https://tryhackme.com/room/25daysofchristmas) |
| Advent of Cyber 2 | [tryhackme.com/room/adventofcyber2](https://tryhackme.com/room/adventofcyber2) |
| Advent of Cyber 2023 | [tryhackme.com/room/adventofcyber2023](https://tryhackme.com/room/adventofcyber2023) |
| Advent of Cyber 2024 | [tryhackme.com/room/adventofcyber2024](https://tryhackme.com/room/adventofcyber2024) |
| Advent of Cyber 2025 | [tryhackme.com/room/adventofcyber25](https://tryhackme.com/room/adventofcyber25) |
| AoC 2023 Side Quest | Side quest challenges |
| AoC 2024 Side Quest | Side quest challenges |
| AoC 2025 Side Quest | Side quest challenges |
| Advent of dbOps (AoC special) | [tryhackme.com/room/adv3nt0fdbopsjcap](https://tryhackme.com/room/adv3nt0fdbopsjcap) |

#### AoC 2025 Bonus Rooms

| Room | Topic | Link |
|---|---|---|
| AI for Cyber | AI in cybersecurity | [tryhackme.com](https://tryhackme.com) |
| Attacks on Encrypted Files | Crypto/forensics | [tryhackme.com](https://tryhackme.com) |
| Azure Sentinel | SIEM / cloud security | [tryhackme.com](https://tryhackme.com) |
| Cloud Enum | Cloud enumeration | [tryhackme.com](https://tryhackme.com) |
| Container Security | Docker/container attacks | [tryhackme.com](https://tryhackme.com) |
| Detecting C2 with RITA | C2 traffic analysis | [tryhackme.com](https://tryhackme.com) |
| Encoding & Decoding | Data encoding techniques | [tryhackme.com](https://tryhackme.com) |
| HTAP PowerShell | PowerShell attacks | [tryhackme.com](https://tryhackme.com) |
| ICS Modbus | Industrial control systems | [tryhackme.com](https://tryhackme.com) |
| IDOR | Insecure Direct Object Reference | [tryhackme.com](https://tryhackme.com) |
| Linux CLI | Linux command line | [tryhackme.com](https://tryhackme.com) |
| Malware Sandbox | Malware analysis | [tryhackme.com](https://tryhackme.com) |
| Network Services | Network exploitation | [tryhackme.com](https://tryhackme.com) |
| Obfuscation | Code/payload obfuscation | [tryhackme.com](https://tryhackme.com) |
| Phishing | Phishing techniques | [tryhackme.com](https://tryhackme.com) |
| Prompt Injection | AI/LLM attacks | [tryhackme.com](https://tryhackme.com) |
| Race Conditions | Race condition exploits | [tryhackme.com](https://tryhackme.com) |
| Registry Forensics | Windows registry analysis | [tryhackme.com](https://tryhackme.com) |
| Splunk for Log Analysis | SIEM / log analysis | [tryhackme.com](https://tryhackme.com) |
| Spotting Phishing | Phishing detection | [tryhackme.com](https://tryhackme.com) |
| Web Attack Forensics | Web log forensics | [tryhackme.com](https://tryhackme.com) |
| Web Hacking with curl | Web enumeration | [tryhackme.com](https://tryhackme.com) |
| XSS | Cross-Site Scripting | [tryhackme.com](https://tryhackme.com) |
| Yara | Yara rule writing | [tryhackme.com](https://tryhackme.com) |

#### Standard Rooms

| Room | Topic | Link |
|---|---|---|
| AD Enumeration | Active Directory | [tryhackme.com/room/adenumeration](https://tryhackme.com/room/adenumeration) |
| Agent Sudo | CTF / privilege escalation | [tryhackme.com/room/agentsudoctf](https://tryhackme.com/room/agentsudoctf) |
| Anonymous | FTP / SMB enumeration | [tryhackme.com/room/anonymous](https://tryhackme.com/room/anonymous) |
| Auditing & Monitoring | Security auditing | [tryhackme.com/room/auditingandmonitoringse](https://tryhackme.com/room/auditingandmonitoringse) |
| Authentication Bypass | Auth vulnerabilities | [tryhackme.com/room/authenticationbypass](https://tryhackme.com/room/authenticationbypass) |
| Blaster | Windows exploitation | [tryhackme.com/room/blaster](https://tryhackme.com/room/blaster) |
| Blue | EternalBlue / MS17-010 | [tryhackme.com/room/blue](https://tryhackme.com/room/blue) |
| Buffer Overflow Prep | BOF fundamentals | [tryhackme.com/room/bof1](https://tryhackme.com/room/bof1) |
| Breaching AD | AD initial access | [tryhackme.com/room/breachingad](https://tryhackme.com/room/breachingad) |
| Break RSA | Cryptography | [tryhackme.com/room/breakrsa](https://tryhackme.com/room/breakrsa) |
| Burp Suite: Basics | Web proxy | [tryhackme.com/room/burpsuitebasics](https://tryhackme.com/room/burpsuitebasics) |
| Burp Suite: Intruder | Brute force / fuzzing | [tryhackme.com/room/burpsuiteintruder](https://tryhackme.com/room/burpsuiteintruder) |
| Burp Suite: Other Modules | Extensions / scanner | [tryhackme.com/room/burpsuiteom](https://tryhackme.com/room/burpsuiteom) |
| Burp Suite: Repeater | Manual web testing | [tryhackme.com/room/burpsuiterepeater](https://tryhackme.com/room/burpsuiterepeater) |
| Code Analysis | SAST / source review | [tryhackme.com/room/codeanalysis](https://tryhackme.com/room/codeanalysis) |
| Common Linux Privesc | Linux privilege escalation | [tryhackme.com/room/commonlinuxprivesc](https://tryhackme.com/room/commonlinuxprivesc) |
| Content Discovery | Web enumeration | [tryhackme.com/room/contentdiscovery](https://tryhackme.com/room/contentdiscovery) |
| Cowboy Hacker | CTF / web | [tryhackme.com/room/cowboyhacker](https://tryhackme.com/room/cowboyhacker) |
| Crack the Hash | Hash cracking | [tryhackme.com/room/crackthehash](https://tryhackme.com/room/crackthehash) |
| Cryptography Intro | Crypto fundamentals | [tryhackme.com/room/cryptographyintro](https://tryhackme.com/room/cryptographyintro) |
| Cyber Governance & Regulation | GRC | [tryhackme.com/room/cybergovernanceregulation](https://tryhackme.com/room/cybergovernanceregulation) |
| DAST with ZAP | Dynamic application security testing | [tryhackme.com/room/dastzap](https://tryhackme.com/room/dastzap) |
| Data Exfiltration | C2 / exfil techniques | [tryhackme.com/room/dataxexfilt](https://tryhackme.com/room/dataxexfilt) |
| Easy CTF (Simple CTF) | CTF / beginner | [tryhackme.com/room/easyctf](https://tryhackme.com/room/easyctf) |
| Encryption — Crypto 101 | Symmetric/asymmetric crypto | [tryhackme.com/room/encryptioncrypto101](https://tryhackme.com/room/encryptioncrypto101) |
| Enumeration (Post-Exploit) | Post-exploitation enum | [tryhackme.com/room/enumerationpe](https://tryhackme.com/room/enumerationpe) |
| Exploiting AD | AD exploitation | [tryhackme.com/room/exploitingad](https://tryhackme.com/room/exploitingad) |
| File Inclusion | LFI / RFI | [tryhackme.com/room/fileinc](https://tryhackme.com/room/fileinc) |
| First Shift CTF | CTF challenge | [tryhackme.com/room/first-shift-ctf](https://tryhackme.com/room/first-shift-ctf) |
| Hackfinity Battle | CTF / multi-topic | [tryhackme.com/room/HackfinityBattle](https://tryhackme.com/room/HackfinityBattle) |
| Hydra | Password brute forcing | [tryhackme.com/room/hydra](https://tryhackme.com/room/hydra) |
| Ice | Windows exploitation / RDP | [tryhackme.com/room/ice](https://tryhackme.com/room/ice) |
| Intro to Network Security | Network fundamentals | [tryhackme.com/room/intronetworksecurity](https://tryhackme.com/room/intronetworksecurity) |
| John the Ripper | Hash / password cracking | [tryhackme.com/room/johntheripper0](https://tryhackme.com/room/johntheripper0) |
| Kenobi | Samba / ProFTPd / NFS | [tryhackme.com/room/kenobi](https://tryhackme.com/room/kenobi) |
| Lateral Movement & Pivoting | Post-exploitation movement | [tryhackme.com/room/lateralmovementandpivoting](https://tryhackme.com/room/lateralmovementandpivoting) |
| Linux Fundamentals Part 1 | Linux basics | [tryhackme.com/room/linuxfundamentalspart1](https://tryhackme.com/room/linuxfundamentalspart1) |
| Linux Fundamentals Part 2 | Linux intermediate | [tryhackme.com/room/linuxfundamentalspart2](https://tryhackme.com/room/linuxfundamentalspart2) |
| Linux Fundamentals Part 3 | Linux advanced | [tryhackme.com/room/linuxfundamentalspart3](https://tryhackme.com/room/linuxfundamentalspart3) |
| Linux PrivEsc | Linux privilege escalation | [tryhackme.com/room/linprivesc](https://tryhackme.com/room/linprivesc) |
| Linux Privilege Escalation | PrivEsc techniques | [tryhackme.com/room/linuxprivesc](https://tryhackme.com/room/linuxprivesc) |
| Linux System Hardening | Hardening techniques | [tryhackme.com/room/linuxsystemhardening](https://tryhackme.com/room/linuxsystemhardening) |
| Malware Introductory | Malware basics | [tryhackme.com/room/malmalintroductory](https://tryhackme.com/room/malmalintroductory) |
| Metasploit: Exploitation | Metasploit framework | [tryhackme.com/room/metasploitexploitation](https://tryhackme.com/room/metasploitexploitation) |
| Meterpreter | Post-exploitation shell | [tryhackme.com/room/meterpreter](https://tryhackme.com/room/meterpreter) |
| Network Security Challenge | Network CTF | [tryhackme.com/room/netsecchallenge](https://tryhackme.com/room/netsecchallenge) |
| OhSINT | OSINT investigation | [tryhackme.com/room/ohsint](https://tryhackme.com/room/ohsint) |
| OS Security | Operating system hardening | [tryhackme.com/room/operatingsystemsecurity](https://tryhackme.com/room/operatingsystemsecurity) |
| OWASP Juice Shop | Web application pentesting | [tryhackme.com/room/owaspjuiceshop](https://tryhackme.com/room/owaspjuiceshop) |
| OWASP Top 10 2021 | Web vulnerabilities | [tryhackme.com/room/owasptop102021](https://tryhackme.com/room/owasptop102021) |
| Password Attacks | Credential attacks | [tryhackme.com/room/passwordattacks](https://tryhackme.com/room/passwordattacks) |
| Persisting AD | AD persistence | [tryhackme.com/room/persistingad](https://tryhackme.com/room/persistingad) |
| Pickle Rick | Web / Linux CTF | [tryhackme.com/room/picklerick](https://tryhackme.com/room/picklerick) |
| Post Exploitation Basics | Post-exploit fundamentals | [tryhackme.com/room/postexploit](https://tryhackme.com/room/postexploit) |
| PowerShell (Hacking with PowerShell) | PowerShell for pentesters | [tryhackme.com/room/powershell](https://tryhackme.com/room/powershell) |
| Printer Hacking 101 | Network printer attacks | [tryhackme.com/room/printerhacking101](https://tryhackme.com/room/printerhacking101) |
| Red Team Recon | Passive/active recon | [tryhackme.com/room/redteamrecon](https://tryhackme.com/room/redteamrecon) |
| Nessus Redux | Vulnerability scanning | [tryhackme.com/room/rpnessusredux](https://tryhackme.com/room/rpnessusredux) |
| RootMe | Web / Linux CTF | [tryhackme.com/room/rrootme](https://tryhackme.com/room/rrootme) |
| SAST | Static application security testing | [tryhackme.com/room/sast](https://tryhackme.com/room/sast) |
| Security Risk Management | GRC / risk frameworks | [tryhackme.com/room/seriskmanagement](https://tryhackme.com/room/seriskmanagement) |
| Shodan | OSINT / attack surface | [tryhackme.com/room/shodan](https://tryhackme.com/room/shodan) |
| SQL Injection | SQLi attacks | [tryhackme.com/room/sql_injection](https://tryhackme.com/room/sql_injection) |
| Steel Mountain | Windows exploitation | [tryhackme.com/room/steelmountain](https://tryhackme.com/room/steelmountain) |
| The Lay of the Land | Post-exploitation recon | [tryhackme.com/room/thelayoftheland](https://tryhackme.com/room/thelayoftheland) |
| Threat Modelling | Threat modelling frameworks | [tryhackme.com/room/threatmodelling](https://tryhackme.com/room/threatmodelling) |
| Traverse | Web / path traversal | [tryhackme.com/room/traverse](https://tryhackme.com/room/traverse) |
| Upload Vulnerabilities | File upload attacks | [tryhackme.com/room/uploadvulns](https://tryhackme.com/room/uploadvulns) |
| Vulnerability Capstone | Vulnerability assessment | [tryhackme.com/room/vulnerabilitycapstone](https://tryhackme.com/room/vulnerabilitycapstone) |
| Vulnerability Management | VM process | [tryhackme.com/room/vulnerabilitymanagementkj](https://tryhackme.com/room/vulnerabilitymanagementkj) |
| Vulnversity | Web / PrivEsc | [tryhackme.com/room/vulnversity](https://tryhackme.com/room/vulnversity) |
| Walking an Application | Manual web testing | [tryhackme.com/room/walkinganapplication](https://tryhackme.com/room/walkinganapplication) |
| Weaponization | Payload creation | [tryhackme.com/room/weaponization](https://tryhackme.com/room/weaponization) |
| Windows AD Basics | Active Directory intro | [tryhackme.com/room/winadbasics](https://tryhackme.com/room/winadbasics) |
| Windows 10 PrivEsc | Windows privilege escalation | [tryhackme.com/room/windows10privesc](https://tryhackme.com/room/windows10privesc) |
| Windows Fundamentals 1 | Windows basics | [tryhackme.com/room/windowsfundamentals1](https://tryhackme.com/room/windowsfundamentals1) |
| Windows Fundamentals 2 | Windows intermediate | [tryhackme.com/room/windowsfundamentals2](https://tryhackme.com/room/windowsfundamentals2) |
| Windows Fundamentals 3 | Windows advanced | [tryhackme.com/room/windowsfundamentals3](https://tryhackme.com/room/windowsfundamentals3) |
| Windows Local Persistence | Persistence techniques | [tryhackme.com/room/windowslocalpersistence](https://tryhackme.com/room/windowslocalpersistence) |
| Windows PrivEsc 20 | Windows privilege escalation | [tryhackme.com/room/windowsprivesc20](https://tryhackme.com/room/windowsprivesc20) |
| Wireshark: Packet Operations | Traffic analysis | [tryhackme.com/room/wiresharkpacketoperations](https://tryhackme.com/room/wiresharkpacketoperations) |
| Wireshark: The Basics | Packet capture fundamentals | [tryhackme.com/room/wiresharkthebasics](https://tryhackme.com/room/wiresharkthebasics) |
| Wonderland | CTF / Alice in Wonderland | [tryhackme.com/room/wonderland](https://tryhackme.com/room/wonderland) |

---

### 🖥️ HTB Walkthroughs (`04-writeups-and-walkthroughs/htb-walkthroughs`)

HackTheBox machine walkthroughs covering Active Directory, Windows, and Linux targets.

---

### 🧪 Portfolio (`04-writeups-and-walkthroughs/portfolio`)

Professional-style security work built as portfolio pieces.

| Document | Description |
|---|---|
| `Incident Response/Post-Exploitation Incident Investigation.md` | Post-exploitation IR investigation write-up |
| `Incident Response/VM Bruteforce Detection.md` | Bruteforce attack detection and response |
| `Risk Assessment Case Study - OWASP Juice Shop/Part 1 - Threat Modeling.md` | Threat modelling (STRIDE) on Juice Shop |
| `Risk Assessment Case Study - OWASP Juice Shop/Part 2 - DAST and Remediation.md` | DAST scanning and remediation recommendations |
| `Risk Assessment Case Study - OWASP Juice Shop/Part 3 - SAST Implementation to CICD Pipeline.md` | SAST integration into CI/CD pipeline |
| `Threat Hunting/End of Year Suspicious Activity.md` | Threat hunt — year-end anomaly investigation |
| `Threat Hunting/Internal Data Exfiltration Investigation.md` | Internal data exfiltration investigation |
| `Threat Hunting/RDP Password Spray.md` | RDP password spray detection |
| `Threat Hunting/Suspicious Tor Browser Usage.md` | Tor browser usage investigation |
| `Vulnerability Management/Vulnerability Assessment and Remediation.md` | Full vulnerability assessment report |
| `Vulnerability Management/STIG Remediations/` | STIG compliance remediation scripts and notes |

---

### 📄 Pentest Reports (`04-writeups-and-walkthroughs/pentest-reports`)

Professional penetration testing reports in PDF format.

| Report | Target |
|---|---|
| `HTB - Administrator Report.pdf` | HackTheBox — Administrator machine |
| `HTB - Escape Report.pdf` | HackTheBox — Escape machine |

---

*Structured and maintained for personal use. PRs not accepted — fork it and make it your own.*
