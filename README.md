# Cosmas Saidi

**Security Operations | Detection Engineering | Incident Investigation**

My portfolio documents completed detection and investigation work across
Windows/Active Directory, Linux, network, and Azure telemetry. The projects
demonstrate detection validation, false-positive analysis, event correlation,
evidence preservation, and documented analyst conclusions.

**Education:** Third-year Computer Science student at Kenyatta University.

## Security Operations Portfolio

| Project | Investigation & detection work |
| --- | --- |
| [SOC-001 — Linux Security Operations](https://github.com/CosmasSaidi/SOC-001-linux-security-operations) | Validated auditd-based file-change detection; investigated authorized and simulated-suspicious configuration changes with preserved audit records and file diffs. |
| [SOC-002 — Windows Detection Engineering](https://github.com/CosmasSaidi/SOC-002-windows-detection-engineering) | Tuned encoded-PowerShell detection using Sysmon/WEF evidence, confirmed a Base64-reconstruction blind spot, and validated a complementary detection. |
| [SOC-003 — Network Security Monitoring](https://github.com/CosmasSaidi/SOC-003-network-security-monitoring) | Validated Zeek/Suricata detections for controlled service discovery, DNS bursts, and periodic HTTP; correlated alerts with PCAP evidence. |
| [SOC-004 — Windows Identity & Authentication](https://github.com/CosmasSaidi/SOC-004-Windows-Identity-Authentication-Detection-Engineering-Investigation) | Validated a Kerberos Event ID 4771 rule match and closed the controlled case as benign/expected; documented audit-policy and visibility limitations. |
| [SOC-005 — Azure & Microsoft Sentinel](https://github.com/CosmasSaidi/SOC-005-Azure-Microsoft-SOC) | Validated Azure RBAC detection and Sentinel incident investigation, tuned for ingestion delay, developed KQL hunting queries, and validated Logic App incident enrichment. |

## Supplementary Investigation

**[TeamCity Network Forensics Investigation](https://github.com/CosmasSaidi/TeamCity-Network-Forensics-Investigation)** — Analyzed preserved Wireshark evidence from a
CyberDefenders lab covering suspicious plugin upload submissions, shell commands,
and Docker requests. Produced an evidence-linked timeline, qualified ATT&CK
mappings, detection opportunities, and response recommendations. Command
execution and compromise remain unverified; the report's KQL examples are
proposed and untested.

## Technical Domains

Technologies and methods evidenced in the projects above:

| Security domain | Technologies & methods |
| --- | --- |
| Windows & identity security | Active Directory, Kerberos, Windows Security events, Sysmon, WEF, PowerShell logging |
| Linux security monitoring | auditd, Bash |
| Network security monitoring | Zeek, Suricata, Wireshark/tshark |
| Azure security operations & SIEM | Microsoft Sentinel, KQL, Azure Activity, Azure RBAC, Entra Audit Logs, Logic Apps |
| Detection & investigation methods | Sigma (offline), MITRE ATT&CK, Python, PowerShell |

## Contact

- [LinkedIn](https://www.linkedin.com/in/cosmas-saidi-5965212a8)
- [Email](mailto:cosmassaidi2@gmail.com)
