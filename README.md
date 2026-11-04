<div align="center">

# 🚩 CTF Writeups & Security Labs

**Hands-on notes from CTFs and labs — attack it, then learn how to detect it.**

![Focus](https://img.shields.io/badge/Focus-SOC%20%7C%20AppSec-0A66C2?style=for-the-badge)
![Platforms](https://img.shields.io/badge/Platforms-THM%20%7C%20HTB%20%7C%20picoCTF%20%7C%20CyberDefenders-red?style=for-the-badge)

🇺🇸 English · [🇧🇷 Português](README.pt-BR.md)

</div>

---

## 👋 About

I'm Mattheus, a junior cybersecurity analyst (SOC Tier 1 / AppSec) from Brazil. This repository is where I document the CTFs and labs I solve.

Most writeups have a short **"Blue Team view"** section. After exploiting something, I write down what it would look like from the defender's side: logs, network traffic, and how a SOC analyst could detect it.

Portfolio: [mattheusalfonso.github.io](https://mattheusalfonso.github.io)

## 🗂️ Structure

```
ctf-writeups/
├── tryhackme/        # TryHackMe rooms
├── hackthebox/       # Hack The Box (retired machines only)
├── picoctf/          # picoCTF challenges
├── cyberdefenders/   # Blue team labs (PCAP, logs, forensics)
└── _template/        # Writeup template
```

Each writeup lives in its own folder: `platform/room-name/README.md`, with screenshots in `platform/room-name/img/`.

## 📈 Progress

| Platform | Room / Challenge | Category | Difficulty | Date | Writeup |
| -------- | ---------------- | -------- | :--------: | :--: | :-----: |
| —        | Coming soon      | —        | —          | —    | —       |

## 📜 Rules I follow

- **No flags or direct answers.** I explain the method, not the answer to copy, and flags are redacted (`THM{REDACTED}`).
- **Hack The Box:** I only publish writeups for **retired** machines, as the platform requires.
- **Legal and isolated only.** Everything here was done on CTF platforms or in my own VirtualBox lab, never against systems I don't own or don't have permission to test.
- **No secrets in git.** VPN files (`.ovpn`), credentials and large captures are blocked by `.gitignore`.

## 🔗 Resources I use

- [TryHackMe Free Rooms checklist](https://github.com/jkx00/TryHackMe-Free-Rooms) by jkx00: a topic-organized list of free THM rooms.
