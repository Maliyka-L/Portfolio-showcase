## About Me

Cyber Security student at **Aston University** (graduating 2028), currently in my placement year. I focus on **threat intelligence, SOC analysis and detection engineering**, and I build my own security tools in Python to learn how attacks are detected, investigated and stopped.

- 🔭 **Currently building:** Network Threat Mapper, a packet capture analyser that maps networks and detects port scans, brute force and beaconing
- 🌱 **Learning:** KQL, Microsoft Sentinel, Sigma and Elastic
- 📚 **Studying for:** CompTIA Security+
- 🧪 **Practising on:** Hack The Box (Starting Point) and TryHackMe (Pre Security path)

---

## ⭐ Featured Project: ThreatHunter SIEM

**[ThreatHunter_SIEM](https://github.com/Maliyka-L/ThreatHunter_SIEM)** · Python, Flask

A security information and event management (SIEM) tool that brings my detection projects together in one application.

- **Log Analysis:** six detection rules for web server logs, including brute force attempts, admin page access and scanner user-agents
- **Alert Engine:** analyses host events such as logins and process creation, maps detections to **MITRE ATT&CK** and correlates multi-step activity
- **Threat Intelligence:** checks IP addresses against **VirusTotal** and **AbuseIPDB**, assigns a risk score and caches results
- **Case Management:** automatically escalates High and Critical alerts to cases in my [Investigation Manager](https://github.com/Maliyka-L/Investigation_Manager)

Related: [ThreatHunter_Dashboard](https://github.com/Maliyka-L/ThreatHunter_Dashboard) (MVP dashboard for presenting findings)

---

## ☁️ Featured Project: Cloud Posture Auditor (AzureGuard)

**[Cloud_Posture_Auditor](https://github.com/Maliyka-L/Cloud_Posture_Auditor)** · Python, Flask, Azure SDK

A cloud security posture tool that audits a live Microsoft Azure subscription for misconfigurations.

- **Storage checks:** public blob access, disabled encryption, secure transfer (HTTPS) not required and outdated TLS versions
- **Network checks:** reads network security group rules and flags RDP and SSH open to the internet
- **RBAC analysis:** flags Owner and User Access Administrator assignments and subscriptions with too many Owners
- **Guest user detection:** uses **Microsoft Graph** to find external guest accounts with Azure roles
- **CIS mapping and scoring:** maps every finding to the **CIS Microsoft Azure Foundations Benchmark** and grades risk from A to F
- **Reporting:** exports colour-coded PDF audit reports, with 32 automated pytest tests

---

## 🛠️ Security Tools

| Project | What it does | Tech |
|:---|:---|:---|
| [PasswordChecker](https://github.com/Maliyka-L/PasswordChecker) | Analyses password strength using entropy, pattern detection and crack-time estimation, with a secure password generator | Python |
| [Phishing_Email_Identifier](https://github.com/Maliyka-L/Phishing_Email_Identifier) | Trains a model to detect phishing emails based on patterns | Python, Jupyter |
| [data_anonymisation_tool](https://github.com/Maliyka-L/data_anonymisation_tool) | Anonymises CSV datasets using hashing, tokenisation, redaction and AES encryption | Python |
| [log_parser_alerting_tool](https://github.com/Maliyka-L/log_parser_alerting_tool) | Scans log files for suspicious activity and generates alerts | Python |

---

## 🧪 Hands-on Labs

**[htb-writeups](https://github.com/Maliyka-L/htb-writeups)**: a write-up for every Hack The Box lab I complete, covering my approach, the tools I used and what I learned.

---

## 🗺️ Portfolio Roadmap

| # | Project | Status |
|:---:|:---|:---|
| 1 | ThreatHunter SIEM | ✅ Complete |
| 2 | [Cloud Posture Auditor](https://github.com/Maliyka-L/Cloud_Posture_Auditor) (Azure) | ✅ Complete |
| 3 | SentinelSandbox | 📋 Planned |
| 4 | Malware Genome | 📋 Planned |
| 5 | SecureCode AI | 📋 Planned |
| 6 | Incident Investigator | 📋 Planned |
| 7 | Network Threat Mapper | 🔨 In progress |
| 8 | ZeroTrust Hub | 📋 Planned |
| 9 | RiskLens | 📋 Planned |
| 10 | AttackForge | 📋 Planned |

---

## 🧰 Skills

**Languages:** Python, Java, C++, C, SQL, PHP, HTML, CSS, JavaScript
**Security:** log analysis, detection rules, MITRE ATT&CK, threat intelligence (VirusTotal, AbuseIPDB), incident case management, cloud security posture management, CIS benchmarks, Azure RBAC
**Tools & Platforms:** Flask, Git and GitHub, Microsoft Azure, Azure SDK for Python, Microsoft Graph, pytest, Hack The Box, TryHackMe

---

## 📫 Connect With Me

[LinkedIn](https://www.linkedin.com/in/maliyka-liaqat-21b53422b/)
