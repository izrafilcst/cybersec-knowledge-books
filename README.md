# Cybersecurity Study Library

> **Philosophy:** Build a solid defense foundation before going offensive. Those who understand how Blue Teams think, detect, alert, and investigate gain a real advantage in Red Teaming — they know what won't appear in logs, what will trigger an alert, and where the blind spots are.

---

## Repository Structure

```
.
├── fundacao/      — Linux, scripting, programming languages
├── red-team/      — Pentest, bug bounty, exploitation, vuln research
├── blue-team/     — Defense, SOC, IR, traffic analysis, hardening
├── carreira/      — Career, interviews, positioning
└── guia/          — Roadmap and reading guide
```

---

## 5-Year Roadmap — Blue Team → Red Team (2026–2030)

```
2026 ──► 2027 ──► 2028 ──► 2029 ──► 2030
 Blue      Blue    Bridge   Red       Red
 Found.    Inter.  Blue↔Red  Inter.   Advanced
```

| Year | Focus | Main Goal |
|------|-------|-----------|
| 2026 | Blue Team — Foundation | Understand the environment, tools and defensive mindset |
| 2027 | Blue Team — Intermediate | Threat analysis, incident response, scripting |
| 2028 | Transition — Bridge | Web security, basic pentest, emerging offensive vision |
| 2029 | Red Team — Intermediate | Practical pentest, bug bounty, offensive tools |
| 2030 | Red Team — Advanced | Vulnerability research, red team ops, specialization |

---

## Year 1 — 2026 · Blue Team Foundation

**Goal:** Master the terminal, understand how systems work, and internalize the defensive mindset.

### Reading List

| Order | Book | Level | Why Now |
|-------|------|-------|---------|
| 1 | [The Linux Command Line](fundacao/The-Linux-Command-Line.pdf) | `[BAS]` | Absolute prerequisite — nothing works without this |
| 2 | [How Linux Works](fundacao/How-Linux-Works.pdf) | `[BAS]` | Understanding processes, memory and I/O is foundational for forensics and IR |
| 3 | [How Cybersecurity Really Works](blue-team/how-cybersecurity-really-works.pdf) | `[BAS]` | Systemic view of threats — dual read: defensive now, offensive later |
| 4 | [Cyberjutsu](blue-team/Cyberjutsu.pdf) | `[BAS]` | Strategic defensive mindset — ex-NSA author; shapes SOC reasoning |
| 5 | [Blue Team Field Manual](blue-team/Blue%20Team%20Field%20Manual.pdf) | `[REF]` | Desk reference — use it daily from day one |
| 6 | [The Art of Invisibility (Mitnick)](blue-team/The%20Art%20of%20Invisibility%20-%20The%20World%27s%20Most%20Famous%20Hacker%20Teaches%20You%20How%20to%20Be%20Safe%20in%20the%20Age%20of%20Big%20Brother%20and%20Big%20Data%20by%20Kevin%20Mitnick.pdf) | `[BAS]` | OPSEC and privacy; understanding what attackers hide helps you look for it |

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **CompTIA Security+** | CompTIA | Mid-2026 | ~$370 USD |
| **CompTIA Linux+** *(optional)* | CompTIA | End-2026 | ~$338 USD |

### Labs & Practice

- TryHackMe — **Pre-Security** and **SOC Level 1** paths
- Blue Team Labs Online (BTLO) — log analysis and PCAP challenges
- Set up a home SIEM: Elastic Stack (ELK) or Splunk Free Tier

---

## Year 2 — 2027 · Blue Team Intermediate

**Goal:** Work on traffic analysis, automation and incident response. Start understanding defensive scripting.

### Reading List

| Order | Book | Level | Why Now |
|-------|------|-------|---------|
| 1 | [Practical Packet Analysis 3rd Edition](blue-team/practical%20packet%20analysis%203rd%20edition.pdf) | `[INT]` | Wireshark is an essential tool — for SOC and for understanding what red teamers are sending |
| 2 | [PowerShell for Sysadmins](blue-team/PowerShell_for_Sysadmins.pdf) | `[INT]` | Hardening automation and incident response in Windows environments |
| 3 | [Learn Windows PowerShell in a Month of Lunches](blue-team/learn-windows-powershell-in-a-month-of-lunches.pdf) | `[INT]` | Reinforces PowerShell — progressive format, ideal for parallel reading |
| 4 | [Linux Basics for Hackers](fundacao/linux-basics-for-hackers.pdf) | `[BAS]` | Re-reading with a different eye — now you see the tools attackers use |
| 5 | [Wicked Cool Shell Scripts](fundacao/Wicked%20Cool%20Shell%20Scripts.pdf) | `[INT]` | Bash automation — monitoring scripts, artifact collection |
| 6 | [Beyond the Basic Stuff with Python](fundacao/Beyond-the-Basic-Stuff-with-Python.pdf) | `[BAS]` | Python for defensive automation and log parsing |

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **CompTIA CySA+** | CompTIA | Mid-2027 | ~$370 USD |
| **SC-200** (Microsoft Security Operations Analyst) | Microsoft | End-2027 | ~$165 USD |

### Labs & Practice

- TryHackMe — **SOC Level 2** path
- BTLO — advanced malware analysis and threat hunting challenges
- Build home lab: pfSense + Zeek + Suricata + ELK
- Participate in CTFs under **forensics** and **misc** categories

---

## Year 3 — 2028 · Bridge — Blue Meets Red

**Goal:** Understand how attackers think using what you already know about defense. First solid contact with pentest and web hacking.

### Reading List

| Order | Book | Level | Why Now |
|-------|------|-------|---------|
| 1 | [Web Security for Developers](red-team/websecurityfordevelopers.pdf) | `[INT]` | Dual read: you already know how to defend — now understand what devs get wrong |
| 2 | [The Web Application Hackers Handbook](red-team/The%20Web%20Application%20Hackers%20Handbook%202nd%20Edition.pdf) | `[INT]` | The web hacking bible — reference reading, no need to read linearly |
| 3 | [Penetration Testing (Georgia Weidman)](red-team/Penetration%20Testing%20-%20A%20hands-on%20introduction%20to%20Hacking.pdf) | `[BAS]` | The most recommended introductory pentest book |
| 4 | [Violent Python](red-team/Violent%20Python.pdf) | `[BAS]` | Offensive Python scripts; port scanners, sniffers — you already know what logs they generate |
| 5 | [Attacking Network Protocols](red-team/attacking%20network%20protocols.pdf) | `[INT]` | James Forshaw — protocol analysis with an offensive lens; your Wireshark foundation helps a lot |
| 6 | [Real-World Bug Hunting](red-team/Real-World%20Bug%20Hunting%20-%20A%20Field%20Guide%20to%20Web%20Hacking.pdf) | `[INT]` | Peter Yaworski — first contact with real bug bounty; accessible and motivating |

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **eJPT** (eLearnSecurity Junior Penetration Tester) | INE Security | Early-2028 | ~$200 USD |
| **CompTIA PenTest+** | CompTIA | End-2028 | ~$370 USD |

### Labs & Practice

- HackTheBox — **Easy** machines in the Starting Point category
- TryHackMe — **Jr Penetration Tester** path
- PortSwigger Web Security Academy — free labs, all basic modules
- Install and learn Burp Suite Community Edition

---

## Year 4 — 2029 · Red Team Intermediate

**Goal:** Practical pentest, active bug bounty, offensive tools and focus on web/API hacking.

### Reading List

| Order | Book | Level | Why Now |
|-------|------|-------|---------|
| 1 | [Black Hat Python, 2nd Edition](red-team/Black%20Hat%20Python%2C%202nd%20Edition.pdf) | `[INT]` | Offensive Python — trojans, sniffers, exploits; you already understand the defensive counterpart |
| 2 | [Black Hat Bash](red-team/Black-Hat-Bash.pdf) | `[INT]` | Recon, exploitation and post-exploitation automation in Bash |
| 3 | [Bug Bounty Bootcamp](red-team/bug-bounty-bootcamp.pdf) | `[INT]` | Vivian Weisman — complete trail: XSS, SSRF, SQLi, IDOR, recon |
| 4 | [Hacking APIs](red-team/Hacking%20APIs%20-%20Early%20Access.pdf) | `[INT]` | REST/SOAP API testing — authentication, fuzzing, logic; highly demanded in bounty |
| 5 | [BlackHat GraphQL](red-team/BlackHat%20GraphQL.pdf) | `[INT]` | GraphQL attacks — growing and underexplored attack surface |
| 6 | [The Hacker Playbook 3](red-team/The%20Hacker%20Playbook%203%20-%20Practical%20Guide%20To%20Penetration%20Testing.pdf) | `[INT]` | Active Directory, evasion, lateral movement; real red team methodology |
| 7 | [Black Hat Go](red-team/Black-Hat-Go.pdf) | `[INT]` | Go for offensive tools — C2, proxies, modern scanners |
| 8 | [RTFM — Red Team Field Manual](red-team/rtfm-red-team-field-manual.pdf) | `[REF]` | Field reference for offensive operations |

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **OSCP** (OffSec Certified Professional) | Offensive Security | Mid-2029 | ~$1,499 USD (90-day lab) |
| **BSCP** (Burp Suite Certified Practitioner) | PortSwigger | End-2029 | ~$99 USD |

### Labs & Practice

- HackTheBox — **Medium/Hard** machines, **Pro Labs (Offshore or RastaLabs)**
- PortSwigger Web Security Academy — all advanced labs (SSRF, XXE, OAuth, SSTI)
- Actively participate in bug bounty: **HackerOne** and **Bugcrowd**
- Practice vulnerability reports — technical writing is a differentiator in bounty and pentest

---

## Year 5 — 2030 · Red Team Advanced

**Goal:** Vulnerability research, red team operations, specialization in one vertical (web, AD, IoT, cloud or vuln research).

### Reading List

| Order | Book | Level | Why Now |
|-------|------|-------|---------|
| 1 | [The Bug Hunters Methodology 2](red-team/The%20Bug%20Hunters%20Methodology%202.pdf) | `[ADV]` | Jason Haddix — deep methodology for experienced hunters |
| 2 | [Bug Hunters Methodology Live Day Two](red-team/Bug_Hunters_Methodology_Live_Day_Two_-_App_Analysis_Master.pdf) | `[ADV]` | Continuation — in-depth application analysis |
| 3 | [zseano's Methodology](red-team/zseanos-methodology.pdf) | `[ADV]` | zseano — approach to 1000+ vulnerabilities in web apps; requires Burp Suite mastery |
| 4 | [From Day Zero to Zero Day](red-team/From%20Day%20Zero%20to%20Zero%20Day%20A%20Hands-On%20Guide%20_compressed.pdf) | `[ADV]` | Eugene Lim — vuln research with code review, reversing and fuzzing; requires C and Python |
| 5 | [Enumerating Esoteric Attack Surfaces](red-team/Enumerating%20Esoteric%20Attack%20Surfaces%20by%20Jann%20Moon.pdf) | `[ADV]` | Jann Horn (Project Zero) — enumeration of non-obvious attack surfaces; elite reading |
| 6 | [A Bug Hunter's Diary](red-team/a%20bug%20hunters%20diary.pdf) | `[ADV]` | Tobias Klein — 7 real bugs narrated from discovery to patch; process reference |

### Advanced Vertical — Choose One

**Web / Bug Bounty**
- Continue `zseanos-methodology` + practice HackerOne live programs
- Goal: **H1-702 / H1-415** (exclusive HackerOne conferences)

**Active Directory / Red Team Ops**
- `The Hacker Playbook 3` (review) + Covenant/Havoc C2 study
- Cert: **CRTO** (Certified Red Team Operator) — Zero Point Security

**Cloud Red Team**
- [Pentesting Azure Applications](red-team/pentesting%20azure%20applications.pdf) + AWS/GCP equivalents
- Cert: **CARTP** (Certified Azure Red Team Professional) — Altered Security

**IoT & Hardware**
- [The Definitive Guide to Attacking the IoT](red-team/The%20Definitive%20Guide%20to%20Attacking%20the%20Internet%20of%20Things-No%20Starch%20Press%20%282021%29.pdf)
- [IoT Security 101](red-team/IoT_Security_101__Deep_Dive_Into_Attack_Surface.pdf) (advanced review)

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **CRTO** (Certified Red Team Operator) | Zero Point Security | Mid-2030 | ~$600 USD |
| **OSEP** (OffSec Experienced Pentester) | Offensive Security | End-2030 | ~$1,499 USD |
| *(alternative)* **eCPPTv2** | INE Security | Mid-2030 | ~$400 USD |

### Labs & Practice

- HackTheBox Pro Labs: **Offshore** and **Dante**
- Build AD home lab: Windows Server + domain + GPOs + Bloodhound
- Contribute to open-source offensive security tools
- Publish CTF write-ups and bug bounty findings

---

## Certifications Summary

| Year | Cert | Level | Area |
|------|------|-------|------|
| 2026 | CompTIA Security+ | Foundation | Blue |
| 2026 | CompTIA Linux+ *(optional)* | Foundation | Blue |
| 2027 | CompTIA CySA+ | Intermediate | Blue |
| 2027 | SC-200 (Microsoft) | Intermediate | Blue |
| 2028 | eJPT | Basic | Red |
| 2028 | CompTIA PenTest+ | Basic | Red |
| 2029 | OSCP | Intermediate | Red |
| 2029 | BSCP | Intermediate | Red/Web |
| 2030 | CRTO or OSEP | Advanced | Red |

---

## Why Blue First?

| Advantage | How It Applies in Red Teaming |
|-----------|-------------------------------|
| You know what generates alerts | Avoids obvious IoCs — stealthier movement |
| You know defense tools | Understands what Splunk, Defender and Zeek see |
| You've analyzed logs | Knows how to cover tracks and manipulate events |
| You've studied malware | Understands persistence and evasion techniques |
| You've done threat hunting | Thinks like the defender who will hunt you |
| You've configured SIEMs | Knows where the coverage blind spots are |

---

## Full Library — Organized by Category

> Legend: `[BAS]` Basic · `[INT]` Intermediate · `[ADV]` Advanced · `[REF]` Reference · `[MET]` Methodology

---

### `fundacao/` — Foundations: Tools & Programming

#### Basic

| Book | Level | Notes |
|------|-------|-------|
| [The Linux Command Line](fundacao/The-Linux-Command-Line.pdf) | `[BAS]` | Linux terminal mastery — foundation for any path |
| [How Linux Works](fundacao/How-Linux-Works.pdf) | `[BAS]` | How Linux works internally — processes, memory, I/O |
| [Linux Basics for Hackers](fundacao/linux-basics-for-hackers.pdf) | `[BAS]` | Security-oriented Linux; great first book for the hacker track |
| [Bash Cheat Sheet](fundacao/bash_cheat_sheet.pdf) | `[REF]` | Quick Bash reference |
| [Beyond the Basic Stuff with Python](fundacao/Beyond-the-Basic-Stuff-with-Python.pdf) | `[BAS]` | Python beyond the basics; includes automation and projects |
| [Make Python Talk](fundacao/make-python-talk.pdf) | `[BAS]` | Practical Python with voice synthesis and automation projects |
| [Ruby by Example](fundacao/Ruby%20by%20Example.pdf) | `[BAS]` | Introduction to Ruby through practical examples |
| [The Book of Ruby](fundacao/the-book-of-ruby.pdf) | `[BAS]` | Ruby from scratch; good for understanding the language before using offensive scripts |
| [Build an HTML5 Game](fundacao/Build%20an%20HTML5%20Game.pdf) | `[BAS]` | HTML5/JavaScript fundamentals; useful for understanding web attack surfaces |

#### Intermediate

| Book | Level | Notes |
|------|-------|-------|
| [Wicked Cool Shell Scripts](fundacao/Wicked%20Cool%20Shell%20Scripts.pdf) | `[INT]` | Shell scripts for automation — foundation for Black Hat Bash |
| [Wicked Cool Ruby Scripts](fundacao/wicked-cool-ruby-scripts.pdf) | `[INT]` | Ruby automation; useful for building custom tools |
| [Wicked Cool Perl Scripts](fundacao/Wicked%20Cool%20Perl%20Scripts.pdf) | `[INT]` | Perl for security automation and scraping |
| [Perl One-Liners](fundacao/perl-one-liners.pdf) | `[REF]` | Perl one-liner reference; excellent for text processing in CTFs |
| [The Rust Programming Language](fundacao/No-Starch-Press-The-Rust.pdf) | `[INT]` | Rust — memory safety; growing presence in security tooling |

---

### `red-team/` — Red Team

#### Basic

| Book | Level | Notes |
|------|-------|-------|
| [Penetration Testing (Georgia Weidman)](red-team/Penetration%20Testing%20-%20A%20hands-on%20introduction%20to%20Hacking.pdf) | `[BAS]` | The most recommended introductory pentest book; covers the full cycle |
| [Violent Python](red-team/Violent%20Python.pdf) | `[BAS]` | Offensive Python scripts; port scanner, sniffer and more |
| [The Art of Deception (Mitnick)](red-team/The_Art_of_Deception_by_Kelvin_Mitnick.pdf) | `[BAS]` | Social engineering by Kevin Mitnick — essential for understanding the human factor |
| [The Art of Intrusion (Mitnick)](red-team/Kevin_Mitnick_-_The_Art_of_Intrusion.pdf) | `[BAS]` | Real intrusion cases narrated by Mitnick — accessible and motivating |

#### Intermediate

| Book | Level | Notes |
|------|-------|-------|
| [Black Hat Python, 2nd Edition](red-team/Black%20Hat%20Python%2C%202nd%20Edition.pdf) | `[INT]` | Offensive Python — network tools, trojans, exploits; classic reference |
| [Black Hat Bash](red-team/Black-Hat-Bash.pdf) | `[INT]` | Bash for Red Team — recon, exploitation and post-exploitation automation |
| [Black Hat Go](red-team/Black-Hat-Go.pdf) | `[INT]` | Go for modern offensive tools — C2, proxies, scanners |
| [The Hacker Playbook 3](red-team/The%20Hacker%20Playbook%203%20-%20Practical%20Guide%20To%20Penetration%20Testing.pdf) | `[INT]` | Practical pentest methodology; covers Active Directory, evasion and lateral movement |
| [Real-World Bug Hunting](red-team/Real-World%20Bug%20Hunting%20-%20A%20Field%20Guide%20to%20Web%20Hacking.pdf) | `[INT]` | Peter Yaworski — practical bug bounty guide with real cases |
| [Bug Bounty Bootcamp](red-team/bug-bounty-bootcamp.pdf) | `[INT]` | Vivian Weisman — full trail: recon, XSS, SSRF, SQLi and more |
| [The Web Application Hackers Handbook](red-team/The%20Web%20Application%20Hackers%20Handbook%202nd%20Edition.pdf) | `[INT]` | Comprehensive web hacking reference; covers nearly all vulnerability classes |
| [Hacking APIs](red-team/Hacking%20APIs%20-%20Early%20Access.pdf) | `[INT]` | REST/SOAP API security testing; authentication, fuzzing and logic flaws |
| [BlackHat GraphQL](red-team/BlackHat%20GraphQL.pdf) | `[INT]` | GraphQL API attacks; cutting-edge techniques and hands-on lab |
| [Mastering Modern Web Penetration Testing](red-team/Mastering%20Modern%20Web%20Penetration%20Testing.pdf) | `[INT]` | Web pentesting with OAuth, CORS, SSRF, IDOR; solid intermediate complement |
| [The Tangled Web](red-team/The%20tangled%20Web_%20a%20guide%20to%20securing%20modern%20Web%20applications.pdf) | `[INT]` | Michal Zalewski — deep understanding of web architecture and its security pitfalls |
| [JavaScript Security](red-team/JavaScript%20Security.pdf) | `[INT]` | JavaScript-specific vulnerabilities in the browser and Node.js |
| [Attacking Network Protocols](red-team/attacking%20network%20protocols.pdf) | `[INT]` | James Forshaw — network protocol analysis and exploitation |
| [Android Hacker's Handbook](red-team/Android%20Hacker%27s%20Handbook.pdf) | `[INT]` | Exploiting vulnerabilities on the Android platform |
| [IoT Security 101](red-team/IoT_Security_101__Deep_Dive_Into_Attack_Surface.pdf) | `[INT]` | IoT device attack surfaces — firmware, embedded protocols |
| [Practical Internet of Things Security](red-team/PracticalInternetofThingsSecurity-PacktPublishing.pdf) | `[INT]` | Hands-on IoT security; protocol analysis and hardware |
| [Pentesting Azure Applications](red-team/pentesting%20azure%20applications.pdf) | `[INT]` | Matt Burrough — pentest in Azure environments; good for cloud red team |
| [RTFM — Red Team Field Manual](red-team/rtfm-red-team-field-manual.pdf) | `[REF]` | Quick reference for offensive field commands |
| [DEF CON 23 — Jason Haddix](red-team/DEF%20CON%2023%20-%20Jason-Haddix-How-Do-I-shot-Web.pdf) | `[MET]` | Web recon and attack methodology; the talk that defined modern bug bounty |
| [Webbots, Spiders, and Screen Scrapers](red-team/Webbots%2C%20Spiders%2C%20and%20Screen%20Scrapers.pdf) | `[INT]` | Web automation for data collection — useful for OSINT and passive recon |
| [Mining Social Media](red-team/mining-social-media.pdf) | `[INT]` | OSINT techniques on social networks for target reconnaissance |
| [Web Security for Developers](red-team/websecurityfordevelopers.pdf) | `[INT]` | Web security from the developer's perspective — understand defenses to bypass them |

#### Advanced

| Book | Level | Notes |
|------|-------|-------|
| [The Bug Hunters Methodology 2](red-team/The%20Bug%20Hunters%20Methodology%202.pdf) | `[ADV]` | Jason Haddix — deep methodology for experienced hunters |
| [Bug Hunters Methodology Live Day Two](red-team/Bug_Hunters_Methodology_Live_Day_Two_-_App_Analysis_Master.pdf) | `[ADV]` | Continuation with in-depth application analysis |
| [zseano's Methodology](red-team/zseanos-methodology.pdf) | `[ADV]` | zseano — approach to 1000+ vulnerabilities in web apps; requires Burp Suite |
| [A Bug Hunter's Diary](red-team/a%20bug%20hunters%20diary.pdf) | `[ADV]` | Tobias Klein — diary of 7 real bugs in iOS, VLC, OS X; full discovery-to-patch narrative |
| [From Day Zero to Zero Day](red-team/From%20Day%20Zero%20to%20Zero%20Day%20A%20Hands-On%20Guide%20_compressed.pdf) | `[ADV]` | Eugene Lim — vuln research with code review, reversing and fuzzing; requires C and Python |
| [Enumerating Esoteric Attack Surfaces](red-team/Enumerating%20Esoteric%20Attack%20Surfaces%20by%20Jann%20Moon.pdf) | `[ADV]` | Jann Horn (Project Zero) — non-obvious attack surface enumeration; elite reading |
| [LFI with phpinfo() Assistance](red-team/LFI%20with%20phpinfo%28%29%20assistance.pdf) | `[ADV]` | Specific and deep technique for LFI exploitation via phpinfo |
| [The Definitive Guide to Attacking the IoT](red-team/The%20Definitive%20Guide%20to%20Attacking%20the%20Internet%20of%20Things-No%20Starch%20Press%20%282021%29.pdf) | `[ADV]` | Complete advanced guide to IoT attacks — firmware, hardware and protocols |

---

### `blue-team/` — Blue Team

#### Basic

| Book | Level | Notes |
|------|-------|-------|
| [Blue Team Field Manual](blue-team/Blue%20Team%20Field%20Manual.pdf) | `[REF]` | BTFM — essential reference for defensive commands and techniques; daily SOC/IR use |
| [The Art of Invisibility (Mitnick)](blue-team/The%20Art%20of%20Invisibility%20-%20The%20World%27s%20Most%20Famous%20Hacker%20Teaches%20You%20How%20to%20Be%20Safe%20in%20the%20Age%20of%20Big%20Brother%20and%20Big%20Data%20by%20Kevin%20Mitnick.pdf) | `[BAS]` | Mitnick — privacy, personal OPSEC and defense against surveillance |
| [How Cybersecurity Really Works](blue-team/how-cybersecurity-really-works.pdf) | `[BAS]` | Defensive view of threats, attacks and mitigations |
| [Cyberjutsu](blue-team/Cyberjutsu.pdf) | `[BAS]` | Ben McCarty (ex-NSA) — defensive strategy; great entry point into defensive mindset |

#### Intermediate

| Book | Level | Notes |
|------|-------|-------|
| [Practical Packet Analysis 3rd Edition](blue-team/practical%20packet%20analysis%203rd%20edition.pdf) | `[INT]` | Chris Sanders — traffic analysis with Wireshark; essential skill for SOC and IR analysts |
| [Web Security for Developers](red-team/websecurityfordevelopers.pdf) | `[INT]` | Secure web application development — headers, CSP, authentication, CSRF *(in `red-team/`)* |
| [PowerShell for Sysadmins](blue-team/PowerShell_for_Sysadmins.pdf) | `[INT]` | PowerShell for Windows admins — automation, IR scripts and hardening |
| [Learn Windows PowerShell in a Month of Lunches](blue-team/learn-windows-powershell-in-a-month-of-lunches.pdf) | `[INT]` | Progressive PowerShell in daily lessons; ideal for blue teamers in Windows environments |

---

### `carreira/` — Career & Overview

| Book | Level | Notes |
|------|-------|-------|
| [How to Make More Money in Cybersecurity](carreira/How%20to%20make%20more%20money%20in%20Cybersecurity%20v3.0.pdf) | `[BAS]` | Career strategies, pricing and positioning in the cybersecurity market |
| [Mastering Cybersecurity Interviews](carreira/Mastering%20Cybersecurity%20Interviews%201.0.docx-3.pdf) | `[BAS]` | Preparation for technical and behavioral cybersecurity interviews |

---

## Suggested Reading Trails

### Trail 1 — Bug Bounty Hunter (From Zero)

```
1.  [BAS] fundacao/  The Linux Command Line
2.  [BAS] fundacao/  Linux Basics for Hackers
3.  [BAS] fundacao/  Beyond the Basic Stuff with Python
4.  [BAS] red-team/  Penetration Testing (Georgia Weidman)
5.  [BAS] blue-team/ How Cybersecurity Really Works
6.  [INT] red-team/  Real-World Bug Hunting (Peter Yaworski)
7.  [INT] red-team/  Bug Bounty Bootcamp
8.  [INT] red-team/  The Web Application Hackers Handbook
9.  [INT] red-team/  Hacking APIs
10. [MET] red-team/  DEF CON 23 - Jason Haddix (How Do I Shot Web)
11. [ADV] red-team/  The Bug Hunters Methodology 2
12. [ADV] red-team/  zseano's Methodology
```

### Trail 2 — Pentester / Red Teamer

```
1.  [BAS] fundacao/  The Linux Command Line
2.  [BAS] fundacao/  Linux Basics for Hackers
3.  [BAS] red-team/  Violent Python
4.  [BAS] red-team/  Penetration Testing (Georgia Weidman)
5.  [INT] red-team/  Black Hat Python
6.  [INT] red-team/  Black Hat Bash
7.  [INT] red-team/  The Hacker Playbook 3
8.  [REF] red-team/  RTFM — Red Team Field Manual
9.  [INT] red-team/  Attacking Network Protocols
10. [INT] red-team/  Pentesting Azure Applications
11. [ADV] red-team/  From Day Zero to Zero Day
```

### Trail 3 — Blue Teamer / SOC Analyst

```
1.  [BAS] fundacao/  The Linux Command Line
2.  [BAS] fundacao/  How Linux Works
3.  [BAS] blue-team/ How Cybersecurity Really Works
4.  [BAS] blue-team/ Cyberjutsu
5.  [REF] blue-team/ Blue Team Field Manual
6.  [INT] blue-team/ Practical Packet Analysis
7.  [INT] blue-team/ PowerShell for Sysadmins
8.  [INT] blue-team/ Learn Windows PowerShell in a Month of Lunches
9.  [INT] red-team/  Web Security for Developers
```

### Trail 4 — Web Security Specialist

```
1.  [INT] red-team/  The Web Application Hackers Handbook
2.  [INT] red-team/  The Tangled Web
3.  [INT] red-team/  JavaScript Security
4.  [INT] red-team/  Hacking APIs
5.  [INT] red-team/  BlackHat GraphQL
6.  [INT] red-team/  Mastering Modern Web Penetration Testing
7.  [MET] red-team/  DEF CON 23 - Jason Haddix
8.  [ADV] red-team/  The Bug Hunters Methodology 2
9.  [ADV] red-team/  zseano's Methodology
10. [ADV] red-team/  Enumerating Esoteric Attack Surfaces
```

### Trail 5 — IoT & Hardware Security

```
1.  [INT] red-team/  IoT Security 101
2.  [INT] red-team/  Practical Internet of Things Security
3.  [ADV] red-team/  The Definitive Guide to Attacking the IoT
```

---

## Practice Platforms

| Platform | Use | Cost |
|----------|-----|------|
| TryHackMe | Guided Blue and Red Team paths | Free / ~$14/mo |
| HackTheBox | CTF + Pro Labs | Free / ~$14/mo |
| Blue Team Labs Online | Forensics and IR | Free / Pro |
| PortSwigger Web Academy | Web hacking labs | Free |
| HackerOne / Bugcrowd | Real bug bounty | Free |
| INE / eLearnSecurity | Courses + certs | ~$750/yr |
| Offensive Security (OffSec) | OSCP/OSEP/labs | Per exam |

---

> **Remember:** Certifications prove you studied — a portfolio proves you know. Balance both. A well-written HTB machine write-up or a real bug bounty report is worth more in an interview than any certification alone.
