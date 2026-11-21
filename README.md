# Week 3 – Password Cracking with JTR & Networkwalks Tools

**Student:** Tongdiya Nancwat Bendal  
**Kali Username:** codertech  
**Submission Date:** 21 December 2025  
**Training Platform:** Networkwalks Cybersecurity & Ethical Hacking

---

## Project Overview

This repository contains the documentation and results for **Week 3 Project Modules 1 & 2**.

The goal was to recover the password of a password-protected PDF file (`My Locked PDF1.pdf`) using two different methods:

| Module | Tools Used | Result |
|--------|------------|--------|
| **Module 1** | John the Ripper (JTR) + Johnny GUI | Password cracked: `password1` |
| **Module 2** | Networkwalks Hash Calculator + Password Cracker | Password cracked: `password1` |

---

## Flags Captured

- `nw{networkwalks_persistence_jtr_270521}`
- `nw{networkwalks_flag_260821_1}`

---

## Tools Used

### Module 1 – Offline Cracking
- **John the Ripper (JTR)** – Popular open-source password cracking tool
- **Johnny** – Graphical user interface (GUI) for John the Ripper

### Module 2 – Online Cracking (Browser-based)
- **Networkwalks Hash Calculator** → https://networkwalks.com/hash-calculator/
- **Networkwalks Password Cracker** → https://networkwalks.com/password-cracker/

---

## Steps Summary

### Module 1 (JTR + Johnny)
1. Installed John the Ripper and Johnny on Windows.
2. Configured Johnny to use `john.exe`.
3. Extracted the PDF hash (`$pdf$...` format).
4. Saved the hash to `hash1.txt`.
5. Loaded the hash into Johnny and started a dictionary attack.
6. Successfully recovered the password: **password1**.

### Module 2 (Networkwalks Tools)
1. Uploaded `My Locked PDF1.pdf` to the Hash Calculator.
2. Copied the extracted `$pdf$` hash.
3. Pasted the hash into the Password Cracker tool.
4. Ran a dictionary attack.
5. Successfully recovered the same password: **password1**.
6. Unlocked the original PDF using the recovered password.

---

## Key Lessons Learned

- Simple/common passwords can be cracked very quickly with dictionary attacks.
- Hash extraction is the first critical step in password recovery.
- Both offline (JTR) and online (Networkwalks) methods confirmed the same result.
- Strong, unique passwords + Multi-Factor Authentication (MFA) are essential for real-world security.

---

## Files in this Repository

| File | Description |
|------|-------------|
| `README.md` | This file |
| `Week3_Password_Cracking_Report.html` | Full HTML project report (open in browser) |
| `LinkedIn_Post_Week3_Password_Cracking.md` | Ready-to-post LinkedIn content |

---

## How to View the Report

1. Download or clone this repository.
2. Open `Week3_Password_Cracking_Report.html` in any modern web browser (Chrome, Firefox, Edge, etc.).

---

## Disclaimer

This project was completed as part of ethical hacking / cybersecurity training for educational purposes only.  
All activities were performed in a controlled lab environment using authorized materials provided by Networkwalks.

---

**Thank you to the Networkwalks team for the practical and well-structured labs!**

#Cybersecurity #EthicalHacking #PasswordCracking #JohnTheRipper #Networkwalks
