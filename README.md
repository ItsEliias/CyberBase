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

*Structured and maintained for personal use. PRs not accepted — fork it and make it your own.*
