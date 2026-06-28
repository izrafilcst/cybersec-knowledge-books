# Guia de Estudo em Cibersegurança

> **Filosofia:** Construir uma base sólida em defesa antes de atacar. Quem entende como o Blue Team pensa, cria, alerta e investiga tem vantagem real no Red Team — sabe o que não vai aparecer nos logs, o que vai disparar um alerta e onde estão os pontos cegos da defesa.

---

## Estrutura do Repositório

```
.
├── fundacao/      — Linux, scripting, linguagens de programação
├── red-team/      — Pentest, bug bounty, exploração, pesquisa de vulns
├── blue-team/     — Defesa, SOC, IR, análise de tráfego, hardening
├── carreira/      — Carreira, entrevistas, posicionamento
└── guia/          — Roadmap e guia de leitura
```

---

## Roadmap 5 Anos — Blue Team → Red Team (2026–2030)

```
2026 ──► 2027 ──► 2028 ──► 2029 ──► 2030
 Blue      Blue    Bridge   Red       Red
 Fundação  Inter   Blue↔Red  Intermed  Avançado
```

| Ano | Foco | Meta Principal |
|-----|------|----------------|
| 2026 | Blue Team — Fundação | Entender o ambiente, ferramentas e mentalidade defensiva |
| 2027 | Blue Team — Intermediário | Análise de ameaças, resposta a incidentes, scripting |
| 2028 | Transição — Bridge | Web security, pentest básico, visão ofensiva nascente |
| 2029 | Red Team — Intermediário | Pentest prático, bug bounty, ferramentas ofensivas |
| 2030 | Red Team — Avançado | Pesquisa de vulnerabilidades, red team ops, especialização |

---

## Ano 1 — 2026 · Blue Team Fundação

**Objetivo:** Dominar o terminal, entender como sistemas funcionam e internalizar a mentalidade defensiva.

### Leituras do Ano

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | [The Linux Command Line](fundacao/The-Linux-Command-Line.pdf) | `[BAS]` | Pré-requisito absoluto — sem isso nada funciona |
| 2 | [How Linux Works](fundacao/How-Linux-Works.pdf) | `[BAS]` | Entender processos, memória e I/O é base para análise forense e IR |
| 3 | [How Cybersecurity Really Works](blue-team/how-cybersecurity-really-works.pdf) | `[BAS]` | Visão sistêmica de ameaças — leitura dupla: defensiva agora, ofensiva depois |
| 4 | [Cyberjutsu](blue-team/Cyberjutsu.pdf) | `[BAS]` | Mentalidade defensiva estratégica — ex-NSA; forma o raciocínio de SOC |
| 5 | [Blue Team Field Manual](blue-team/Blue%20Team%20Field%20Manual.pdf) | `[REF]` | Referência de mesa — usar no dia a dia desde já |
| 6 | [The Art of Invisibility (Mitnick)](blue-team/The%20Art%20of%20Invisibility%20-%20The%20World%27s%20Most%20Famous%20Hacker%20Teaches%20You%20How%20to%20Be%20Safe%20in%20the%20Age%20of%20Big%20Brother%20and%20Big%20Data%20by%20Kevin%20Mitnick.pdf) | `[BAS]` | OPSEC e privacidade; entender o que o atacante esconde te ajuda a procurar |

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **CompTIA Security+** | CompTIA | Mid-2026 | ~$370 USD |
| **CompTIA Linux+** *(opcional)* | CompTIA | End-2026 | ~$338 USD |

### Labs & Prática

- TryHackMe — trilha **Pre-Security** e **SOC Level 1**
- Blue Team Labs Online (BTLO) — desafios de análise de logs e PCAP
- Configurar um SIEM caseiro: Elastic Stack (ELK) ou Splunk Free Tier

---

## Ano 2 — 2027 · Blue Team Intermediário

**Objetivo:** Trabalhar análise de tráfego, automação e resposta a incidentes. Começar a entender scripting defensivo.

### Leituras do Ano

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | [Practical Packet Analysis 3rd Edition](blue-team/practical%20packet%20analysis%203rd%20edition.pdf) | `[INT]` | Wireshark é ferramenta essencial — tanto para SOC quanto para entender o que red teamers trafegam |
| 2 | [PowerShell for Sysadmins](blue-team/PowerShell_for_Sysadmins.pdf) | `[INT]` | Automação de hardening e resposta a incidentes em ambientes Windows |
| 3 | [Learn Windows PowerShell in a Month of Lunches](blue-team/learn-windows-powershell-in-a-month-of-lunches.pdf) | `[INT]` | Reforça PowerShell — progressivo, ideal para leitura paralela |
| 4 | [Linux Basics for Hackers](fundacao/linux-basics-for-hackers.pdf) | `[BAS]` | Releitura com olhar diferente — agora você vê as ferramentas que o atacante usa |
| 5 | [Wicked Cool Shell Scripts](fundacao/Wicked%20Cool%20Shell%20Scripts.pdf) | `[INT]` | Automação com Bash — scripts de monitoramento, coleta de artefatos |
| 6 | [Beyond the Basic Stuff with Python](fundacao/Beyond-the-Basic-Stuff-with-Python.pdf) | `[BAS]` | Python para automação defensiva e parsing de logs |

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **CompTIA CySA+** | CompTIA | Mid-2027 | ~$370 USD |
| **SC-200** (Microsoft Security Operations Analyst) | Microsoft | End-2027 | ~$165 USD |

### Labs & Prática

- TryHackMe — trilha **SOC Level 2**
- BTLO — desafios avançados de malware analysis e threat hunting
- Montar home lab: pfSense + Zeek + Suricata + ELK
- Participar de CTFs na categoria **forensics** e **misc**

---

## Ano 3 — 2028 · Bridge — Blue Meets Red

**Objetivo:** Entender como o atacante pensa usando o que você já sabe sobre defesa. Primeiro contato sólido com pentest e web hacking.

### Leituras do Ano

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | [Web Security for Developers](red-team/websecurityfordevelopers.pdf) | `[INT]` | Leitura dupla: você já sabe defender — agora entende o que os devs erram |
| 2 | [The Web Application Hackers Handbook](red-team/The%20Web%20Application%20Hackers%20Handbook%202nd%20Edition.pdf) | `[INT]` | A bíblia do web hacking — leitura de referência, não precisa ler linear |
| 3 | [Penetration Testing (Georgia Weidman)](red-team/Penetration%20Testing%20-%20A%20hands-on%20introduction%20to%20Hacking.pdf) | `[BAS]` | O livro introdutório de pentest mais recomendado |
| 4 | [Violent Python](red-team/Violent%20Python.pdf) | `[BAS]` | Scripts ofensivos em Python; port scanners, sniffers — você já sabe o que eles geram de log |
| 5 | [Attacking Network Protocols](red-team/attacking%20network%20protocols.pdf) | `[INT]` | James Forshaw — análise de protocolos com olhar ofensivo; sua base de Wireshark ajuda muito aqui |
| 6 | [Real-World Bug Hunting](red-team/Real-World%20Bug%20Hunting%20-%20A%20Field%20Guide%20to%20Web%20Hacking.pdf) | `[INT]` | Peter Yaworski — primeiro contato com bug bounty real; acessível e motivador |

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **eJPT** (eLearnSecurity Junior Penetration Tester) | INE Security | Early-2028 | ~$200 USD |
| **CompTIA PenTest+** | CompTIA | End-2028 | ~$370 USD |

### Labs & Prática

- HackTheBox — máquinas **Easy** na categoria Starting Point
- TryHackMe — trilha **Jr Penetration Tester**
- PortSwigger Web Security Academy — labs gratuitos, todos os módulos básicos
- Instalar e aprender Burp Suite Community Edition

---

## Ano 4 — 2029 · Red Team Intermediário

**Objetivo:** Pentest prático, bug bounty ativo, ferramentas ofensivas e foco em web/API hacking.

### Leituras do Ano

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | [Black Hat Python, 2nd Edition](red-team/Black%20Hat%20Python%2C%202nd%20Edition.pdf) | `[INT]` | Python ofensivo — trojans, sniffers, exploits; você já entende a contrapartida defensiva |
| 2 | [Black Hat Bash](red-team/Black-Hat-Bash.pdf) | `[INT]` | Automação de recon, exploração e pós-exploração em Bash |
| 3 | [Bug Bounty Bootcamp](red-team/bug-bounty-bootcamp.pdf) | `[INT]` | Vivian Weisman — trilha completa: XSS, SSRF, SQLi, IDOR, recon |
| 4 | [Hacking APIs](red-team/Hacking%20APIs%20-%20Early%20Access.pdf) | `[INT]` | Testes em APIs REST/SOAP — autenticação, fuzzing, lógica; muito demandado em bounty |
| 5 | [BlackHat GraphQL](red-team/BlackHat%20GraphQL.pdf) | `[INT]` | Ataques a GraphQL — superfície de ataque crescente e pouco coberta |
| 6 | [The Hacker Playbook 3](red-team/The%20Hacker%20Playbook%203%20-%20Practical%20Guide%20To%20Penetration%20Testing.pdf) | `[INT]` | Active Directory, evasão, movimento lateral; metodologia real de red team |
| 7 | [Black Hat Go](red-team/Black-Hat-Go.pdf) | `[INT]` | Go para ferramentas ofensivas — C2, proxies, scanners modernos |
| 8 | [RTFM — Red Team Field Manual](red-team/rtfm-red-team-field-manual.pdf) | `[REF]` | Referência de campo para operações ofensivas |

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **OSCP** (OffSec Certified Professional) | Offensive Security | Mid-2029 | ~$1.499 USD (90 dias lab) |
| **BSCP** (Burp Suite Certified Practitioner) | PortSwigger | End-2029 | ~$99 USD |

### Labs & Prática

- HackTheBox — máquinas **Medium/Hard**, trilha **Pro Labs (Offshore ou RastaLabs)**
- PortSwigger Web Security Academy — todos os labs avançados (SSRF, XXE, OAuth, SSTI)
- Participar ativamente de bug bounty: **HackerOne** e **Bugcrowd**
- Praticar relatórios de vulnerabilidade — escrita técnica é diferencial em bounty e pentest

---

## Ano 5 — 2030 · Red Team Avançado

**Objetivo:** Pesquisa de vulnerabilidades, red team operations, especialização em uma vertical (web, AD, IoT, cloud ou vuln research).

### Leituras do Ano

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | [The Bug Hunters Methodology 2](red-team/The%20Bug%20Hunters%20Methodology%202.pdf) | `[AVA]` | Jason Haddix — metodologia profunda para hunters experientes |
| 2 | [Bug Hunters Methodology Live Day Two](red-team/Bug_Hunters_Methodology_Live_Day_Two_-_App_Analysis_Master.pdf) | `[AVA]` | Continuação — análise de aplicações em profundidade |
| 3 | [zseano's Methodology](red-team/zseanos-methodology.pdf) | `[AVA]` | Abordagem de 1000+ vulns em web apps; exige domínio de Burp Suite |
| 4 | [From Day Zero to Zero Day](red-team/From%20Day%20Zero%20to%20Zero%20Day%20A%20Hands-On%20Guide%20_compressed.pdf) | `[AVA]` | Eugene Lim — vuln research com code review, reversão e fuzzing; exige C e Python |
| 5 | [Enumerating Esoteric Attack Surfaces](red-team/Enumerating%20Esoteric%20Attack%20Surfaces%20by%20Jann%20Moon.pdf) | `[AVA]` | Jann Horn (Project Zero) — enumeração de superfícies não óbvias; leitura de elite |
| 6 | [A Bug Hunter's Diary](red-team/a%20bug%20hunters%20diary.pdf) | `[AVA]` | Tobias Klein — 7 bugs reais narrados do discovery ao patch; referência de processo |

### Vertical Avançada — Escolha uma

**Web / Bug Bounty**
- Continuar `zseanos-methodology` + praticar HackerOne live programs
- Meta: **H1-702 / H1-415** (conferências exclusivas HackerOne)

**Active Directory / Red Team Ops**
- `The Hacker Playbook 3` (revisar) + Covenant/Havoc C2 study
- Cert: **CRTO** (Certified Red Team Operator) — Zero Point Security

**Cloud Red Team**
- [Pentesting Azure Applications](red-team/pentesting%20azure%20applications.pdf) + AWS/GCP equivalentes
- Cert: **CARTP** (Certified Azure Red Team Professional) — Altered Security

**IoT & Hardware**
- [The Definitive Guide to Attacking the IoT](red-team/The%20Definitive%20Guide%20to%20Attacking%20the%20Internet%20of%20Things-No%20Starch%20Press%20%282021%29.pdf)
- [IoT Security 101](red-team/IoT_Security_101__Deep_Dive_Into_Attack_Surface.pdf) (revisão avançada)

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **CRTO** (Certified Red Team Operator) | Zero Point Security | Mid-2030 | ~$600 USD |
| **OSEP** (OffSec Experienced Pentester) | Offensive Security | End-2030 | ~$1.499 USD |
| *(alternativa)* **eCPPTv2** | INE Security | Mid-2030 | ~$400 USD |

### Labs & Prática

- HackTheBox Pro Labs: **Offshore** e **Dante**
- Montar lab de AD em casa: Windows Server + domínio + GPOs + Bloodhound
- Contribuir com ferramentas open-source de segurança ofensiva
- Publicar write-ups de CTF e vulns descobertas em bug bounty

---

## Tabela Resumo — Certificações

| Ano | Cert | Nível | Área |
|-----|------|-------|------|
| 2026 | CompTIA Security+ | Fundação | Blue |
| 2026 | CompTIA Linux+ *(opcional)* | Fundação | Blue |
| 2027 | CompTIA CySA+ | Intermediário | Blue |
| 2027 | SC-200 (Microsoft) | Intermediário | Blue |
| 2028 | eJPT | Básico | Red |
| 2028 | CompTIA PenTest+ | Básico | Red |
| 2029 | OSCP | Intermediário | Red |
| 2029 | BSCP | Intermediário | Red/Web |
| 2030 | CRTO ou OSEP | Avançado | Red |

---

## Por Que Blue Primeiro?

| Vantagem | Como se aplica em Red Team |
|----------|---------------------------|
| Você sabe o que gera alerta | Evita IoCs óbvios — movimento mais silencioso |
| Você conhece ferramentas de defesa | Sabe o que o Splunk, Defender e Zeek enxergam |
| Você analisou logs | Sabe apagar rastros e manipular eventos |
| Você estudou malware | Entende técnicas de persistência e evasão |
| Você fez threat hunting | Pensa como o defensor que vai te caçar |
| Você configurou SIEMs | Sabe onde ficam os pontos cegos da cobertura |

---

## Acervo Completo — Organizado por Categoria

> Legenda: `[BAS]` Básico · `[INT]` Intermediário · `[AVA]` Avançado · `[REF]` Referência · `[MET]` Metodologia

---

### `fundacao/` — Ferramentas e Programação

#### Básico

| Livro | Nível | Notas |
|-------|-------|-------|
| [The Linux Command Line](fundacao/The-Linux-Command-Line.pdf) | `[BAS]` | Domínio do terminal Linux — base para qualquer trilha |
| [How Linux Works](fundacao/How-Linux-Works.pdf) | `[BAS]` | Como o Linux funciona internamente — processos, memória, I/O |
| [Linux Basics for Hackers](fundacao/linux-basics-for-hackers.pdf) | `[BAS]` | Linux voltado para segurança ofensiva; ótimo primeiro livro da trilha hacker |
| [Bash Cheat Sheet](fundacao/bash_cheat_sheet.pdf) | `[REF]` | Referência rápida de Bash |
| [Beyond the Basic Stuff with Python](fundacao/Beyond-the-Basic-Stuff-with-Python.pdf) | `[BAS]` | Aprofundamento em Python além do básico; inclui automação e projetos |
| [Make Python Talk](fundacao/make-python-talk.pdf) | `[BAS]` | Python prático com projetos de síntese de voz e automação |
| [Ruby by Example](fundacao/Ruby%20by%20Example.pdf) | `[BAS]` | Introdução à linguagem Ruby por exemplos práticos |
| [The Book of Ruby](fundacao/the-book-of-ruby.pdf) | `[BAS]` | Ruby completo do zero; bom para entender a linguagem antes de usar scripts ofensivos |
| [Build an HTML5 Game](fundacao/Build%20an%20HTML5%20Game.pdf) | `[BAS]` | Fundamentos de HTML5/JavaScript; útil para compreender superfícies web |

#### Intermediário

| Livro | Nível | Notas |
|-------|-------|-------|
| [Wicked Cool Shell Scripts](fundacao/Wicked%20Cool%20Shell%20Scripts.pdf) | `[INT]` | Scripts de shell para automação — base para Black Hat Bash |
| [Wicked Cool Ruby Scripts](fundacao/wicked-cool-ruby-scripts.pdf) | `[INT]` | Automação com Ruby; útil para criar ferramentas customizadas |
| [Wicked Cool Perl Scripts](fundacao/Wicked%20Cool%20Perl%20Scripts.pdf) | `[INT]` | Perl para automação de segurança e scraping |
| [Perl One-Liners](fundacao/perl-one-liners.pdf) | `[REF]` | Referência de Perl one-liners; excelente para processamento de texto em CTF |
| [The Rust Programming Language](fundacao/No-Starch-Press-The-Rust.pdf) | `[INT]` | A linguagem Rust — segurança de memória; crescente na área de ferramentas de segurança |

---

### `red-team/` — Red Team

#### Básico

| Livro | Nível | Notas |
|-------|-------|-------|
| [Penetration Testing (Georgia Weidman)](red-team/Penetration%20Testing%20-%20A%20hands-on%20introduction%20to%20Hacking.pdf) | `[BAS]` | O livro introdutório de pentest mais recomendado; cobre o ciclo completo |
| [Violent Python](red-team/Violent%20Python.pdf) | `[BAS]` | Scripts ofensivos em Python; projetos de port scanner, sniffer e mais |
| [The Art of Deception (Mitnick)](red-team/The_Art_of_Deception_by_Kelvin_Mitnick.pdf) | `[BAS]` | Engenharia social por Kevin Mitnick — essencial para compreender o fator humano |
| [The Art of Intrusion (Mitnick)](red-team/Kevin_Mitnick_-_The_Art_of_Intrusion.pdf) | `[BAS]` | Casos reais de intrusão narrados por Mitnick — leitura acessível e motivadora |

#### Intermediário

| Livro | Nível | Notas |
|-------|-------|-------|
| [Black Hat Python, 2nd Edition](red-team/Black%20Hat%20Python%2C%202nd%20Edition.pdf) | `[INT]` | Python para ofensiva — ferramentas de rede, trojans, exploits; referência clássica |
| [Black Hat Bash](red-team/Black-Hat-Bash.pdf) | `[INT]` | Bash para Red Team — automação de reconhecimento, exploração e pós-exploração |
| [Black Hat Go](red-team/Black-Hat-Go.pdf) | `[INT]` | Go para criação de ferramentas ofensivas modernas — C2, proxies, scanners |
| [The Hacker Playbook 3](red-team/The%20Hacker%20Playbook%203%20-%20Practical%20Guide%20To%20Penetration%20Testing.pdf) | `[INT]` | Metodologia prática de pentest; cobre Active Directory, evasão e movimento lateral |
| [Real-World Bug Hunting](red-team/Real-World%20Bug%20Hunting%20-%20A%20Field%20Guide%20to%20Web%20Hacking.pdf) | `[INT]` | Peter Yaworski — guia prático de bug bounty com casos reais |
| [Bug Bounty Bootcamp](red-team/bug-bounty-bootcamp.pdf) | `[INT]` | Vivian Weisman — trilha completa: recon, XSS, SSRF, SQLi e mais |
| [The Web Application Hackers Handbook](red-team/The%20Web%20Application%20Hackers%20Handbook%202nd%20Edition.pdf) | `[INT]` | Referência abrangente de web hacking; cobre quase todas as classes de vulnerabilidades web |
| [Hacking APIs](red-team/Hacking%20APIs%20-%20Early%20Access.pdf) | `[INT]` | Testes de segurança em APIs REST/SOAP; cobre autenticação, fuzzing e abusos de lógica |
| [BlackHat GraphQL](red-team/BlackHat%20GraphQL.pdf) | `[INT]` | Ataque a APIs GraphQL; inclui técnicas inéditas e laboratório prático |
| [Mastering Modern Web Penetration Testing](red-team/Mastering%20Modern%20Web%20Penetration%20Testing.pdf) | `[INT]` | Web pentesting com OAuth, CORS, SSRF, IDOR; bom complemento intermediário |
| [The Tangled Web](red-team/The%20tangled%20Web_%20a%20guide%20to%20securing%20modern%20Web%20applications.pdf) | `[INT]` | Michal Zalewski — compreensão profunda da arquitetura web e suas armadilhas de segurança |
| [JavaScript Security](red-team/JavaScript%20Security.pdf) | `[INT]` | Vulnerabilidades específicas de JavaScript no browser e Node.js |
| [Attacking Network Protocols](red-team/attacking%20network%20protocols.pdf) | `[INT]` | James Forshaw — análise e exploração de protocolos de rede |
| [Android Hacker's Handbook](red-team/Android%20Hacker%27s%20Handbook.pdf) | `[INT]` | Exploração de vulnerabilidades na plataforma Android |
| [IoT Security 101](red-team/IoT_Security_101__Deep_Dive_Into_Attack_Surface.pdf) | `[INT]` | Superfícies de ataque em dispositivos IoT — firmware, protocolos embarcados |
| [Practical Internet of Things Security](red-team/PracticalInternetofThingsSecurity-PacktPublishing.pdf) | `[INT]` | Segurança em IoT de forma prática; inclui análise de protocolos e hardware |
| [Pentesting Azure Applications](red-team/pentesting%20azure%20applications.pdf) | `[INT]` | Matt Burrough — pentest em ambientes Azure; bom para cloud red team |
| [RTFM — Red Team Field Manual](red-team/rtfm-red-team-field-manual.pdf) | `[REF]` | Referência rápida de comandos ofensivos para campo |
| [DEF CON 23 — Jason Haddix](red-team/DEF%20CON%2023%20-%20Jason-Haddix-How-Do-I-shot-Web.pdf) | `[MET]` | Metodologia de reconhecimento e ataque web; apresentação que definiu o bug bounty moderno |
| [Webbots, Spiders, and Screen Scrapers](red-team/Webbots%2C%20Spiders%2C%20and%20Screen%20Scrapers.pdf) | `[INT]` | Automação web para coleta de dados — útil para OSINT e reconhecimento passivo |
| [Mining Social Media](red-team/mining-social-media.pdf) | `[INT]` | Técnicas de OSINT em redes sociais para reconhecimento de alvos |
| [Web Security for Developers](red-team/websecurityfordevelopers.pdf) | `[INT]` | Segurança web do ponto de vista do desenvolvedor — entender como as defesas funcionam para contorná-las |

#### Avançado

| Livro | Nível | Notas |
|-------|-------|-------|
| [The Bug Hunters Methodology 2](red-team/The%20Bug%20Hunters%20Methodology%202.pdf) | `[AVA]` | Jason Haddix — metodologia aprofundada para hunters experientes |
| [Bug Hunters Methodology Live Day Two](red-team/Bug_Hunters_Methodology_Live_Day_Two_-_App_Analysis_Master.pdf) | `[AVA]` | Continuação da metodologia com análise de aplicações em profundidade |
| [zseano's Methodology](red-team/zseanos-methodology.pdf) | `[AVA]` | zseano — abordagem de 1000+ vulnerabilidades em web apps; requer Burp Suite |
| [A Bug Hunter's Diary](red-team/a%20bug%20hunters%20diary.pdf) | `[AVA]` | Tobias Klein — diário de 7 bugs reais em iOS, VLC, OS X; narrativa completa do discovery ao patch |
| [From Day Zero to Zero Day](red-team/From%20Day%20Zero%20to%20Zero%20Day%20A%20Hands-On%20Guide%20_compressed.pdf) | `[AVA]` | Eugene Lim — pesquisa de vulnerabilidades com code review, reversão e fuzzing; exige C e Python |
| [Enumerating Esoteric Attack Surfaces](red-team/Enumerating%20Esoteric%20Attack%20Surfaces%20by%20Jann%20Moon.pdf) | `[AVA]` | Jann Horn (Project Zero) — enumeração de superfícies de ataque não óbvias; leitura de elite |
| [LFI with phpinfo() Assistance](red-team/LFI%20with%20phpinfo%28%29%20assistance.pdf) | `[AVA]` | Técnica específica e profunda de exploração de LFI com phpinfo |
| [The Definitive Guide to Attacking the IoT](red-team/The%20Definitive%20Guide%20to%20Attacking%20the%20Internet%20of%20Things-No%20Starch%20Press%20%282021%29.pdf) | `[AVA]` | Guia completo e avançado de ataques a IoT — firmware, hardware e protocolos |

---

### `blue-team/` — Blue Team

#### Básico

| Livro | Nível | Notas |
|-------|-------|-------|
| [Blue Team Field Manual](blue-team/Blue%20Team%20Field%20Manual.pdf) | `[REF]` | BTFM — referência essencial de comandos e técnicas defensivas; use no dia a dia de SOC/IR |
| [The Art of Invisibility (Mitnick)](blue-team/The%20Art%20of%20Invisibility%20-%20The%20World%27s%20Most%20Famous%20Hacker%20Teaches%20You%20How%20to%20Be%20Safe%20in%20the%20Age%20of%20Big%20Brother%20and%20Big%20Data%20by%20Kevin%20Mitnick.pdf) | `[BAS]` | Mitnick — privacidade, OPSEC pessoal e defesa contra vigilância |
| [How Cybersecurity Really Works](blue-team/how-cybersecurity-really-works.pdf) | `[BAS]` | Visão defensiva de ameaças, ataques e mitigações |
| [Cyberjutsu](blue-team/Cyberjutsu.pdf) | `[BAS]` | Ben McCarty (ex-NSA) — estratégia defensiva; bom ponto de entrada em mentalidade defensiva |

#### Intermediário

| Livro | Nível | Notas |
|-------|-------|-------|
| [Practical Packet Analysis 3rd Edition](blue-team/practical%20packet%20analysis%203rd%20edition.pdf) | `[INT]` | Chris Sanders — análise de tráfego com Wireshark; habilidade essencial para analistas SOC e IR |
| [Web Security for Developers](red-team/websecurityfordevelopers.pdf) | `[INT]` | Desenvolvimento seguro de aplicações web — headers, CSP, autenticação, CSRF *(em `red-team/`)* |
| [PowerShell for Sysadmins](blue-team/PowerShell_for_Sysadmins.pdf) | `[INT]` | PowerShell para administradores Windows — automação, scripts de IR e hardening |
| [Learn Windows PowerShell in a Month of Lunches](blue-team/learn-windows-powershell-in-a-month-of-lunches.pdf) | `[INT]` | PowerShell progressivo em formato de lições diárias; ideal para blue teamers no ambiente Windows |

---

### `carreira/` — Carreira e Visão Geral

| Livro | Nível | Notas |
|-------|-------|-------|
| [How to Make More Money in Cybersecurity](carreira/How%20to%20make%20more%20money%20in%20Cybersecurity%20v3.0.pdf) | `[BAS]` | Estratégias de carreira, precificação e posicionamento no mercado |
| [Mastering Cybersecurity Interviews](carreira/Mastering%20Cybersecurity%20Interviews%201.0.docx-3.pdf) | `[BAS]` | Preparação para entrevistas técnicas e comportamentais em cibersegurança |

---

## Trilhas de Leitura Sugeridas

### Trilha 1 — Bug Bounty Hunter (do Zero)

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
11. [AVA] red-team/  The Bug Hunters Methodology 2
12. [AVA] red-team/  zseano's Methodology
```

### Trilha 2 — Pentester / Red Teamer

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
11. [AVA] red-team/  From Day Zero to Zero Day
```

### Trilha 3 — Blue Teamer / SOC Analyst

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

### Trilha 4 — Web Security Especialista

```
1.  [INT] red-team/  The Web Application Hackers Handbook
2.  [INT] red-team/  The Tangled Web
3.  [INT] red-team/  JavaScript Security
4.  [INT] red-team/  Hacking APIs
5.  [INT] red-team/  BlackHat GraphQL
6.  [INT] red-team/  Mastering Modern Web Penetration Testing
7.  [MET] red-team/  DEF CON 23 - Jason Haddix
8.  [AVA] red-team/  The Bug Hunters Methodology 2
9.  [AVA] red-team/  zseano's Methodology
10. [AVA] red-team/  Enumerating Esoteric Attack Surfaces
```

### Trilha 5 — IoT & Hardware Security

```
1.  [INT] red-team/  IoT Security 101
2.  [INT] red-team/  Practical Internet of Things Security
3.  [AVA] red-team/  The Definitive Guide to Attacking the IoT
```

---

## Plataformas de Prática

| Plataforma | Uso | Custo |
|------------|-----|-------|
| TryHackMe | Trilhas guiadas Blue e Red | Free / ~$14/mês |
| HackTheBox | CTF + Pro Labs | Free / ~$14/mês |
| Blue Team Labs Online | Forensics e IR | Free / Pro |
| PortSwigger Web Academy | Web hacking labs | Gratuito |
| HackerOne / Bugcrowd | Bug bounty real | Gratuito |
| INE / eLearnSecurity | Cursos + certs | ~$750/ano |
| Offensive Security (OffSec) | OSCP/OSEP/labs | Por exame |

---

> **Lembre:** Certificações provam que você estudou — o portfólio prova que você sabe. Equilibre os dois. Um write-up bem escrito de uma máquina HTB ou um relatório de bug bounty real vale mais em entrevista do que qualquer cert isolada.
