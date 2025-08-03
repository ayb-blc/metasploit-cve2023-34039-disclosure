# Responsible Disclosure: Metasploit CVE-2023-34039 Module – Hardcoded SSH Keys

## 📌 Summary

During a penetration test in July 2025, I discovered multiple unprotected, hardcoded SSH private keys embedded within the Metasploit Framework Snap package. The keys were located inside the module data for CVE-2023-34039.

I responsibly disclosed the issue to the Rapid7 Security Team.

## 🔐 Files

Several `id_rsa_vnera_keypair_*` files, readable by all users

## 🧾 Resolution

Rapid7 responded on the same day, confirming that these SSH keys are intentionally included in the Metasploit module for testing vulnerable VMware Aria Operations for Networks systems and do not represent a vulnerability in their codebase.

## 📫 Communication

Initial email sent: July 30, 2025  
Response received: July 30, 2025

> _"Thanks for reporting this, Ayberk! We're investigating this issue with our engineering & support teams – we'll get back to you soon."_  
> — Rapid7 Security Team

> _"The keys are intentionally included as part of an attack module and are not a vulnerability in our code."_  
> — Rapid7 Engineering Team

## 🧠 Notes

While not an actual vulnerability in Rapid7 code, the process improved my skills in:

- Module code review
- Public data analysis
- Responsible disclosure
- Professional security communication

## 👤 Author

Ayberk Balcı – Security Researcher & Penetration Tester  
📧 balciayberk06@gmail.com
