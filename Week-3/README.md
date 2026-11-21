# 🔐 Week 3: Password Cracking & Hash Analysis

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Week](https://img.shields.io/badge/Week-03-blue)
![Program](https://img.shields.io/badge/Program-Networkwalks-CB3837)
![Focus](https://img.shields.io/badge/Focus-Password%20Cracking-red)

Welcome to **Week 3** of my Cybersecurity Journey! This week was a deep dive into the world of **Password Cracking and Hash Extraction**. I learned how passwords are stored within protected files, how to extract their hashes, and the techniques used by ethical hackers to recover them to test system security.

---

## 📑 Final Submission Report

> **📄 The complete, consolidated report for all modules of Week 3 has been submitted.**

| Field | Details |
| :--- | :--- |
| **Report File** | [`W3-PM-FINAL - Report.docx`](./W3-PM-FINAL%20-%20Report.docx) |
| **Status** | ✅ Submitted |
| **Modules Covered** | W3-PM1 • W3-PM2 |
| **Phases Covered** | Phase 3: Password Cracking & Hash Analysis |
| **Target** | `My Locked PDF1.pdf, My Locked PDF2.pdf, My Locked PDF3.pdf` (Provided Lab Environment) |
| **Author** | Yash Raj |
| **Program** | Cybersecurity @ Networkwalks |

The final report consolidates the step-by-step methodology, screenshots, risk analysis, and detailed findings for cracking a password-protected PDF using both CLI/GUI and Web-based tools.

---

## 🎯 Modules Completed

| # | Module | Description | Report |
| :--- | :--- | :--- | :--- |
| 1 | **[W3-PM1: Password Cracking with JTR](./Project-Module-1-JTR/README.md)** | Configured John the Ripper (JTR) core with the Johnny GUI interface to prepare for offline password cracking. | 📂 |
| 2 | **[W3-PM2: Password Cracking with NW Tools](./Project-Module-2-NW-Tools/README.md)** | Utilized Networkwalks' Hash Calculator & Password Cracker web tools to perform a dictionary attack and crack the PDF password. | 📂 |

---

## 🛠️ Tools Used

| Tool | Module | Purpose |
| :--- | :--- | :--- |
| **John the Ripper (JTR)** | W3-PM1 | Command-line password cracking engine. |
| **Johnny GUI** | W3-PM1 | Graphical interface to simplify JTR operations. |
| **NW Hash Calculator** | W3-PM2 | Web tool to extract `$pdf$` hashes from protected files. |
| **NW Password Cracker** | W3-PM2 | Web tool to execute dictionary attacks on extracted hashes. |

---

## 💡 Key Learnings

- 🛡️ **Human Predictability is the Weakest Link:** The PDF password was `password1` — a highly predictable pattern that was cracked instantly using a simple 100-word dictionary list.
- 🧩 **Hashing vs. Encryption:** Encryption is a two-way function (can be decrypted), whereas Hashing is a one-way function. However, if a weak password is hashed, it can still be cracked (matched) using dictionary or brute-force attacks.
- 💻 **Offline Cracking Threat:** Once a file is stolen, the attacker has all the time in the world to crack the hash offline without triggering any security alerts. 
- ⚖️ **Ethics First:** All cracking activities were performed strictly on lab-provided files within an authorized environment.

---

## 📂 Repository Structure

```
📦 Week-03-Password-Cracking
├── 📄 W3-PM-FINAL - Report.docx # ⭐ Final consolidated submission
├── 📁 Project-Module-1-JTR
│ ├── README.md
│ └── screenshots/ # JTR setup, Johnny GUI configuration
├── 📁 Project-Module-2-NW-Tools
│ ├── README.md
│ └── screenshots/ # Hash extraction, Cracking process
└── 📄 My Locked PDF1.pdf # Target file provided for the lab
```

---

## 🙏 Acknowledgements

A huge thank you to my instructor **@Waqas Karim (CCIE)** for the continuous guidance, and to **[@Networkwalks](https://www.linkedin.com/company/networkwalks/)** for developing custom, easy-to-use tools like the Hash Calculator and Password Cracker that make learning these concepts so accessible.

---

## 🔗 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/yash-raj-ba4414312)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/y-ro9)

---

> ⚠️ **Disclaimer:** All activities documented in this repository were performed strictly within the scope of a controlled lab environment provided by Networkwalks. This content is for educational purposes only. Unauthorized access to systems or cracking passwords without permission is illegal.

