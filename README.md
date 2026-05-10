# Dhiral Vyas

**Security Engineer** — red team, vulnerability research, and source-code review across web, API, cloud (AWS / Azure / GCP), IoT & firmware, and Active Directory.

[![OSCP](https://img.shields.io/badge/OffSec-OSCP-EE0000?style=flat-square)](https://credentials.offsec.com/1584ba7d-3ab8-43ac-a99f-39f85f4426b2)
[![OSWE](https://img.shields.io/badge/OffSec-OSWE-EE0000?style=flat-square)](https://credentials.offsec.com/1c67d6a2-8669-4315-b5d3-e14a2f95f351)
[![BSCP](https://img.shields.io/badge/PortSwigger-BSCP-FF6633?style=flat-square)](https://portswigger.net/web-security/e/c/72cddeb515af9e2c)
[![MCRTA](https://img.shields.io/badge/CyberWarFare%20Labs-MCRTA-1F6FEB?style=flat-square)](https://labs.cyberwarfare.live/credential/achievement/6671bf1442b8b5382b3ef8cf)
[![CVE-2026-34519](https://img.shields.io/badge/CVE-2026--34519-8B0000?style=flat-square&logo=cve&logoColor=white)](https://github.com/aio-libs/aiohttp/security/advisories/GHSA-mwh4-6h8g-pg8w)
[![CVE-2026-44340](https://img.shields.io/badge/CVE-2026--44340-8B0000?style=flat-square&logo=cve&logoColor=white)](https://github.com/MervinPraison/PraisonAI/security/advisories/GHSA-9q28-ghcr-c4x3)

> **HackTheBox: Guru** — Top 50 Global Hall of Fame · **1st of 50+** in Praetorian's company-wide CTF
> **M.Eng. Cybersecurity**, University of Maryland · **B.Eng. ICT**, Gujarat Technological University

### Selected work

- **[CVE-2026-44340](https://github.com/MervinPraison/PraisonAI/security/advisories/GHSA-9q28-ghcr-c4x3)** — Symlink-extraction path traversal in [PraisonAI](https://github.com/MervinPraison/PraisonAI) (High, CWE-22 + CWE-59). Bypassed `_safe_extractall`'s member-name check via an unvalidated `linkname`, achieving arbitrary file write across `recipe pull`, `recipe publish`, and `recipe unpack`. Coordinated disclosure; fixed in v4.6.37. Surfaced by my [`claude-cve-research`](https://github.com/DHIRAL2908/claude-cve-research) automation pipeline.
- **[claude-cve-research](https://github.com/DHIRAL2908/claude-cve-research)** — Automation pipeline that mines the GitHub `/advisories` API, enriches and triages high-CVE-volume OSS targets, and runs semgrep / bandit / pip-audit pivots with per-target triage notes. Surfaced CVE-2026-44340 in PraisonAI on its first end-to-end run.
- **[CVE-2026-34519](https://github.com/aio-libs/aiohttp/security/advisories/GHSA-mwh4-6h8g-pg8w)** — HTTP response splitting in [AIOHTTP](https://github.com/aio-libs/aiohttp) (CVSS 5.3, CWE-113). Coordinated disclosure with maintainers; fixed in v3.13.4. Public advisory and PoC.
- **["Gone Phishing, Got a Token: When Separate Flaws Combine"](https://www.praetorian.com/blog/gone-phishing-got-a-token-when-separate-flaws-combine)** — Praetorian blog post on chaining two low-severity web findings into infrastructure compromise.
- **Pre-auth SQLi → authenticated RCE** — gray-box source review of a 100K+ LOC web platform. Chained an injection primitive into full DB read/write and briefed engineering and execs on the chain and remediation roadmap.
- **6+ onsite IoT / medical-device engagements** — full bare-metal compromise via kiosk bypass, encrypted-storage recovery, firmware reverse engineering in GHIDRA, and bootloader analysis.
- **Embedded post-exploitation framework** (Python) — restricted-shell bypass and post-exploitation toolkit; reduced manual testing time ~40%, adopted across the practice.
- **HackerOne** — disclosed exploitable vulnerabilities to major telecom and Fortune 500 financial corporations. Profile: [hackerone.com/dhiral](https://hackerone.com/dhiral).

### Focus areas

`web / API` · `cloud red team (AWS · Azure · GCP)` · `source-code review`
`IoT / firmware / bare-metal` · `Active Directory` · `vulnerability research & coordinated disclosure`

### Tools I reach for

| | |
|---|---|
| **Offense** | Burp Suite Pro · Nmap · Metasploit · BloodHound · NetExec · SQLMap · Nuclei · Frida · Hashcat |
| **RE / forensics** | GHIDRA · IDA · Volatility · Wireshark |
| **Code review** | semgrep · CodeQL · manual triage |
| **Languages** | Python · C · Bash · PowerShell · SQL · JavaScript · x86 / x64 assembly |
| **Frameworks** | OWASP Top 10 / ASVS · MITRE ATT&CK · NIST CSF · CVSS v4 · PTES |

### Teaching & community

- **Teaching Assistant — ENPM691** *(Hacking of C Programs and Unix Binaries)*, University of Maryland. Taught binary exploitation, ROP, shellcode, and heap/stack memory corruption to 30+ graduate students; designed 10+ CTF-style labs.
- **OffSec UGC author** — designed 5+ vulnerable Linux/Windows lab environments with privilege-escalation chains for OffSec's commercial training platform.
- **Mentor** — coached 100+ people through offensive-security fundamentals, CTF methodology, and OSCP / OSWE prep.
- **YouTube** — CTF writeups, certification reviews, and offensive-security tutorials at [@dhiral2908](https://youtube.com/@dhiral2908).

### Find me

| | |
|---|---|
| LinkedIn | [linkedin.com/in/dhiralvyas](https://linkedin.com/in/dhiralvyas) |
| HackerOne | [hackerone.com/dhiral](https://hackerone.com/dhiral) |
| HackTheBox | [app.hackthebox.com/users/210010](https://app.hackthebox.com/users/210010) |
| YouTube | [youtube.com/@dhiral2908](https://youtube.com/@dhiral2908) |
| Linktree | [linktr.ee/dhiral](https://linktr.ee/dhiral) |

---

<sub>If you're working on something interesting in offensive security, vulnerability research, or coordinated disclosure — happy to chat.</sub>
