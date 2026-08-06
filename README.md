# SSH Honeypot and Intrusion Detection System

## Overview

The **SSH Honeypot and Intrusion Detection System** is a cybersecurity project that simulates a vulnerable SSH server using **Cowrie** to capture and analyze unauthorized login attempts. The project aims to demonstrate practical security monitoring by collecting attacker activity, detecting brute-force attempts, and automating basic incident response using Bash scripts.

This project is being developed as a hands-on learning exercise to strengthen Linux administration, security monitoring, and automation skills.

---

## Objectives

* Deploy an SSH honeypot to capture malicious login attempts.
* Monitor attacker activity through Cowrie log files.
* Automate log parsing and attack detection using Bash.
* Detect brute-force attacks based on configurable thresholds.
* Automatically block malicious IP addresses using `iptables`.
* Generate security reports summarizing detected attacks.

---

## Technologies Used

* Linux
* Cowrie SSH Honeypot
* Bash
* iptables
* Git
* VMware

---

## Planned Features

* SSH honeypot deployment using Cowrie
* Log collection and monitoring
* Automated log parsing
* Brute-force attack detection
* Automatic IP blocking
* Security report generation
* Optional email notifications
* Configurable detection thresholds

---

## Project Structure

```text
SSH-Honeypot-and-Intrusion-Detection-System/
│
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── architecture.png
│   └── screenshots/
├── sample_logs/
│   └── cowrie.log
├── scripts/
│   ├── analyze_logs.sh
│   ├── detect_bruteforce.sh
│   ├── block_ip.sh
│   └── generate_report.sh
└── config/
```

---

## Project Workflow

```text
Attacker
    │
    ▼
Cowrie SSH Honeypot
    │
    ▼
Cowrie Log Files
    │
    ▼
Bash Analysis Scripts
    │
    ├── Extract attacker IPs
    ├── Count login attempts
    ├── Detect brute-force attacks
    └── Generate reports
             │
             ▼
      Automated Response
      (iptables Block)
```

---

## Development Roadmap

* [x] Project planning
* [x] Repository structure
* [ ] Deploy Cowrie honeypot
* [ ] Capture authentication attempts
* [ ] Parse Cowrie logs
* [ ] Detect brute-force attacks
* [ ] Automate IP blocking
* [ ] Generate attack reports
* [ ] Add screenshots and documentation

---

## Learning Goals

This project is intended to improve practical knowledge in:

* Linux System Administration
* Bash Scripting
* Network Security
* Log Analysis
* Security Monitoring
* Incident Response Fundamentals
* Firewall Management
* Git and GitHub

---

## Future Improvements

* ELK Stack integration
* Splunk integration
* GeoIP attacker visualization
* MITRE ATT&CK technique mapping
* Email and Slack alerting
* Web dashboard for attack statistics

---

## License

This project is released under the MIT License.

---

## Author

**Sangeetham Padma Teja**

* GitHub: https://github.com/Padmateja-000
* LinkedIn: https://linkedin.com/in/padma-teja-sangeetham
