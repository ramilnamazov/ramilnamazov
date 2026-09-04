# Hi, I'm Ramil 👋

<a href="https://linkedin.com/in/ramilnamazov">![LinkedIn](https://img.shields.io/badge/-LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white)</a> <a href="https://ramilnamazov.com/">![ramilnamazov.com](https://img.shields.io/badge/-ramilnamazov.com-0d1117?style=for-the-badge)</a>

**Security Engineer** — Detection, Vulnerability & Cloud Operations · New Jersey

10 years across help desk, systems support, and security engineering — currently running vulnerability management and detection operations at a global bank, chasing critical findings across 3,000+ assets so nobody else has to find them the hard way. I build the tooling that removes the manual step: a fleet remediation script instead of RDP'ing into hundreds of boxes one at a time, a MITRE ATT&CK technique turned into a tested detection rule, a vulnerability export turned into a dashboard a team actually opens every morning instead of a spreadsheet nobody reads. Somewhere around year three of "have you tried turning it off and on again," I got tired of asking and just automated the part where I ask.

*Vulnerability Management · Detection Engineering · Alert Tuning · Threat Hunting · Incident Response & Forensics · Cloud Security · IAM · EDR · SIEM Engineering · Security Automation · GRC & Compliance*

**Day job runs on:** Microsoft Sentinel, Tenable Nessus & Qualys, Azure Entra ID, SCCM & Intune, across 3,000+ Windows & macOS endpoints.

---

## 🔧 Featured Projects

### [US Infra Vulnerability Dashboard](https://github.com/ramilnamazov/VulnManagment_Powerbi) — [live demo](https://ramilnamazov.github.io/VulnManagment_Powerbi/)
Interactive, Power BI–styled vulnerability management dashboard shipped as a single self-contained HTML file — click-to-filter KPIs, cross-page filter persistence, CISA KEV tracking, and a regulatory scorecard mapped to FedRAMP / NIST SP 800-53 / CMMC 2.0 / OSFI B-13 / FFIEC.

`HTML5` `CSS3` `vanilla JS` `zero dependencies`

![US Infra Vulnerability Dashboard demo](https://raw.githubusercontent.com/ramilnamazov/VulnManagment_Powerbi/main/assets/dashboard-demo.gif)

### [Siemphony Detection Corpus](https://github.com/ramilnamazov/siemphony-detections) — [live product](https://www.siemphony.com)
400 machine-authored, adversarially reviewed Sigma detection rules covering 402 MITRE ATT&CK techniques — each translated to Splunk SPL, Microsoft Sentinel KQL, Elastic ES|QL, and Wazuh where the backend can actually express it. Six techniques are left with no rule at all, on purpose, with the gap documented rather than papered over. The rules ship free on GitHub; siemphony.com is the live product — author a rule in Sigma, get every SIEM dialect back with the ATT&CK mapping and reasoning attached.

`Sigma` `MITRE ATT&CK` `Splunk SPL` `Sentinel KQL` `Elastic ES|QL` `Wazuh`

![Siemphony demo](assets/siemphony-demo.gif)

### [FleetPatch](https://github.com/ramilnamazov/fleetpatch)
Single-file Windows GUI tool that discovers, plans, executes, and verifies remote Java remediation across a fleet of workstations over PsExec and admin shares — no agent, verified by SHA-256 after every replace.

`Python` `tkinter` `PsExec`

### [PWDTYPER](https://github.com/ramilnamazov/PWDTYPER)
AES-256 encrypted credential vault that types credentials into any window via simulated keystrokes — built for Remote Desktop sessions where clipboard paste is blocked or unreliable.

`Python` `AES-256` `Windows`

### [Kommandor](https://github.com/ramilnamazov/kommandor-releases) — [live site](https://kommandor-website.vercel.app/)
Agentless Windows & Linux fleet management — no cloud, no agents to deploy. Windows side runs PsExec-based remote commands, a live host grid with ping status, 40+ one-click Quick Fix templates, and a full system toolkit (registry, services, event logs, certs, scheduled tasks). Linux side holds a persistent SSH connection pool across servers for package/service/firewall/container/cron management. Every action — command, fix, deploy — writes to a local audit database with a timestamp and result.

`Python` `PsExec` `SSH` `Windows & Linux` `Local audit log`

![Kommandor demo](assets/kommandor-demo.gif)

### Security Labs — [Azure SOC / HoneyNet](https://github.com/ramilnamazov/Azure-Soc) & [AD + Atomic Red Team + Splunk](https://github.com/ramilnamazov/Atomic-Red-Project-)
Hands-on purple-team environments: a live Azure honeynet feeding a SOC pipeline, and an Active Directory lab instrumented with Splunk to detect Atomic Red Team–simulated attacks.

`Azure` `Splunk` `Active Directory` `Atomic Red Team`

---

## 🚀 Also shipped — outside security

Products built and shipped end-to-end, not portfolio pieces — real users, real infrastructure.

### [Tsip Tsip](https://tsiptsip.com) — Poultry Farm Management
SaaS for small poultry farms to run the business, not just log it: flock and incubation tracking, egg production and breakdown, feed-stock runway, orders, a customer bazaar, and P&L reporting down to break-even, in one dashboard.

`SaaS` `Multi-tenant` `Financial reporting`

![Tsip Tsip demo](assets/tsiptsip-demo.gif)

### [Chumad](https://www.chumad.com) — Private. Instant. Gone.
Ephemeral, client-side-encrypted sharing — clipboard drops, chat, and invite-only circles, built so the server has nothing worth subpoenaing. A room's optional passphrase is combined with its Room ID and encrypted **entirely in-browser** — it's never transmitted, so Chumad's own servers cannot decrypt a room even under compulsion. Every room carries a hard TTL (15 min / 1 hr / 24 hr) enforced server-side with no recovery path once it lapses, and an optional "burn after read" mode destroys the content the moment a second participant joins — a one-time read, not just a timer. Ending a session live-wipes the room for every connected participant, not just the initiator.

`Client-side AES` `Zero-knowledge server` `WebSocket live sync` `TTL self-destruct`

![Chumad demo](assets/chumad-demo.gif)

---

## 🧭 Skills → Projects

| Skill | Demonstrated in |
|---|---|
| Detection engineering (Sigma / MITRE ATT&CK) | [siemphony-detections](https://github.com/ramilnamazov/siemphony-detections) |
| Vulnerability management & reporting | [VulnManagment_Powerbi](https://github.com/ramilnamazov/VulnManagment_Powerbi) |
| SIEM implementation & log analysis | [Azure-Soc](https://github.com/ramilnamazov/Azure-Soc) |
| Fleet / endpoint remediation tooling | [fleetpatch](https://github.com/ramilnamazov/fleetpatch) |
| Secure credential handling & automation | [PWDTYPER](https://github.com/ramilnamazov/PWDTYPER) |
| Active Directory & purple-teaming | [Atomic-Red-Project-](https://github.com/ramilnamazov/Atomic-Red-Project-) |

---
## 🛠️ Tools & Technologies

**SIEM & Detection**

![sentinel](https://img.shields.io/badge/-Microsoft%20Sentinel-0078D4?style=for-the-badge&logo=microsoft&logoColor=white) ![splunk](https://img.shields.io/badge/-Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white) ![qradar](https://img.shields.io/badge/-IBM%20QRadar-054ADA?style=for-the-badge&logo=ibm&logoColor=white) ![wazuh](https://img.shields.io/badge/-Wazuh-04A777?style=for-the-badge&logo=wazuh&logoColor=white) ![KQL](https://img.shields.io/badge/-KQL-00809D?style=for-the-badge)

**Endpoint & EDR**

![sentinelone](https://img.shields.io/badge/-SentinelOne-DB1F76?style=for-the-badge) ![defender](https://img.shields.io/badge/-Defender%20for%20Endpoint-00A4EF?style=for-the-badge) ![sccm](https://img.shields.io/badge/-SCCM-5B5B5B?style=for-the-badge) ![intune](https://img.shields.io/badge/-Intune-0078D4?style=for-the-badge) ![patchmypc](https://img.shields.io/badge/-PatchMyPC-F58220?style=for-the-badge) ![wireshark](https://img.shields.io/badge/-Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white) ![macos](https://img.shields.io/badge/-macOS-000000?style=for-the-badge&logo=apple&logoColor=white)

**Vulnerability Management**

![nessus](https://img.shields.io/badge/-Tenable%20Nessus-339933?style=for-the-badge) ![qualys](https://img.shields.io/badge/-Qualys-E4002B?style=for-the-badge) ![CVSS 3.1](https://img.shields.io/badge/-CVSS%203.1-C1272D?style=for-the-badge) ![nmap](https://img.shields.io/badge/-Nmap-4D4D4D?style=for-the-badge&logo=nmap&logoColor=white) ![metasploit](https://img.shields.io/badge/-Metasploit-000000?style=for-the-badge&logo=metasploit&logoColor=white)

**Identity & Access**

![ad](https://img.shields.io/badge/-Active%20Directory-0052CC?style=for-the-badge) ![entra](https://img.shields.io/badge/-Azure%20Entra%20ID-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white) ![avd](https://img.shields.io/badge/-Azure%20Virtual%20Desktop-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white) ![IAM](https://img.shields.io/badge/-IAM-5C2D91?style=for-the-badge) ![MFA/SSO](https://img.shields.io/badge/-MFA%20%2F%20SSO-107C10?style=for-the-badge) ![PAM](https://img.shields.io/badge/-PAM-B7472A?style=for-the-badge) ![Conditional Access](https://img.shields.io/badge/-Conditional%20Access-0078D4?style=for-the-badge) ![GPO](https://img.shields.io/badge/-Group%20Policy%20%28GPO%29-5B5B5B?style=for-the-badge) ![PKI](https://img.shields.io/badge/-PKI%20%2F%20Cert%20Lifecycle-8A6D00?style=for-the-badge)

**Cloud & Email Security**

![azurecloud](https://img.shields.io/badge/-Azure%20Log%20Analytics-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white) ![guardduty](https://img.shields.io/badge/-AWS%20GuardDuty-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) ![proofpoint](https://img.shields.io/badge/-Proofpoint-EE3831?style=for-the-badge) ![mimecast](https://img.shields.io/badge/-Mimecast-E2231A?style=for-the-badge)

**Scripting, Automation & Threat Analysis**

![powershell](https://img.shields.io/badge/-PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white) ![python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white) ![REST APIs/SQL](https://img.shields.io/badge/-REST%20APIs%20%2F%20SQL-00758F?style=for-the-badge) ![mitre](https://img.shields.io/badge/-MITRE%20ATT%26CK-333333?style=for-the-badge) ![yara](https://img.shields.io/badge/-YARA-333333?style=for-the-badge) ![virustotal](https://img.shields.io/badge/-VirusTotal-394EFF?style=for-the-badge&logo=virustotal&logoColor=white) ![cuckoo](https://img.shields.io/badge/-Cuckoo%20Sandbox-000000?style=for-the-badge)

**Compliance & Reporting**

![nist](https://img.shields.io/badge/-NIST-002F6C?style=for-the-badge) ![cis](https://img.shields.io/badge/-CIS%20Benchmarks-00629B?style=for-the-badge) ![iso](https://img.shields.io/badge/-ISO%2027001-4B4B4B?style=for-the-badge) ![soc2](https://img.shields.io/badge/-SOC%202-2E2E38?style=for-the-badge) ![pcidss](https://img.shields.io/badge/-PCI%20DSS-6E1E2C?style=for-the-badge) ![gdpr](https://img.shields.io/badge/-GDPR-003399?style=for-the-badge) ![servicenow](https://img.shields.io/badge/-ServiceNow-62D84E?style=for-the-badge&logo=servicenow&logoColor=white) ![jira](https://img.shields.io/badge/-Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white) ![powerbi](https://img.shields.io/badge/-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=white)

---

## 📜 Certifications

<a href="https://www.comptia.org/certifications/cybersecurity-analyst">![cysa](https://img.shields.io/badge/-CompTIA%20CySA%2B-00B0F0?style=for-the-badge&logo=comptia&logoColor=white)</a> <a href="https://www.comptia.org/certifications/security">![secplus](https://img.shields.io/badge/-CompTIA%20Security%2B-00B0F0?style=for-the-badge&logo=comptia&logoColor=white)</a> <a href="https://www.comptia.org/certifications/which-certification/stackable-certifications">![secanalytics](https://img.shields.io/badge/-Security%20Analytics%20Professional-5B5B5B?style=for-the-badge&logo=comptia&logoColor=white)</a> <a href="https://www.credly.com/badges/b721d749-d3e0-466c-8e50-1ea3ceede787/linked_in_profile">![rfsoc2](https://img.shields.io/badge/-RangeForce%20SOC2-1F1F1F?style=for-the-badge)</a> <a href="https://learn.microsoft.com/en-us/certifications/azure-fundamentals/">![az900](https://img.shields.io/badge/-Microsoft%20Azure%20AZ--900-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)</a> <a href="https://www.credly.com/badges/2e487fa7-7592-482e-bc44-3065e77b16fc/linked_in_profile">![rfmitre](https://img.shields.io/badge/-RangeForce%20MITRE%20ATT%26CK%20Ready-1F1F1F?style=for-the-badge)</a> <a href="https://www.credly.com/org/rangeforce/badge/junior-penetration-tester">![rfjr](https://img.shields.io/badge/-RangeForce%20Junior%20Penetration%20Tester-1F1F1F?style=for-the-badge)</a>

---

## 🎓 Education & Languages

B.A., Business Administration / International Relations — Yalova University, 2015  

English · Russian · Turkish (fluent) · Georgian (native)

---

## 📫 Contact

<a href="https://linkedin.com/in/ramilnamazov">![linkedin](https://img.shields.io/badge/-LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white)</a> <a href="mailto:ramil.namazov@protonmail.com">![email](https://img.shields.io/badge/-Email-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white)</a> <a href="https://ramilnamazov.com/">![ramilnamazov.com](https://img.shields.io/badge/-ramilnamazov.com-0d1117?style=for-the-badge)</a>
