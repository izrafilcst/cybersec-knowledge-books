# Cybersecurity Reading Guide 2026

> Categorization based on public research for each title, organized by area of expertise and maturity level.
> Updated: June 2026

---

## Table of Contents

- [Legend](#legend)
- [Foundations — Tools & Programming](#-foundations--tools--programming)
- [Red Team](#-red-team)
- [Blue Team](#-blue-team)
- [Career & Overview](#-career--overview)
- [Suggested Reading Trails](#-suggested-reading-trails)

---

## Legend

| Symbol | Meaning |
|--------|---------|
| `[BAS]` | Basic — ideal for beginners, no advanced prerequisites |
| `[INT]` | Intermediate — requires familiarity with security concepts and OS |
| `[ADV]` | Advanced — requires solid hands-on experience |
| `[REF]` | Quick reference / cheatsheet — use during work |
| `[MET]` | Methodology / practical approach |

---

## Foundations — Tools & Programming

> Essential reading before entering Red or Blue Team. Covers Linux, scripting and programming languages used in security.

### Basic

| Book | Level | Notes |
|------|-------|-------|
| `The-Linux-Command-Line.pdf` | `[BAS]` | Linux terminal mastery — foundation for any track |
| `How-Linux-Works.pdf` | `[BAS]` | How Linux works internally — processes, memory, I/O |
| `linux-basics-for-hackers.pdf` | `[BAS]` | Security-oriented Linux; great first book on the hacker track |
| `bash_cheat_sheet.pdf` | `[REF]` | Quick Bash reference |
| `Beyond-the-Basic-Stuff-with-Python.pdf` | `[BAS]` | Python beyond the basics; includes automation and projects |
| `make-python-talk.pdf` | `[BAS]` | Practical Python with voice synthesis and automation projects |
| `Ruby by Example.pdf` | `[BAS]` | Introduction to Ruby through practical examples |
| `the-book-of-ruby.pdf` | `[BAS]` | Ruby from scratch; good for understanding the language before using offensive scripts |
| `Build an HTML5 Game.pdf` | `[BAS]` | HTML5/JavaScript fundamentals; useful for understanding web attack surfaces |

### Intermediate

| Book | Level | Notes |
|------|-------|-------|
| `Wicked Cool Shell Scripts.pdf` | `[INT]` | Shell scripts for automation — foundation for Black Hat Bash |
| `wicked-cool-ruby-scripts.pdf` | `[INT]` | Ruby automation; useful for building custom tools |
| `Wicked Cool Perl Scripts.pdf` | `[INT]` | Perl for security automation and scraping |
| `perl-one-liners.pdf` | `[REF]` | Perl one-liner reference; excellent for text processing in CTFs |
| `No-Starch-Press-The-Rust.pdf` | `[INT]` | The Rust language — memory safety; growing presence in security tooling |

---

## Red Team

> Covers reconnaissance, application exploitation, penetration testing, bug bounty and vulnerability research.

### Basic

| Book | Level | Notes |
|------|-------|-------|
| `Penetration Testing - A hands-on introduction to Hacking.pdf` | `[BAS]` | Georgia Weidman — the most recommended introductory pentest book; covers the full cycle |
| `Violent Python.pdf` | `[BAS]` | Offensive Python scripts; port scanner, sniffer projects and more |
| `The_Art_of_Deception_by_Kelvin_Mitnick.pdf` | `[BAS]` | Social engineering by Kevin Mitnick — essential for understanding the human factor |
| `Kevin_Mitnick_-_The_Art_of_Intrusion.pdf` | `[BAS]` | Real intrusion cases narrated by Mitnick — accessible and motivating |
| `how-cybersecurity-really-works.pdf` | `[BAS]` | Overview of threats, attacks and defenses — excellent entry point |

### Intermediate

| Book | Level | Notes |
|------|-------|-------|
| `Black Hat Python, 2nd Edition.pdf` | `[INT]` | Offensive Python — network tools, trojans, exploits; classic reference |
| `Black-Hat-Bash.pdf` | `[INT]` | Bash for Red Team — recon, exploitation and post-exploitation automation |
| `Black-Hat-Go.pdf` | `[INT]` | Go for modern offensive tools — C2, proxies, scanners |
| `The Hacker Playbook 3 - Practical Guide To Penetration Testing.pdf` | `[INT]` | Practical pentest methodology; covers Active Directory, evasion and lateral movement |
| `Real-World Bug Hunting - A Field Guide to Web Hacking.pdf` | `[INT]` | Peter Yaworski — practical bug bounty guide with real cases; great for web hacking beginners |
| `bug-bounty-bootcamp.pdf` | `[INT]` | Vivian Weisman — complete bug bounty trail; covers recon, XSS, SSRF, SQLi and more |
| `The Web Application Hackers Handbook 2nd Edition.pdf` | `[INT]` | Comprehensive web hacking reference; covers nearly all web vulnerability classes |
| `Hacking APIs - Early Access.pdf` | `[INT]` | Cooney — REST/SOAP API security testing; authentication, fuzzing and logic flaws |
| `BlackHat GraphQL.pdf` | `[INT]` | Nick Aleks & Dolev Farhi — GraphQL API attacks; cutting-edge techniques and hands-on lab |
| `Mastering Modern Web Penetration Testing.pdf` | `[INT]` | Prakhar Prasad — web pentesting with OAuth, CORS, SSRF, IDOR; solid intermediate complement |
| `The tangled Web_ a guide to securing modern Web applications.pdf` | `[INT]` | Michal Zalewski — deep understanding of web architecture and its security pitfalls |
| `JavaScript Security.pdf` | `[INT]` | JavaScript-specific vulnerabilities in the browser and Node.js |
| `attacking network protocols.pdf` | `[INT]` | James Forshaw — network protocol analysis and exploitation; capture and reverse engineering focus |
| `Android Hacker's Handbook.pdf` | `[INT]` | Exploiting vulnerabilities on the Android platform |
| `IoT_Security_101__Deep_Dive_Into_Attack_Surface.pdf` | `[INT]` | IoT device attack surfaces — firmware, embedded protocols |
| `PracticalInternetofThingsSecurity-PacktPublishing.pdf` | `[INT]` | Hands-on IoT security; protocol analysis and hardware |
| `pentesting azure applications.pdf` | `[INT]` | Matt Burrough — pentest in Azure environments; good for cloud red team |
| `rtfm-red-team-field-manual.pdf` | `[REF]` | Red Team Field Manual — quick reference for offensive field commands |
| `DEF CON 23 - Jason-Haddix-How-Do-I-shot-Web.pdf` | `[MET]` | Jason Haddix — web recon and attack methodology; the talk that defined modern bug bounty |
| `Webbots, Spiders, and Screen Scrapers.pdf` | `[INT]` | Web automation for data collection — useful for OSINT and passive recon |
| `mining-social-media.pdf` | `[INT]` | OSINT techniques on social networks for target reconnaissance |
| `websecurityfordevelopers.pdf` | `[INT]` | Web security from the developer's perspective — understand defenses to bypass them |

### Advanced

| Book | Level | Notes |
|------|-------|-------|
| `The Bug Hunters Methodology 2.pdf` | `[ADV]` | Jason Haddix — deep methodology for experienced hunters |
| `Bug_Hunters_Methodology_Live_Day_Two_-_App_Analysis_Master.pdf` | `[ADV]` | Continuation with in-depth application analysis |
| `zseanos-methodology.pdf` | `[ADV]` | zseano (BugBountyHunter.com) — approach to 1000+ web app vulnerabilities; requires Burp Suite |
| `a bug hunters diary.pdf` | `[ADV]` | Tobias Klein — diary of 7 real bugs in iOS, VLC, OS X; full discovery-to-patch narrative |
| `From Day Zero to Zero Day A Hands-On Guide _compressed.pdf` | `[ADV]` | Eugene Lim — vuln research with code review, reversing and fuzzing; requires C and Python |
| `Enumerating Esoteric Attack Surfaces by Jann Moon.pdf` | `[ADV]` | Jann Horn (Project Zero) — non-obvious attack surface enumeration; elite reading |
| `LFI with phpinfo() assistance.pdf` | `[ADV]` | Specific and deep technique for LFI exploitation via phpinfo |
| `The Definitive Guide to Attacking the Internet of Things-No Starch Press (2021).pdf` | `[ADV]` | Complete advanced guide to IoT attacks — firmware, hardware and protocols |
| `AbhishekPawarNotes/` | `[MET]` | Notes and methodologies by Abhishek Pawar (recognized hunter) — advanced practical complement |

---

## Blue Team

> Covers defense, network analysis, incident response, hardening and secure development.

### Basic

| Book | Level | Notes |
|------|-------|-------|
| `Blue Team Field Manual.pdf` | `[REF]` | BTFM — essential reference for defensive commands and techniques; daily SOC/IR use |
| `The Art of Invisibility - The World's Most Famous Hacker Teaches You How to Be Safe in the Age of Big Brother and Big Data by Kevin Mitnick.pdf` | `[BAS]` | Mitnick — privacy, personal OPSEC and defense against surveillance; accessible to general audience |
| `how-cybersecurity-really-works.pdf` | `[BAS]` | Defensive view of threats, attacks and mitigations — also applicable to Blue Team |
| `Cyberjutsu.pdf` | `[BAS]` | Ben McCarty (ex-NSA) — defensive strategy inspired by ninja principles; great entry point into defensive mindset |

### Intermediate

| Book | Level | Notes |
|------|-------|-------|
| `practical packet analysis 3rd edition.pdf` | `[INT]` | Chris Sanders — traffic analysis with Wireshark; essential skill for SOC and IR analysts |
| `websecurityfordevelopers.pdf` | `[INT]` | Secure web application development — headers, CSP, authentication, CSRF |
| `PowerShell_for_Sysadmins.pdf` | `[INT]` | PowerShell for Windows admins — automation, IR scripts and hardening |
| `learn-windows-powershell-in-a-month-of-lunches.pdf` | `[INT]` | Progressive PowerShell in daily lessons; ideal for blue teamers in Windows environments |

---

## Career & Overview

> Books on career development, context and inspiring narratives.

| Book | Level | Notes |
|------|-------|-------|
| `How to make more money in Cybersecurity v3.0.pdf` | `[BAS]` | Career strategies, pricing and positioning in the cybersecurity market |
| `Mastering Cybersecurity Interviews 1.0.docx-3.pdf` | `[BAS]` | Preparation for technical and behavioral cybersecurity interviews |

---

## Suggested Reading Trails

### Trail 1 — Bug Bounty Hunter (From Zero)

```
1.  [BAS] The Linux Command Line
2.  [BAS] Linux Basics for Hackers
3.  [BAS] Beyond the Basic Stuff with Python
4.  [BAS] Penetration Testing (Georgia Weidman)
5.  [BAS] How Cybersecurity Really Works
6.  [INT] Real-World Bug Hunting (Peter Yaworski)
7.  [INT] Bug Bounty Bootcamp
8.  [INT] The Web Application Hackers Handbook
9.  [INT] Hacking APIs
10. [MET] DEF CON 23 - Jason Haddix (How Do I Shot Web)
11. [ADV] The Bug Hunters Methodology 2
12. [ADV] zseano's Methodology
```

### Trail 2 — Pentester / Red Teamer

```
1.  [BAS] The Linux Command Line
2.  [BAS] Linux Basics for Hackers
3.  [BAS] Violent Python
4.  [BAS] Penetration Testing (Georgia Weidman)
5.  [INT] Black Hat Python
6.  [INT] Black Hat Bash
7.  [INT] The Hacker Playbook 3
8.  [REF] RTFM — Red Team Field Manual
9.  [INT] Attacking Network Protocols
10. [INT] Pentesting Azure Applications
11. [ADV] From Day Zero to Zero Day
```

### Trail 3 — Blue Teamer / SOC Analyst

```
1.  [BAS] The Linux Command Line
2.  [BAS] How Linux Works
3.  [BAS] How Cybersecurity Really Works
4.  [BAS] Cyberjutsu
5.  [REF] Blue Team Field Manual
6.  [INT] Practical Packet Analysis
7.  [INT] PowerShell for Sysadmins
8.  [INT] Learn Windows PowerShell in a Month of Lunches
9.  [INT] Web Security for Developers
```

### Trail 4 — Web Security Specialist

```
1.  [INT] The Web Application Hackers Handbook
2.  [INT] The Tangled Web
3.  [INT] JavaScript Security
4.  [INT] Hacking APIs
5.  [INT] BlackHat GraphQL
6.  [INT] Mastering Modern Web Penetration Testing
7.  [MET] DEF CON 23 - Jason Haddix
8.  [ADV] The Bug Hunters Methodology 2
9.  [ADV] zseano's Methodology
10. [ADV] Enumerating Esoteric Attack Surfaces
```

### Trail 5 — IoT & Hardware Security

```
1.  [INT] IoT Security 101
2.  [INT] Practical Internet of Things Security
3.  [ADV] The Definitive Guide to Attacking the IoT
```

---

> **Tip:** Start with the trail that best aligns with your goal. Foundation books can be read in parallel with any trail.
