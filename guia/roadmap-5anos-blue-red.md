# Roadmap 5 Anos — Blue Team → Red Team (2026–2030)

> **Filosofia:** Construir uma base sólida em defesa antes de atacar. Quem entende como o Blue Team pensa, cria, alerta e investiga tem vantagem real no Red Team — sabe o que não vai aparecer nos logs, o que vai disparar um alerta e onde estão os pontos cegos da defesa.

---

## Visão Geral

```
2026 ──► 2027 ──► 2028 ──► 2029 ──► 2030
 Blue      Blue    Bridge   Red       Red
 Foundation Inter   Blue↔Red  Intermed  Advanced
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

### Leituras

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | `The-Linux-Command-Line.pdf` | `[BAS]` | Pré-requisito absoluto — sem isso nada funciona |
| 2 | `How-Linux-Works.pdf` | `[BAS]` | Entender processos, memória e I/O é base para análise forense e IR |
| 3 | `how-cybersecurity-really-works.pdf` | `[BAS]` | Visão sistêmica de ameaças — leitura dupla: defensiva agora, ofensiva depois |
| 4 | `Cyberjutsu.pdf` | `[BAS]` | Mentalidade defensiva estratégica — ex-NSA; forma o raciocínio de SOC |
| 5 | `Blue Team Field Manual.pdf` | `[REF]` | Referência de mesa — usar no dia a dia desde já |
| 6 | `The Art of Invisibility (Mitnick).pdf` | `[BAS]` | OPSEC e privacidade; entender o que o atacante esconde te ajuda a procurar |

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **CompTIA Security+** | CompTIA | Mid-2026 | ~$370 USD |
| **CompTIA Linux+** *(opcional)* | CompTIA | End-2026 | ~$338 USD |

> **Nota:** Security+ é a cert de entrada mais reconhecida globalmente para Blue Team. Abre portas em SOC Tier 1 e posições de analista júnior.

### Labs & Prática

- TryHackMe — trilha **Pre-Security** e **SOC Level 1**
- Blue Team Labs Online (BTLO) — desafios de análise de logs e PCAP
- Configurar um SIEM caseiro: Elastic Stack (ELK) ou Splunk Free Tier

---

## Ano 2 — 2027 · Blue Team Intermediário

**Objetivo:** Trabalhar análise de tráfego, automação e resposta a incidentes. Começar a entender scripting defensivo.

### Leituras

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | `practical packet analysis 3rd edition.pdf` | `[INT]` | Wireshark é ferramenta essencial — tanto para SOC quanto para entender o que red teamers trafegam |
| 2 | `PowerShell_for_Sysadmins.pdf` | `[INT]` | Automação de hardening e resposta a incidentes em ambientes Windows |
| 3 | `learn-windows-powershell-in-a-month-of-lunches.pdf` | `[INT]` | Reforça PowerShell — progressivo, ideal para leitura paralela |
| 4 | `linux-basics-for-hackers.pdf` | `[BAS]` | Releitura com olhar diferente — agora você vê as ferramentas que o atacante usa |
| 5 | `Wicked Cool Shell Scripts.pdf` | `[INT]` | Automação com Bash — scripts de monitoramento, coleta de artefatos |
| 6 | `Beyond-the-Basic-Stuff-with-Python.pdf` | `[BAS]` | Python para automação defensiva e parsing de logs |

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **CompTIA CySA+** | CompTIA | Mid-2027 | ~$370 USD |
| **SC-200** (Microsoft Security Operations Analyst) | Microsoft | End-2027 | ~$165 USD |

> **Nota:** CySA+ é a evolução natural do Security+ para analistas de SOC. SC-200 é diferencial enorme para ambientes corporativos Azure/M365.

### Labs & Prática

- TryHackMe — trilha **SOC Level 2**
- BTLO — desafios avançados de malware analysis e threat hunting
- Montar home lab: pfSense + Zeek + Suricata + ELK
- Participar de CTFs na categoria **forensics** e **misc**

---

## Ano 3 — 2028 · Bridge — Blue Meets Red

**Objetivo:** Entender como o atacante pensa usando o que você já sabe sobre defesa. Primeiro contato sólido com pentest e web hacking.

### Leituras

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | `websecurityfordevelopers.pdf` | `[INT]` | Leitura dupla: você já sabe defender — agora entende o que os devs erram |
| 2 | `The Web Application Hackers Handbook 2nd Edition.pdf` | `[INT]` | A bíblia do web hacking — leitura de referência, não precisa ler linear |
| 3 | `Penetration Testing - A hands-on introduction to Hacking.pdf` | `[BAS]` | Georgia Weidman — o livro introdutório de pentest mais recomendado |
| 4 | `Violent Python.pdf` | `[BAS]` | Scripts ofensivos em Python; port scanners, sniffers — você já sabe o que eles geram de log |
| 5 | `attacking network protocols.pdf` | `[INT]` | James Forshaw — análise de protocolos com olhar ofensivo; sua base de Wireshark ajuda muito aqui |
| 6 | `Real-World Bug Hunting.pdf` | `[INT]` | Peter Yaworski — primeiro contato com bug bounty real; acessível e motivador |

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **eJPT** (eLearnSecurity Junior Penetration Tester) | INE Security | Early-2028 | ~$200 USD |
| **CompTIA PenTest+** | CompTIA | End-2028 | ~$370 USD |

> **Nota:** eJPT é o melhor primeiro passo em pentest — prático, acessível e reconhecido. PenTest+ complementa com metodologia e relatório, útil para transição de carreira.

### Labs & Prática

- HackTheBox — máquinas **Easy** na categoria Starting Point
- TryHackMe — trilha **Jr Penetration Tester**
- PortSwigger Web Security Academy — labs gratuitos, todos os módulos básicos
- Instalar e aprender Burp Suite Community Edition

---

## Ano 4 — 2029 · Red Team Intermediário

**Objetivo:** Pentest prático, bug bounty ativo, ferramentas ofensivas e foco em web/API hacking.

### Leituras

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | `Black Hat Python, 2nd Edition.pdf` | `[INT]` | Python ofensivo — trojans, sniffers, exploits; você já entende a contrapartida defensiva |
| 2 | `Black-Hat-Bash.pdf` | `[INT]` | Automação de recon, exploração e pós-exploração em Bash |
| 3 | `bug-bounty-bootcamp.pdf` | `[INT]` | Vivian Weisman — trilha completa: XSS, SSRF, SQLi, IDOR, recon |
| 4 | `Hacking APIs - Early Access.pdf` | `[INT]` | Testes em APIs REST/SOAP — autenticação, fuzzing, lógica; muito demandado em bounty |
| 5 | `BlackHat GraphQL.pdf` | `[INT]` | Ataques a GraphQL — superfície de ataque crescente e pouco coberta |
| 6 | `The Hacker Playbook 3.pdf` | `[INT]` | THP3 — Active Directory, evasão, movimento lateral; metodologia real de red team |
| 7 | `Black-Hat-Go.pdf` | `[INT]` | Go para ferramentas ofensivas — C2, proxies, scanners modernos |
| 8 | `rtfm-red-team-field-manual.pdf` | `[REF]` | RTFM — referência de campo para operações ofensivas |

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **OSCP** (OffSec Certified Professional) | Offensive Security | Mid-2029 | ~$1.499 USD (90 dias lab) |
| **BSCP** (Burp Suite Certified Practitioner) | PortSwigger | End-2029 | ~$99 USD |

> **Nota:** OSCP é o marco da carreira em pentest — exige disciplina, mas com 3 anos de base você chega preparado. BSCP valida web hacking com uma das melhores ferramentas da área.

### Labs & Prática

- HackTheBox — máquinas **Medium/Hard**, trilha **Pro Labs (Offshore ou RastaLabs)**
- PortSwigger Web Security Academy — todos os labs avançados (SSRF, XXE, OAuth, SSTI)
- Participar ativamente de bug bounty em plataformas: **HackerOne** e **Bugcrowd**
- Praticar relatórios de vulnerabilidade — escrita técnica é diferencial em bounty e pentest

---

## Ano 5 — 2030 · Red Team Avançado

**Objetivo:** Pesquisa de vulnerabilidades, red team operations, especialização em uma vertical (web, AD, IoT, cloud ou vuln research).

### Leituras

| Ordem | Livro | Nível | Por quê agora |
|-------|-------|-------|----------------|
| 1 | `The Bug Hunters Methodology 2.pdf` | `[AVA]` | Jason Haddix — metodologia profunda para hunters experientes |
| 2 | `Bug_Hunters_Methodology_Live_Day_Two.pdf` | `[AVA]` | Continuação — análise de aplicações em profundidade |
| 3 | `zseanos-methodology.pdf` | `[AVA]` | zseano — abordagem de 1000+ vulns em web apps; exige domínio de Burp Suite |
| 4 | `From Day Zero to Zero Day.pdf` | `[AVA]` | Eugene Lim — vuln research com code review, reversão e fuzzing; exige C e Python |
| 5 | `Enumerating Esoteric Attack Surfaces - Jann Horn.pdf` | `[AVA]` | Project Zero — enumeração de superfícies não óbvias; leitura de elite |
| 6 | `a bug hunters diary.pdf` | `[AVA]` | Tobias Klein — 7 bugs reais narrados do discovery ao patch; referência de processo |
| 7 | `AbhishekPawarNotes/` | `[MET]` | Notas de hunter reconhecido — complemento prático de metodologia |

### Escolha sua vertical avançada

> Após 4 anos, você já sabe onde quer se aprofundar. Escolha uma:

**Web / Bug Bounty**
- Continuar `zseanos-methodology` + praticar HackerOne live programs
- Meta: **H1-702 / H1-415** (conferências exclusivas HackerOne)

**Active Directory / Red Team Ops**
- `The Hacker Playbook 3` (revisar) + Covenant/Havoc C2 study
- Cert: **CRTO** (Certified Red Team Operator) — Sektor7/ZeroPointSecurity

**Cloud Red Team**
- `pentesting azure applications.pdf` + AWS/GCP equivalentes
- Cert: **CARTP** (Certified Azure Red Team Professional) — Altered Security

**IoT & Hardware**
- `The Definitive Guide to Attacking the Internet of Things.pdf`
- `IoT_Security_101.pdf` (revisão avançada)

### Certificações

| Cert | Emissor | Quando | Custo aprox. |
|------|---------|--------|--------------|
| **CRTO** (Certified Red Team Operator) | Zero Point Security | Mid-2030 | ~$600 USD |
| **OSEP** (OffSec Experienced Pentester) | Offensive Security | End-2030 | ~$1.499 USD |
| *(alternativa)* **eCPPTv2** | INE Security | Mid-2030 | ~$400 USD |

> **Nota:** OSEP é o salto após OSCP — foca em evasão de AV/EDR, pivoting e operações avançadas. CRTO é excelente para Active Directory e C2.

### Labs & Prática

- HackTheBox Pro Labs: **Offshore** e **Dante**
- Montar lab de AD em casa: Windows Server + domínio + GPOs + Bloodhound
- Contribuir com ferramentas open-source de segurança ofensiva
- Publicar write-ups de CTF e vulns descobertas em bug bounty

---

## Tabela Resumo — Certificações por Ano

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

> "O melhor red teamer que já encontrei passou 3 anos em SOC antes de virar ofensivo. Ele sabia exatamente o que não aparecia nos logs." — perspectiva comum na comunidade

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
