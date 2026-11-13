# 🕵️‍♂️ Week 2: Footprinting & Network Scanning

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Week](https://img.shields.io/badge/Week-02-blue)
![Program](https://img.shields.io/badge/Program-Networkwalks-CB3837)
![Focus](https://img.shields.io/badge/Focus-Recon%20%26%20Scanning-orange)

Welcome to **Week 2** of my Cybersecurity Journey! This week was all about the **Reconnaissance** and **Scanning** phases of a Penetration Test. I learned how attackers gather publicly available information about a target and map out a local network — all within a strictly authorized scope.

---

## 📑 Final Submission Report

> **📄 The complete, consolidated report for all three modules of Week 2 has been submitted.**

| Field | Details |
| :--- | :--- |
| **Report File** | [`W2-PM-FINAL - Report.docx`](./W2-PM-FINAL%20-%20Report.docx) |
| **Status** | ✅ Submitted |
| **Modules Covered** | W2-PM1 • W2-PM3 • W2-PM5 |
| **Phases Covered** | Phase 1: Reconnaissance & Footprinting <br> Phase 2: Scanning & Network Discovery |
| **Target** | `networkwalks.com` (with written permission) & own local LAN (`172.16.7.0/24`) |
| **Author** | [Your Name] |
| **Program** | Cybersecurity @ Networkwalks |

The final report consolidates findings, screenshots, risk analysis, recommendations, and a detailed conclusion for all three modules.

---

## 🎯 Modules Completed

| # | Module | Description | Report |
| :--- | :--- | :--- | :--- |
| 1 | **[W2-PM1: Footprinting with Multiple Kali Tools](./Project-Module-1-Kali-Tools/README.md)** | Used 6 different tools (WHOIS, WhatWeb, Nslookup, Curl, Wafw00f, DNSRecon) to extract information about `networkwalks.com`. | 📂 |
| 2 | **[W2-PM3: Maltego based Footprinting](./Project-Module-3-Maltego/README.md)** | Used OSINT techniques to harvest email addresses linked to the target domain using Maltego Graph. | 📂 |
| 3 | **[W2-PM5: Zenmap based Network Scanning](./Project-Module-5-Zenmap/README.md)** | Performed host discovery on my local LAN (`172.16.7.0/24`) to find live hosts and MAC addresses. | 📂 |

---

## 🛠️ Tools Used

| Tool | Module | Purpose |
| :--- | :--- | :--- |
| **WHOIS** | W2-PM1 | Domain registration details |
| **WhatWeb** | W2-PM1 | Web technology fingerprinting |
| **Nslookup** | W2-PM1 | DNS resolution |
| **Curl** | W2-PM1 | HTTP header inspection |
| **Wafw00f** | W2-PM1 | WAF detection (ModSecurity) |
| **DNSRecon** | W2-PM1 | DNS record enumeration |
| **Maltego** | W2-PM3 | OSINT & email harvesting |
| **Zenmap (Nmap GUI)** | W2-PM5 | Host discovery & topology mapping |

---

## 💡 Key Learnings

- 🔎 **Information is Power:** Even without sending a single malicious packet, tools like WHOIS and WhatWeb can reveal the CMS (WordPress 7.1.4), plugins (WP Download Manager), and WAF (ModSecurity) in use.
- 🕸️ **OSINT Mapping:** Maltego visually demonstrates how public data (like domain names) links to sensitive information (like employee emails) which can be weaponized for phishing.
- 🌐 **Network Visibility:** Zenmap (Nmap GUI) makes it incredibly easy to map a subnet, identify unauthorized devices (Grandstream, D-Link), and create visual network topologies.
- ⚖️ **Ethics First:** Every scan was performed only on authorized targets — permission is non-negotiable in pentesting.

---

## 📂 Repository Structure
```
📦 Week-02-Footprinting-and-Scanning
├── 📄 W2-PM-FINAL - Report.docx # ⭐ Final consolidated submission
├── 📁 Project-Module-1-Kali-Tools
│ ├── README.md
│ └── screenshots/
├── 📁 Project-Module-3-Maltego
│ ├── README.md
│ └── screenshots/
└── 📁 Project-Module-5-Zenmap
├── README.md
├── screenshots/
└── zenmap.pdf
```
---
