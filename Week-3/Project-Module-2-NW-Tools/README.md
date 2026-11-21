# 🛠️ W3-PM2: Password Cracking with Networkwalks Tools

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Module](https://img.shields.io/badge/Module-W3--PM2-blue)
![Tool](https://img.shields.io/badge/Tool-Networkwalks%20Web%20Tools-orange)

## 📌 Overview
In this module, I used **Networkwalks' custom web-based tools** to perform hash extraction and a dictionary attack against a password-protected PDF file (`My Locked PDF1.pdf`). The objective was to understand how encryption works and how weak passwords are easily cracked.

## 🛠️ Tools Used
| Tool | Description |
| :--- | :--- |
| **NW Hash Calculator** | A web-based tool used to extract the crackable `$pdf$` hash from protected PDF files. |
| **NW Password Cracker** | A web-based tool that performs dictionary attacks to recover the password from the extracted hash. |
| **My Locked PDF1.pdf** | The target file provided by the Networkwalks lab. |

## 🚀 Step-by-Step Execution

1. **Downloading the Target:**
   - Downloaded the encrypted lab file (`My Locked PDF1.pdf`) to the Windows laptop.

2. **Hash Extraction (NW Hash Calculator):**
   - Opened the Networkwalks Hash Calculator in the web browser.
   - Uploaded the locked PDF file to the "File" tab.
   - The tool successfully read the encryption and extracted a crackable hash starting with `$pdf$4*4*128*...`.
   - Copied the **entire hash string** to the clipboard.

3. **Executing the Attack (NW Password Cracker):**
   - Opened the Networkwalks Password Cracker in the browser.
   - Pasted the copied `$pdf$` hash into the input field.
   - Initiated the attack using the **Built-in list (100 passwords)** for a dictionary attack.

4. **Cracking the Password:**
   - The tool cycled through the wordlist. Within seconds, it successfully found a match.
   - The cracked password was revealed on the screen as: **`password1`**

5. **Verification:**
   - Opened `My Locked PDF1.pdf` in Adobe Acrobat.
   - Entered the password `password1` when prompted.
   - The PDF successfully unlocked, revealing the "Congratulations! You have captured your 1st flag" page.

## 💡 Key Learnings
- **The Danger of Weak Passwords:** The password `password1` was in the top 100 most common passwords. It took the tool literally seconds to crack it.
- **Hashing is One-Way, but Crackable:** Hashing scrambles the password, but if the original password is weak, it can be matched against a dictionary of known hashes.
- **Offline Attack:** Once the hash is extracted, the attacker doesn't need the original file to crack it; they can do it offline at their own pace.

---
> ⚠️ **Disclaimer:** This activity was performed strictly within the authorized scope of the Networkwalks lab environment. The password `password1` was used to demonstrate the critical need for strong, complex passwords in real-world scenarios.