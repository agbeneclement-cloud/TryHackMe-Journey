# TryHackMe-Journey 🛡️
My cybersecurity learning journey | Audit Intern @ BUA Cement Sokoto

**TryHackMe:** https://tryhackme.com/p/agbeneclement
**GitHub:** agbeneclement-cloud
**Location:** Nigeria

## ✅ Completed Rooms

### 1. Guided Pentest: Web - RecruitX [COMPLETED]
- **Room Link:** https://tryhackme.com/room/guidedpentestweb
- **Date:** Nov 2026
- **Status:** ✅ Completed
- **Difficulty:** Easy-Medium
- **Type:** Web Application Pentesting
- **Scenario:** Client application RecruitX - internal recruitment portal

**Learning Objectives:**
- Web recon and directory enumeration
- Insecure Direct Object Reference (IDOR)
- Exploiting weak password reset logic
- Escalating to Admin panel
- Achieving Remote Code Execution (RCE) and reverse shell

**Tools Used:**
- Gobuster / Dirb
- Burp Suite
- curl
- Netcat (nc -lvnp)

**Key Takeaway:**
Real pentests are about chaining low/medium vulns. One IDOR led to account takeover, which led to admin access, which led to RCE. Not just finding one flag.

**Methodology (No Spoilers):**
Started with recon -> mapped application -> identified IDOR in application ID -> leveraged flawed password reset to take over hiring manager -> used admin upload feature to get shell -> upgraded to interactive reverse shell.

---

## 🎯 Next Targets
- [ ] OWASP Top 10
- [ ] Web Fundamentals Path
- [ ] Jr Penetration Tester Path

## 🛠️ Skills
`Web Pentesting` `IDOR` `Burp Suite` `RCE` `Linux` `Audit & IT Controls`
