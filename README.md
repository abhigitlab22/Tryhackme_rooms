# Tryhackme_rooms
# 🛡️ TryHackMe Writeups & Pentesting Notes

Welcome to my offensive security repository! Here I document my methodology, tools, and lessons learned while completing hands-on Capture The Flag (CTF) rooms on **TryHackMe**.

## 🧰 Tools & Skills Practiced
- **Reconnaissance & Enumeration:** Nmap, Gobuster, Enum4linux, SMBclient
- **Credential & Hash Attacks:** Hydra, John the Ripper, Hashcat
- **Exploitation & Privilege Escalation:** Linux SUID/Sudo exploitation, FTP/SSH misconfigurations, Windows Active Directory enumeration, and Kerberoasting

## 📝 Completed Room Summaries

### 1. Brute It
- **Focus:** Brute-forcing, hash cracking, and Linux privilege escalation.
- **Key Takeaways:** Enumerated hidden web directories, used Hydra to brute-force web login forms, cracked SSH private key passphrases with John the Ripper, and escalated privileges via `sudo` misconfigurations.

### 2. Brooklyn Nine-Nine
- **Focus:** Service enumeration, steganography, and basic privilege escalation.
- **Key Takeaways:** Exploited anonymous FTP access, uncovered hidden credentials using steganography tools, and leveraged misconfigured `sudo` binaries to gain root access.

### 3. Bounty Hacker
- **Focus:** FTP enumeration, SSH brute-forcing, and privilege escalation.
- **Key Takeaways:** Retrieved leaked task and password lists from an open FTP server, gained user access via Hydra SSH brute-forcing, and escalated to root using `tar` privilege escalation.

### 4. VulnNet: Active
- **Focus:** Windows Active Directory & SMB enumeration.
- **Key Takeaways:** Enumerated SMB shares and domain users, performed Kerberoasting/AS-REP roasting techniques to retrieve service credentials, and navigated Active Directory privilege escalation paths.

### 5. VulnNet: Endgame
- **Focus:** Multi-stage web exploitation and privilege escalation.
- **Key Takeaways:** Combined thorough web enumeration, vulnerability chaining, and post-exploitation enumeration to compromise the target system end-to-end.

## 🔗 Profiles
- **TryHackMe Profile:** https://tryhackme.com/p/ethicalhack226?utm_campaign=social_share&utm_medium=social&utm_content=profile&cardVersion=700e47357dde&utm_source=copy&share_date=2026-11-16&sharerId=6a831f0d3cb794353e0ca16e
