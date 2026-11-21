# 🔐 W3-PM1: Password Cracking with John the Ripper (JTR)

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Module](https://img.shields.io/badge/Module-W3--PM1-blue)
![Tool](https://img.shields.io/badge/Tool-John%20the%20Ripper-red)

## 📌 Overview
This module focuses on setting up **John the Ripper (JTR)**, one of the most popular open-source password cracking tools, along with its graphical user interface, **Johnny**. The goal was to configure the environment on a Windows machine to prepare for offline password cracking of protected files.

## 🛠️ Tools Used
| Tool | Description |
| :--- | :--- |
| **John the Ripper (Jumbo)** | The core command-line password cracking engine. |
| **Johnny GUI** | A graphical front-end for JTR to simplify the cracking process for beginners. |
| **Windows OS** | The host operating system used for this lab. |

## 🚀 Step-by-Step Execution

1. **Downloading the Tools:**
   - Downloaded the **JTR Jumbo** version for Windows from the official Openwall website.
   - Downloaded the **Johnny GUI** setup (`johnny_2.2_win.zip`) from the Openwall wiki.

2. **Installation:**
   - Extracted the JTR zip file to a local directory.
   - Ran the Johnny installer and completed the setup.

3. **Configuration & Linking:**
   - Opened the **Johnny** application.
   - Navigated to **Settings** from the left menu. (Since Johnny is just a GUI, it needs to be linked to the actual JTR engine).
   - Clicked on **Browse** next to the "John the Ripper executable" field.
   - Navigated to the extracted JTR folder and selected the `john.exe` file located inside the `run` directory (e.g., `C:\Users\...\JTR_John\run\john.exe`).

4. **Verification:**
   - Once the executable was selected, Johnny successfully detected the John the Ripper engine version (e.g., `v1.9.0-jumbo-1`) and displayed it on the dashboard. The tool is now ready to execute cracking tasks.

## 💡 Key Learnings
- **GUI vs CLI:** While JTR is a powerful command-line tool, Johnny makes it much easier to manage sessions and attacks visually.
- **Dependency:** GUIs like Johnny rely entirely on the underlying CLI engine to perform the actual cracking. 
- **Kali Linux Note:** If using Kali Linux, JTR comes pre-installed and can be run directly from the terminal without needing this Windows setup.

---
> ⚠️ **Disclaimer:** This setup and any subsequent cracking activities were performed strictly on lab-provided files in an authorized environment.