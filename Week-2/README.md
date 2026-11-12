# 🕵️‍♂️ Week 2: Footprinting & Network Scanning

Welcome to Week 2 of my Cybersecurity Journey! This week was all about the Reconnaissance and Scanning phases of a Penetration Test. I learned how attackers gather public information about a target and map out a local network.

## 🎯 Modules Completed
1. **[W2-PM1: Footprinting with Multiple Kali Tools](./Project-Module-1-Kali-Tools/README.md)**
   * Used 6 different tools to extract information about `networkwalks.com`.
2. **[W2-PM3: Maltego based Footprinting](./Project-Module-3-Maltego/README.md)**
   * Used OSINT techniques to harvest email addresses linked to the target domain.
3. **[W2-PM5: Zenmap based Network Scanning](./Project-Module-5-Zenmap/README.md)**
   * Performed host discovery on my local LAN to find live hosts and MAC addresses.

## 💡 Key Learnings
* **Information is Power:** Even without sending a single malicious packet, tools like WHOIS and WhatWeb can reveal the CMS (WordPress), plugins, and WAF (ModSecurity) in use.
* **OSINT Mapping:** Maltego visually demonstrates how public data (like domain names) links to sensitive information (like employee emails) which can be used for phishing.
* **Network Visibility:** Zenmap (Nmap GUI) makes it incredibly easy to map a subnet, identify unauthorized devices, and create visual network topologies.
