# Erik Kasunić

**Cybersecurity student @ IT-Högskolan (ITHS) | Blue team, detection engineering & incident response**

Stockholm, Sweden. Building a home SOC lab and publishing the tools I build along the way.

```text
$ whoami
erik_kasunic :: blue team / detection engineering

$ cat focus.txt
[+] SIEM & log analysis   (Wazuh, Sigma)
[+] Network detection     (Python, Scapy, IDS)
[+] Incident response     (NIST 800-61, MITRE ATT&CK)
[ ] Red team cert         (planned)
```

## What I'm working on

- Building a detection lab: Wazuh SIEM, Linux/Windows endpoints and a Raspberry Pi attack box to generate real attack traffic
- Writing Python tools for log analysis, network monitoring and threat-intel enrichment
- Next: red team fundamentals and my first offensive certification

## Projects by course

Personal projects I build alongside my cybersecurity program at ITHS, one for each course, in the order I take them. They are not school assignments. Every project runs in my homelab and builds on the one before.

| Course | Period | Project | What it does | Stack | Status |
|---|---|---|---|---|---|
| Operating systems: Linux & Windows | Autumn 2026 | `logsentry` | Detects brute force, new accounts and file changes in Linux and Windows logs | Python, PowerShell, Sigma, MITRE ATT&CK | Planned |
| Python | Autumn 2026 | `pysec-toolkit` | Port scanner, password checker and hash tool in one tested CLI | Python, pytest, GitHub Actions | Planned |
| Networking | Autumn 2026 | `packetwatch` | Packet sniffer and lightweight IDS, running on a VM or laptop for now (Raspberry Pi sensor later) | Python, Scapy, Wireshark | Planned |
| Virtualization & cloud | Winter 2027 | `wazuh-lab` | Wazuh SIEM with custom detection rules, deployed with Infrastructure as Code | Docker, Terraform, Wazuh | Planned |
| Cryptology | Spring 2027 | `cryptvault` | File encryption with AES-256-GCM and Argon2id, with a documented threat model | Python, cryptography | Planned |
| Malware analysis | Spring 2027 | `phishscope` | Analyzes phishing emails, extracts IOCs and enriches them with threat intel | Python, VirusTotal API, YARA | Planned |
| Threat intelligence | Spring 2027 | `threatpulse` | Tracks new CVEs and CISA KEV, matches them to my lab and writes a digest | Python, NVD API, CISA KEV | Planned |
| Digital forensics | Summer-Autumn 2027 | `timeline-forge` | Builds forensic timelines from lab logs with chain-of-custody hashing | Python, Plaso, Timesketch | Planned |
| Incident response | Autumn 2027 | `ir-playbooks` | Simulated attack from a Raspberry Pi against the lab (Atomic Red Team, Kali), detection and full incident report following NIST 800-61 | Atomic Red Team, Kali, Sigma, Wazuh | Planned |

## Other projects

Not tied to any course.

| Project | What it does | Stack | Status |
|---|---|---|---|
| `SentinelGrid` | SOC investigation platform: enriches IPs, domains and hashes from free threat-intel sources and scores the risk | TypeScript, React, Supabase, Groq | In progress |
| `homelab` | My SOC lab: architecture, configs and write-ups | VMware, Raspberry Pi, Linux, Windows | Planned |
| Red team track | `webscan`, a web vulnerability scanner for lab targets, run from a Raspberry Pi attack box, then eJPT or PNPT | Python, Kali, OWASP Top 10 | Planned |

## Skills

**Blue team:** log analysis, SIEM (Wazuh), IDS, threat intel, incident response
**Languages:** Python, Bash, PowerShell
**Platforms:** Linux, Windows, VMware, Docker, Raspberry Pi
**Networking:** TCP/IP, Wireshark, Scapy

## Background

Building hands-on skills in Linux, Windows Server, networking, troubleshooting and security analysis through studies at IT-Högskolan, while also trying to complete KTH’s technical foundation year.
Especially interested in SOC analysis and incident response, with the goal of growing into advanced security roles and working as a security consultant.

Before moving into IT, I worked in logistics at Posti Group, where I stepped in as acting team leader co-leading daily operations for around 50 people across two departments. That taught me to follow clear procedures, prioritize under pressure and keep things running when something goes wrong.

Seeking an internship (LIA) from fall 2027 and always happy to connect with peers and professionals in the field.

## Contact

[Email](mailto:github-email.basis505@passinbox.com) · Signal: Blueteam.94 · Open to internships and part-time security roles
