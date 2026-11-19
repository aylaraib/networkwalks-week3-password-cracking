# Week 3: Password Cracking & Hash Analysis

This repository documents my **Week 3** project modules for the **Cybersecurity & Ethical Hacking** internship with **Networkwalks** (**Networkwalks Training Academy**). Both modules focus on extracting a hash from a password-protected PDF file (`My Locked PDF1.pdf`) and testing password recovery workflows.

## Lab Overview

- **Target File:** `My Locked PDF1.pdf` (65.2 KB)
- **Objective:** Extract the `$pdf$...` hash from a locked PDF, run a cracking workflow to recover the password (`password1`), and open the protected document.

## Modules Completed

### Module 1: John the Ripper (JTR) & Johnny GUI
1. Downloaded and configured **John the Ripper** (`john.exe`) alongside the **Johnny** graphical interface on Windows.
2. Extracted the `$pdf$...` hash from `My Locked PDF1.pdf` and saved it into a text file (`hash1.txt`).
3. Loaded `hash1.txt` into Johnny, started a cracking attack to recover the password (`password1`), and unlocked the protected.

### Module 2: Networkwalks Browser Tools
1. Opened the **Networkwalks Hash Calculator** in the browser and parsed `My Locked PDF1.pdf` locally to extract the `$pdf$...` hash.
2. Copied the hash into the **Networkwalks Password Cracker** dictionary attack lab and ran a wordlist pass (`password1`) to recover the password and open the file.
## Key Takeaways

- **Hashing vs. Encryption:** Encryption is a two-way process using a key to protect and decrypt data, whereas hashing is a one-way function that produces a digest used to validate information.
- **Password Strength:** Weak, common, or predictable passwords can be recovered quickly during testing, highlighting the importance of strong passwords.

## Disclaimer

Completed strictly for educational and authorized internship lab practice[cite: 1, 3, 18].
