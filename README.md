MITRE ATT&CK Detection Mapping Lab

A practical cybersecurity project demonstrating how security detections and threat hunting findings can be mapped to the MITRE ATT&CK Framework.

Overview

This project simulates Security Operations Center (SOC) analyst activities by mapping security events, detections, and investigation findings to MITRE ATT&CK tactics and techniques.

The lab demonstrates how analysts can use ATT&CK to classify threats, understand attacker behavior, prioritize investigations, and improve detection coverage.

Objectives

- Understand the MITRE ATT&CK Framework
- Map security events to ATT&CK techniques
- Improve threat detection visibility
- Support threat hunting investigations
- Practice SOC analyst workflows
- Document security findings using industry-recognized frameworks

Features

Detection Mapping

Maps common security detections to ATT&CK techniques including:

- Failed Login Detection
- Brute Force Detection
- Suspicious IP Activity
- Privilege Escalation Activity

Investigation Reporting

Documents findings, affected assets, risk levels, and recommended remediation actions.

Threat Classification

Uses ATT&CK techniques to classify suspicious activity and support incident investigations.

MITRE ATT&CK Techniques Covered

Technique ID| Technique
T1110| Brute Force
T1110.001| Password Guessing
T1078| Valid Accounts
T1068| Exploitation for Privilege Escalation

Project Structure

MITRE-Mapping-Lab/
├── detections/
├── mappings/
│   └── mitre_mapping.md
├── reports/
│   └── mitre_investigation_report.txt
├── screenshots/
└── README.md

Sample Detection Mapping

Failed Login Detection

Detection:
Repeated SSH authentication failures.

MITRE ATT&CK:

- T1110 – Brute Force

Severity:
Medium

Brute Force Detection

Detection:
Multiple failed login attempts from a single IP address.

MITRE ATT&CK:

- T1110.001 – Password Guessing

Severity:
High

Suspicious IP Detection

Detection:
Known malicious IP observed in authentication logs.

MITRE ATT&CK:

- T1078 – Valid Accounts

Severity:
High

Privilege Escalation Detection

Detection:
Creation of new privileged accounts and elevated commands.

MITRE ATT&CK:

- T1068 – Exploitation for Privilege Escalation

Severity:
High

Skills Demonstrated

- Threat Hunting
- MITRE ATT&CK Mapping
- Security Monitoring
- Threat Detection
- Incident Investigation
- Log Analysis
- Security Documentation
- Cybersecurity Reporting

Technologies Used

- Linux
- Termux
- Bash
- Git
- GitHub
- MITRE ATT&CK Framework

Learning Outcomes

This project helped develop practical understanding of:

- ATT&CK Tactics and Techniques
- Detection Engineering Concepts
- Threat Classification
- Incident Response Processes
- SOC Operations
- Security Investigations

Future Enhancements

- ATT&CK Navigator Layer Creation
- Sigma Rule Mapping
- Wazuh Detection Integration
- Sysmon Event Correlation
- Threat Intelligence Enrichment
- Automated ATT&CK Reporting

Author

Thabo Sakonta

Microsoft Certified Security Operations Analyst (SC-200)

GitHub:
https://github.com/thabosakonta-wq

LinkedIn:
https://www.linkedin.com/in/thabo-sakonta-377a3748

License

This project is provided for educational and portfolio purposes.
