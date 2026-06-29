# 5-Year Roadmap — Blue Team → Red Team (2026–2030)

> **Philosophy:** Build a solid defense foundation before going offensive. Those who understand how Blue Teams think, detect, alert, and investigate gain a real advantage in Red Teaming — they know what won't appear in logs, what will trigger an alert, and where the blind spots are.

---

## Overview

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
| 1 | `The-Linux-Command-Line.pdf` | `[BAS]` | Absolute prerequisite — nothing works without this |
| 2 | `How-Linux-Works.pdf` | `[BAS]` | Understanding processes, memory and I/O is foundational for forensics and IR |
| 3 | `how-cybersecurity-really-works.pdf` | `[BAS]` | Systemic view of threats — dual read: defensive now, offensive later |
| 4 | `Cyberjutsu.pdf` | `[BAS]` | Strategic defensive mindset — ex-NSA author; shapes SOC reasoning |
| 5 | `Blue Team Field Manual.pdf` | `[REF]` | Desk reference — use it daily from day one |
| 6 | `The Art of Invisibility (Mitnick).pdf` | `[BAS]` | OPSEC and privacy; understanding what attackers hide helps you look for it |

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **CompTIA Security+** | CompTIA | Mid-2026 | ~$370 USD |
| **CompTIA Linux+** *(optional)* | CompTIA | End-2026 | ~$338 USD |

> **Note:** Security+ is the most globally recognized entry-level Blue Team cert. Opens doors for SOC Tier 1 and junior analyst positions.

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
| 1 | `practical packet analysis 3rd edition.pdf` | `[INT]` | Wireshark is an essential tool — for SOC and for understanding what red teamers are sending |
| 2 | `PowerShell_for_Sysadmins.pdf` | `[INT]` | Hardening automation and incident response in Windows environments |
| 3 | `learn-windows-powershell-in-a-month-of-lunches.pdf` | `[INT]` | Reinforces PowerShell — progressive format, ideal for parallel reading |
| 4 | `linux-basics-for-hackers.pdf` | `[BAS]` | Re-reading with a different eye — now you see the tools attackers use |
| 5 | `Wicked Cool Shell Scripts.pdf` | `[INT]` | Bash automation — monitoring scripts, artifact collection |
| 6 | `Beyond-the-Basic-Stuff-with-Python.pdf` | `[BAS]` | Python for defensive automation and log parsing |

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **CompTIA CySA+** | CompTIA | Mid-2027 | ~$370 USD |
| **SC-200** (Microsoft Security Operations Analyst) | Microsoft | End-2027 | ~$165 USD |

> **Note:** CySA+ is the natural evolution of Security+ for SOC analysts. SC-200 is a major differentiator for corporate Azure/M365 environments.

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
| 1 | `websecurityfordevelopers.pdf` | `[INT]` | Dual read: you already know how to defend — now understand what devs get wrong |
| 2 | `The Web Application Hackers Handbook 2nd Edition.pdf` | `[INT]` | The web hacking bible — reference reading, no need to read linearly |
| 3 | `Penetration Testing - A hands-on introduction to Hacking.pdf` | `[BAS]` | The most recommended introductory pentest book |
| 4 | `Violent Python.pdf` | `[BAS]` | Offensive Python scripts; port scanners, sniffers — you already know what logs they generate |
| 5 | `attacking network protocols.pdf` | `[INT]` | James Forshaw — protocol analysis with an offensive lens; your Wireshark foundation helps a lot |
| 6 | `Real-World Bug Hunting - A Field Guide to Web Hacking.pdf` | `[INT]` | Peter Yaworski — first contact with real bug bounty; accessible and motivating |

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **eJPT** (eLearnSecurity Junior Penetration Tester) | INE Security | Early-2028 | ~$200 USD |
| **CompTIA PenTest+** | CompTIA | End-2028 | ~$370 USD |

> **Note:** eJPT is the best first step in pentest — practical, accessible and recognized. PenTest+ complements with methodology and reporting, useful for career transition.

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
| 1 | `Black Hat Python, 2nd Edition.pdf` | `[INT]` | Offensive Python — trojans, sniffers, exploits; you already understand the defensive counterpart |
| 2 | `Black-Hat-Bash.pdf` | `[INT]` | Recon, exploitation and post-exploitation automation in Bash |
| 3 | `bug-bounty-bootcamp.pdf` | `[INT]` | Vivian Weisman — complete trail: XSS, SSRF, SQLi, IDOR, recon |
| 4 | `Hacking APIs - Early Access.pdf` | `[INT]` | REST/SOAP API testing — authentication, fuzzing, logic; highly demanded in bounty |
| 5 | `BlackHat GraphQL.pdf` | `[INT]` | GraphQL attacks — growing and underexplored attack surface |
| 6 | `The Hacker Playbook 3.pdf` | `[INT]` | Active Directory, evasion, lateral movement; real red team methodology |
| 7 | `Black-Hat-Go.pdf` | `[INT]` | Go for offensive tools — C2, proxies, modern scanners |
| 8 | `rtfm-red-team-field-manual.pdf` | `[REF]` | Field reference for offensive operations |

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **OSCP** (OffSec Certified Professional) | Offensive Security | Mid-2029 | ~$1,499 USD (90-day lab) |
| **BSCP** (Burp Suite Certified Practitioner) | PortSwigger | End-2029 | ~$99 USD |

> **Note:** OSCP is the career milestone in pentest — requires discipline, but with 3 years of foundation you arrive prepared. BSCP validates web hacking with one of the best tools in the field.

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
| 1 | `The Bug Hunters Methodology 2.pdf` | `[ADV]` | Jason Haddix — deep methodology for experienced hunters |
| 2 | `Bug_Hunters_Methodology_Live_Day_Two.pdf` | `[ADV]` | Continuation — in-depth application analysis |
| 3 | `zseanos-methodology.pdf` | `[ADV]` | zseano — approach to 1000+ vulnerabilities in web apps; requires Burp Suite mastery |
| 4 | `From Day Zero to Zero Day.pdf` | `[ADV]` | Eugene Lim — vuln research with code review, reversing and fuzzing; requires C and Python |
| 5 | `Enumerating Esoteric Attack Surfaces - Jann Horn.pdf` | `[ADV]` | Project Zero — non-obvious attack surface enumeration; elite reading |
| 6 | `a bug hunters diary.pdf` | `[ADV]` | Tobias Klein — 7 real bugs narrated from discovery to patch; process reference |

### Choose Your Advanced Vertical

> After 4 years, you already know where you want to go deeper. Choose one:

**Web / Bug Bounty**
- Continue `zseanos-methodology` + practice HackerOne live programs
- Goal: **H1-702 / H1-415** (exclusive HackerOne conferences)

**Active Directory / Red Team Ops**
- `The Hacker Playbook 3` (review) + Covenant/Havoc C2 study
- Cert: **CRTO** (Certified Red Team Operator) — Sektor7/ZeroPointSecurity

**Cloud Red Team**
- `pentesting azure applications.pdf` + AWS/GCP equivalents
- Cert: **CARTP** (Certified Azure Red Team Professional) — Altered Security

**IoT & Hardware**
- `The Definitive Guide to Attacking the Internet of Things.pdf`
- `IoT_Security_101.pdf` (advanced review)

### Certifications

| Cert | Issuer | When | Approx. Cost |
|------|--------|------|--------------|
| **CRTO** (Certified Red Team Operator) | Zero Point Security | Mid-2030 | ~$600 USD |
| **OSEP** (OffSec Experienced Pentester) | Offensive Security | End-2030 | ~$1,499 USD |
| *(alternative)* **eCPPTv2** | INE Security | Mid-2030 | ~$400 USD |

> **Note:** OSEP is the leap after OSCP — focuses on AV/EDR evasion, pivoting and advanced operations. CRTO is excellent for Active Directory and C2.

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

> "The best red teamer I ever met spent 3 years in SOC before going offensive. He knew exactly what didn't show up in the logs." — common perspective in the community

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
