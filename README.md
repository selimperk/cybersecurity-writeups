# Security Research & Investigation Notes

This repository is my ongoing collection of write-ups and lab notes covering **Malware Analysis**, **Digital Forensics & Incident Response (DFIR)**, and **Red Teaming / Penetration Testing**. 

Over time, I've been solving challenges on platforms like **Hack The Box**, **TryHackMe** and **LetsDefend**, as well as analyzing samples in my own isolated lab. Rather than writing simple step-by-step "how-to" guides or flag walkthroughs, I try to treat each scenario like a real-world investigation.

My main focus across these notes is:
- Developing a structured investigative and analytical methodology
- Understanding how malware operates under the hood (static & dynamic analysis)
- Getting comfortable with Windows artifacts, memory dumps, and network logs
- Understanding offensive attack paths to see what kind of footprints they leave behind
- Documenting my reasoning, dead ends, and how I validate findings

The level of detail varies from case to case, as these are primarily my personal working notes. The goal isn't perfection, but transparency in how I think through problems, pivot between tools, and reach conclusions.

This repository mainly serves as:
- A personal knowledge base I can reference whenever I need it
- A way to document and share my learning process publicly
- A resource for others practicing DFIR, reverse engineering, or pentesting

## Folders
- `01-Malware-Analysis/` – Reverse engineering notes, unpacking, and config extraction (Ghidra, x32dbg, REMnux)
- `02-DFIR/` – Sherlock cases, LetsDefend alerts, and forensic timeline investigations
- `03-Penetration-Testing/` – Retired HTB machines and Active Directory attack paths

*(Note: I only publish write-ups for retired challenges, and I never upload live malware binaries—only my notes, screenshots, and YARA rules.)*