<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=280&section=header&text=KISHAN%20PANDEY&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Cybersecurity%20Engineer%20%7C%20Zero%20Trust%20%26%20Cloud%20Security&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+Zero+Trust+Security+Systems;Auditing+Cloud+Infrastructure+for+Misconfigurations;Breaking+Networks+to+Understand+Them;200%2B+CTF+Challenges+Solved" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/B.Tech-Computer%20Science-6D28D9?style=flat-square&logo=googlescholar&logoColor=white"/>
<img src="https://img.shields.io/badge/KIET%20Group%20of%20Institutions-2023%20--%202027-7C3AED?style=flat-square&logo=graduation-cap&logoColor=white"/>
<img src="https://img.shields.io/badge/CGPA-7.05%20%2F%2010-8B5CF6?style=flat-square"/>
<img src="https://img.shields.io/badge/Location-India-8B5CF6?style=flat-square&logo=googlemaps&logoColor=white"/>

<br/><br/>

<a href="https://github.com/sonoftroll"><img src="https://img.shields.io/badge/GitHub-1E1B4B?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://linkedin.com/in/val3nt1n3-d4c"><img src="https://img.shields.io/badge/LinkedIn-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:pandeykishan233@gmail.com"><img src="https://img.shields.io/badge/Email-4C1D95?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=sonoftroll&style=flat-square&color=8B5CF6&label=PROFILE+VIEWS"/>
<img src="https://img.shields.io/github/followers/sonoftroll?style=flat-square&color=7C3AED&label=FOLLOWERS&logo=github"/>
<img src="https://img.shields.io/github/stars/sonoftroll?style=flat-square&color=6D28D9&label=STARS&logo=github"/>

</div>

---

## About Me

```yaml
whoami: Kishan Pandey
role: Cybersecurity Engineer | Zero Trust & Cloud Security
focus: Network Security, Cloud Auditing, Breach Simulation
education: B.Tech CSE, KIET Group of Institutions (2023 - 2027) — CGPA 7.05/10
```

I'm a Computer Science undergraduate focused on **cybersecurity engineering** — building tools that model, audit, and stress-test security architectures rather than just theorize about them. My project work spans Zero Trust policy design and breach simulation, AWS cloud security auditing against CIS Benchmarks, and low-level network reconnaissance and vulnerability scanning.

I hold an **AWS Certified Cloud Practitioner** certification and compete actively in CTFs with **ByteHunters**, with 200+ challenges solved across HackTheBox and TryHackMe.

**Open To:**

- Cybersecurity / VAPT internships (paid, non-Internshala)
- Cloud security & IAM-focused engineering roles
- Zero Trust architecture and security tooling opportunities

---

## Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=python,java,bash&theme=dark"/>

**Security Tools**

<img src="https://skillicons.dev/icons?i=kali,wireshark,linux,git&theme=dark"/>

**Backend & Data**

<img src="https://skillicons.dev/icons?i=fastapi,react,postgres,redis&theme=dark"/>

**Cloud, IAM & DevOps**

<img src="https://skillicons.dev/icons?i=aws,docker,githubactions&theme=dark"/>

---

## Featured Projects

<details>
<summary><b>🔐 ZTForge — Zero Trust Architecture Designer & Breach Simulator</b></summary>

<br/>

*Mar 2026 – May 2026*

A full-stack platform to visually model Zero Trust architectures and run deterministic breach simulations.

| Category | Detail |
|---|---|
| Stack | Python, FastAPI, React, Keycloak (OIDC), Open Policy Agent (OPA), PostgreSQL, Redis, Docker |
| Scale | 15+ test scenarios across simulated attack paths |
| Performance | Graph-traversal simulation engine with real-time risk scoring |
| Security | RS256 JWT validation via Keycloak JWKS with key rotation, RBAC, per-user Redis rate limiting, OPA default-deny policy evaluation |
| Impact | Blocked 100% of simulated lateral movement paths; reduced policy misconfiguration surface by ~40% vs. an allow-all baseline; cut manual policy review time by ~60% in internal benchmarks |
| Repository | `github.com/sonoftroll/ztforge` |

Simulates stolen-credential (MITRE ATT&CK T1078), insider-threat (T1136), and privilege-escalation (T1068) scenarios, enforcing NIST 800-207 policies across graph edges. Produces exportable policy artifacts in OPA Rego, Terraform, and iptables formats.

</details>

<details>
<summary><b>☁️ CloudForge-Auditor — AWS Cloud Security & Compliance Auditor</b></summary>

<br/>

*Apr 2026 – May 2026*

A read-only AWS security auditor built around a zero false-positive design philosophy.

| Category | Detail |
|---|---|
| Stack | Python, Boto3, AWS (IAM, S3, EC2, CloudTrail), CIS Benchmarks |
| Scale | 30+ CIS Benchmark controls mapped across IAM, S3, EC2, and CloudTrail |
| Performance | Scans a typical 3-service AWS account in under 90 seconds |
| Security | Detects 8 critical misconfiguration categories, including missing root MFA, public S3 exposure, unrestricted 0.0.0.0/0 security groups, stale IAM keys, and disabled CloudTrail logging |
| Impact | Identified 12 critical findings on a test AWS environment in its first run |
| Repository | `github.com/sonoftroll/cloudforge-auditor` |

Generates prioritized CSV/HTML remediation reports designed for direct handoff to cloud infrastructure teams.

</details>

<details>
<summary><b>🕵️ ShadowProbe — Network Reconnaissance & Vulnerability Scanner</b></summary>

<br/>

*Feb 2026 – Mar 2026*

A modular network reconnaissance and vulnerability scanning framework.

| Category | Detail |
|---|---|
| Stack | Python, Scapy, Socket Programming, TCP/IP, DNS, Nmap, Kali Linux |
| Scale | ICMP/ARP host discovery, TCP-connect, SYN half-open (stealth), and UDP port scanning |
| Performance | Scans a /24 subnet in under 45 seconds vs. 3+ minutes with a naive sequential approach |
| Security | Service fingerprinting via banner grabbing across 25+ protocol signatures with a local CVE/CVSS signature database |
| Impact | Reduced manual triage time by ~50% in lab testing vs. raw Nmap output |
| Repository | `github.com/sonoftroll/shadowprobe` |

Outputs structured JSON and HTML reports with severity ratings for fast prioritization of findings.

</details>

---

## Co-Curricular & Achievements

<div align="center">

| Recognition | Details |
|---|---|
| ByteHunters CTF Team | Active competitor in national and online CTF competitions across web exploitation, binary exploitation, cryptography, and forensics |
| HackTheBox | 200+ challenges solved combined with TryHackMe; ranked in the top 5–6% globally on HackTheBox |
| TryHackMe | Hands-on exploitation experience in privilege escalation, OSINT, reverse engineering, and network forensics |
| AWS Certified Cloud Practitioner | Amazon Web Services, 2025 |

</div>

---

## Certifications

**AWS**

<img src="https://img.shields.io/badge/AWS%20Certified%20Cloud%20Practitioner%20(2025)-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>

---

## Coding & Security Profiles

<div align="center">

<a href="#"><img src="https://img.shields.io/badge/HackTheBox-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black"/></a>
<a href="#"><img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=red"/></a>

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sonoftroll&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=sonoftroll&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sonoftroll&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" width="49%"/>

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=sonoftroll&theme=darkhub&no-frame=true&no-bg=false&margin-w=10&column=7"/>

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sonoftroll&theme=tokyo-night&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C4B5FD&hide_border=true"/>

</div>

---

## Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/sonoftroll/sonoftroll/output/github-contribution-grid-snake-dark.svg"/>

</div>

---

## Current Focus

```yaml
learning:
  - Advanced Zero Trust architecture patterns
  - AWS IAM and cloud security hardening
  - Offensive security techniques via CTFs

building:
  - Expanding ZTForge's breach simulation coverage
  - Additional CIS Benchmark controls for CloudForge-Auditor

exploring:
  - Deeper packet-level analysis and protocol fingerprinting
  - VAPT internship and cloud security engineering opportunities

open_to:
  - Cybersecurity & VAPT internships
  - Cloud security / IAM engineering roles
  - Zero Trust architecture collaborations
```

---

## Connect

<div align="center">

<a href="mailto:pandeykishan233@gmail.com"><img src="https://img.shields.io/badge/Gmail-4C1D95?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/val3nt1n3-d4c"><img src="https://img.shields.io/badge/LinkedIn-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/sonoftroll"><img src="https://img.shields.io/badge/GitHub-1E1B4B?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

---

<div align="center">

*"Assume breach. Verify everything. Audit before you trust."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=footer" width="100%"/>

</div>
