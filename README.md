# NETWORKWALKS-B083-WK3-PM-PASSWORD-CRACKING
Password cracking project using John the Ripper (JTR) and NetworkWalks browser-based tools. Week 3 of Cybersecurity &amp; Ethical Hacking Internship at NetworkWalks.

Password Cracking — Week 3 Project

**Week 3 of the Cybersecurity & Ethical Hacking Internship at Networkwalks (Batch B082)**

Project Overview

This project demonstrates two methods of password cracking against a protected PDF file:

1. **John the Ripper (JTR)** — command-line cracking on Kali Linux
2. **Networkwalks Tools** — browser-based hash extraction and dictionary attack

The goal is to understand how password hashing works, how dictionary attacks function, and why strong passwords matter for protecting sensitive data.

Objectives

- Extract a crackable hash from a locked PDF using `pdf2john`
- Crack the hash using John the Ripper and `rockyou.txt`
- Crack the same hash using Networkwalks Hash Calculator + Password Cracker
- Open the PDF with the recovered password
- Understand the difference between encryption and hashing

Tools Used

| Tool | Purpose | Platform |
|------|---------|----------|
| **Kali Linux** | OS for JTR tools | VMware |
| **John the Ripper (John)** | Command-line password cracker | Kali Linux |
| **pdf2john** | PDF hash extractor | Kali Linux |
| **rockyou.txt** | Wordlist for dictionary attacks | Kali Linux |
| **NW Hash Calculator** | Browser-based hash extractor | Web Browser |
| **NW Password Cracker** | Browser-based dictionary attack | Web Browser |

Key Findings

| Finding | Details |
|---------|---------|
| **Target File** | My Locked PDF1.pdf |
| **Hash Type** | PDF (MD5 AES-128, Revision 4) |
| **Cracked Password** | `good-luck` |
| **Time to Crack** | Under 1 second (weak password) |
| **Wordlist Used** | rockyou.txt (14M+ passwords) |
