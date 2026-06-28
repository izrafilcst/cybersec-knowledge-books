# Guia de Leitura em Cibersegurança 2026

> Categorização baseada em pesquisa pública sobre cada título, separada por área de atuação e nível de maturidade.
> Atualizado em: Junho de 2026

---

## Sumário

- [Legenda](#legenda)
- [Fundação — Ferramentas e Programação](#-fundação--ferramentas-e-programação)
- [Red Team](#-red-team)
- [Blue Team](#-blue-team)
- [Carreira e Visão Geral](#-carreira-e-visão-geral)
- [Trilhas de Leitura Sugeridas](#-trilhas-de-leitura-sugeridas)

---

## Legenda

| Símbolo | Significado |
|---------|------------|
| `[BAS]` | Básico — ideal para iniciantes, sem pré-requisitos avançados |
| `[INT]` | Intermediário — requer familiaridade com conceitos de segurança e SO |
| `[AVA]` | Avançado — exige experiência prática sólida |
| `[REF]` | Referência rápida / cheatsheet — use durante o trabalho |
| `[MET]` | Metodologia / abordagem prática |

---

## Fundação — Ferramentas e Programação

> Leitura essencial antes de entrar em Red ou Blue Team. Cobre Linux, scripting e linguagens de programação usadas em segurança.

### Básico

| Livro | Nível | Notas |
|-------|-------|-------|
| `The-Linux-Command-Line.pdf` | `[BAS]` | Domínio do terminal Linux — base para qualquer trilha |
| `How-Linux-Works.pdf` | `[BAS]` | Como o Linux funciona internamente — processos, memória, I/O |
| `linux-basics-for-hackers.pdf` | `[BAS]` | Linux voltado para segurança ofensiva; ótimo primeiro livro da trilha hacker |
| `bash_cheat_sheet.pdf` | `[REF]` | Referência rápida de Bash |
| `Beyond-the-Basic-Stuff-with-Python.pdf` | `[BAS]` | Aprofundamento em Python além do básico; inclui automação e projetos |
| `make-python-talk.pdf` | `[BAS]` | Python prático com projetos de síntese de voz e automação |
| `Ruby by Example.pdf` | `[BAS]` | Introdução à linguagem Ruby por exemplos práticos |
| `the-book-of-ruby.pdf` | `[BAS]` | Ruby completo do zero; bom para entender a linguagem antes de usar scripts ofensivos |
| `Build an HTML5 Game.pdf` | `[BAS]` | Fundamentos de HTML5/JavaScript; útil para compreender superfícies web |

### Intermediário

| Livro | Nível | Notas |
|-------|-------|-------|
| `Wicked Cool Shell Scripts.pdf` | `[INT]` | Scripts de shell para automação — base para Black Hat Bash |
| `wicked-cool-ruby-scripts.pdf` | `[INT]` | Automação com Ruby; útil para criar ferramentas customizadas |
| `Wicked Cool Perl Scripts.pdf` | `[INT]` | Perl para automação de segurança e scraping |
| `perl-one-liners.pdf` | `[REF]` | Referência de Perl one-liners; excelente para processamento de texto em CTF |
| `No-Starch-Press-The-Rust.pdf` | `[INT]` | A linguagem Rust — segurança de memória; crescente na área de ferramentas de segurança |

---

## Red Team

> Abrange reconhecimento, exploração de aplicações, testes de penetração, bug bounty e pesquisa de vulnerabilidades.

### Básico

| Livro | Nível | Notas |
|-------|-------|-------|
| `Penetration Testing - A hands-on introduction to Hacking.pdf` | `[BAS]` | Georgia Weidman — o livro introdutório de pentest mais recomendado; cobre o ciclo completo |
| `Violent Python.pdf` | `[BAS]` | Scripts ofensivos em Python; projetos de port scanner, sniffer e mais |
| `The_Art_of_Deception_by_Kelvin_Mitnick.pdf` | `[BAS]` | Engenharia social por Kevin Mitnick — essencial para compreender o fator humano |
| `Kevin_Mitnick_-_The_Art_of_Intrusion.pdf` | `[BAS]` | Casos reais de intrusão narrados por Mitnick — leitura acessível e motivadora |
| `how-cybersecurity-really-works.pdf` | `[BAS]` | Visão geral de ameaças, ataques e defesas — excelente ponto de entrada |

### Intermediário

| Livro | Nível | Notas |
|-------|-------|-------|
| `Black Hat Python, 2nd Edition.pdf` | `[INT]` | Python para ofensiva — ferramentas de rede, trojans, exploits; referência clássica |
| `Black-Hat-Bash.pdf` | `[INT]` | Bash para Red Team — automação de reconhecimento, exploração e pós-exploração |
| `Black-Hat-Go.pdf` | `[INT]` | Go para criação de ferramentas ofensivas modernas — C2, proxies, scanners |
| `The Hacker Playbook 3 - Practical Guide To Penetration Testing.pdf` | `[INT]` | Metodologia prática de pentest; cobre Active Directory, evasão e movimento lateral |
| `Real-World Bug Hunting - A Field Guide to Web Hacking.pdf` | `[INT]` | Peter Yaworski — guia prático de bug bounty com casos reais; ótimo para iniciantes em web hacking |
| `bug-bounty-bootcamp.pdf` | `[INT]` | Vivian Weisman — trilha completa de bug bounty; cobre recon, XSS, SSRF, SQLi e mais |
| `The Web Application Hackers Handbook 2nd Edition.pdf` | `[INT]` | Referência abrangente de web hacking; cobre quase todas as classes de vulnerabilidades web |
| `Hacking APIs - Early Access.pdf` | `[INT]` | Cooney — testes de segurança em APIs REST/SOAP; cobre autenticação, fuzzing e abusos de lógica |
| `BlackHat GraphQL.pdf` | `[INT]` | Nick Aleks & Dolev Farhi — ataque a APIs GraphQL; inclui técnicas inéditas e laboratório prático |
| `Mastering Modern Web Penetration Testing.pdf` | `[INT]` | Prakhar Prasad — web pentesting com OAuth, CORS, SSRF, IDOR; bom complemento intermediário |
| `The tangled Web_ a guide to securing modern Web applications.pdf` | `[INT]` | Michal Zalewski — compreensão profunda da arquitetura web e suas armadilhas de segurança |
| `JavaScript Security.pdf` | `[INT]` | Vulnerabilidades específicas de JavaScript no browser e Node.js |
| `attacking network protocols.pdf` | `[INT]` | James Forshaw — análise e exploração de protocolos de rede; foco em captura e engenharia reversa de protocolos |
| `Android Hacker's Handbook.pdf` | `[INT]` | Exploração de vulnerabilidades na plataforma Android |
| `IoT_Security_101__Deep_Dive_Into_Attack_Surface.pdf` | `[INT]` | Superfícies de ataque em dispositivos IoT — firmware, protocolos embarcados |
| `PracticalInternetofThingsSecurity-PacktPublishing.pdf` | `[INT]` | Segurança em IoT de forma prática; inclui análise de protocolos e hardware |
| `pentesting azure applications.pdf` | `[INT]` | Matt Burrough — pentest em ambientes Azure; bom para cloud red team |
| `rtfm-red-team-field-manual.pdf` | `[REF]` | Red Team Field Manual — referência rápida de comandos ofensivos para campo |
| `DEF CON 23 - Jason-Haddix-How-Do-I-shot-Web.pdf` | `[MET]` | Jason Haddix — metodologia de reconhecimento e ataque web; apresentação que definiu o bug bounty moderno |
| `Webbots, Spiders, and Screen Scrapers.pdf` | `[INT]` | Automação web para coleta de dados — útil para OSINT e reconhecimento passivo |
| `mining-social-media.pdf` | `[INT]` | Técnicas de OSINT em redes sociais para reconhecimento de alvos |
| `websecurityfordevelopers.pdf` | `[INT]` | Segurança web do ponto de vista do desenvolvedor — entender como as defesas funcionam para contorná-las |

### Avançado

| Livro | Nível | Notas |
|-------|-------|-------|
| `The Bug Hunters Methodology 2.pdf` | `[AVA]` | Jason Haddix — metodologia aprofundada para hunters experientes |
| `Bug_Hunters_Methodology_Live_Day_Two_-_App_Analysis_Master.pdf` | `[AVA]` | Continuação da metodologia com análise de aplicações em profundidade |
| `zseanos-methodology.pdf` | `[AVA]` | zseano (BugBountyHunter.com) — abordagem de 1000+ vulnerabilidades em web apps; requer Burp Suite |
| `a bug hunters diary.pdf` | `[AVA]` | Tobias Klein — diário de 7 bugs reais em iOS, VLC, OS X; narrativa completa do discovery ao patch |
| `From Day Zero to Zero Day A Hands-On Guide _compressed.pdf` | `[AVA]` | Eugene Lim — pesquisa de vulnerabilidades com code review, reversão e fuzzing; exige C e Python |
| `Enumerating Esoteric Attack Surfaces by Jann Moon.pdf` | `[AVA]` | Jann Horn (Project Zero) — enumeração de superfícies de ataque não óbvias; leitura de elite |
| `LFI with phpinfo() assistance.pdf` | `[AVA]` | Técnica específica e profunda de exploração de LFI com phpinfo |
| `The Definitive Guide to Attacking the Internet of Things-No Starch Press (2021).pdf` | `[AVA]` | Guia completo e avançado de ataques a IoT — firmware, hardware e protocolos |
| `AbhishekPawarNotes/` | `[MET]` | Notas e metodologias de Abhishek Pawar (hunter reconhecido) — complemento prático avançado |

---

## Blue Team

> Abrange defesa, análise de rede, resposta a incidentes, hardening e desenvolvimento seguro.

### Básico

| Livro | Nível | Notas |
|-------|-------|-------|
| `Blue Team Field Manual.pdf` | `[REF]` | BTFM — referência essencial de comandos e técnicas defensivas; use no dia a dia de SOC/IR |
| `The Art of Invisibility - The World's Most Famous Hacker Teaches You How to Be Safe in the Age of Big Brother and Big Data by Kevin Mitnick.pdf` | `[BAS]` | Mitnick — privacidade, OPSEC pessoal e defesa contra vigilância; acessível ao público geral |
| `how-cybersecurity-really-works.pdf` | `[BAS]` | Visão defensiva de ameaças, ataques e mitigações — também aplicável ao Blue Team |
| `Cyberjutsu.pdf` | `[BAS]` | Ben McCarty (ex-NSA) — estratégia defensiva inspirada em princípios ninja; bom ponto de entrada em mentalidade defensiva |

### Intermediário

| Livro | Nível | Notas |
|-------|-------|-------|
| `practical packet analysis 3rd edition.pdf` | `[INT]` | Chris Sanders — análise de tráfego com Wireshark; habilidade essencial para analistas SOC e IR |
| `websecurityfordevelopers.pdf` | `[INT]` | Desenvolvimento seguro de aplicações web — headers, CSP, autenticação, CSRF |
| `PowerShell_for_Sysadmins.pdf` | `[INT]` | PowerShell para administradores Windows — automação, scripts de IR e hardening |
| `learn-windows-powershell-in-a-month-of-lunches.pdf` | `[INT]` | PowerShell progressivo em formato de lições diárias; ideal para blue teamers no ambiente Windows |

---

## Carreira e Visão Geral

> Livros sobre desenvolvimento de carreira, contexto e narrativas inspiradoras.

| Livro | Nível | Notas |
|-------|-------|-------|
| `How to make more money in Cybersecurity v3.0.pdf` | `[BAS]` | Estratégias de carreira, precificação e posicionamento no mercado de cibersegurança |
| `Mastering Cybersecurity Interviews 1.0.docx-3.pdf` | `[BAS]` | Preparação para entrevistas técnicas e comportamentais em cibersegurança |

---

## Trilhas de Leitura Sugeridas

### Trilha 1 — Bug Bounty Hunter (do Zero)

```
1. [BAS] The Linux Command Line
2. [BAS] Linux Basics for Hackers
3. [BAS] Beyond the Basic Stuff with Python
4. [BAS] Penetration Testing (Georgia Weidman)
5. [BAS] how-cybersecurity-really-works
6. [INT] Real-World Bug Hunting (Peter Yaworski)
7. [INT] bug-bounty-bootcamp
8. [INT] The Web Application Hackers Handbook
9. [INT] Hacking APIs
10. [INT] DEF CON 23 - Jason Haddix (How Do I Shot Web)
11. [AVA] The Bug Hunters Methodology 2
12. [AVA] zseanos-methodology
```

### Trilha 2 — Pentester / Red Teamer

```
1. [BAS] The Linux Command Line
2. [BAS] Linux Basics for Hackers
3. [BAS] Violent Python
4. [BAS] Penetration Testing (Georgia Weidman)
5. [INT] Black Hat Python
6. [INT] Black Hat Bash
7. [INT] The Hacker Playbook 3
8. [REF] rtfm-red-team-field-manual
9. [INT] Attacking Network Protocols
10. [INT] Pentesting Azure Applications
11. [AVA] From Day Zero to Zero Day
```

### Trilha 3 — Blue Teamer / SOC Analyst

```
1. [BAS] The Linux Command Line
2. [BAS] How Linux Works
3. [BAS] how-cybersecurity-really-works
4. [BAS] Cyberjutsu
5. [REF] Blue Team Field Manual
6. [INT] Practical Packet Analysis
7. [INT] PowerShell for Sysadmins
8. [INT] Learn Windows PowerShell in a Month of Lunches
9. [INT] Web Security for Developers
```

### Trilha 4 — Web Security Especialista

```
1. [INT] The Web Application Hackers Handbook
2. [INT] The Tangled Web
3. [INT] JavaScript Security
4. [INT] Hacking APIs
5. [INT] BlackHat GraphQL
6. [INT] Mastering Modern Web Penetration Testing
7. [MET] DEF CON 23 - Jason Haddix
8. [AVA] Bug Hunters Methodology 2
9. [AVA] zseanos-methodology
10. [AVA] Enumerating Esoteric Attack Surfaces
```

### Trilha 5 — IoT & Hardware Security

```
1. [INT] IoT Security 101
2. [INT] Practical Internet of Things Security
3. [AVA] The Definitive Guide to Attacking the Internet of Things
```

---

> **Dica:** Comece pela trilha que mais se alinha com seu objetivo. Os livros de Fundação podem ser lidos em paralelo com qualquer trilha.
