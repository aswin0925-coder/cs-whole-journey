# Cybersecurity Operator Roadmap

## Phase 1 — OverTheWire Wargames

> Official order. Bandit is the gatekeeper; everything else assumes its skills.
> Connect via SSH: `ssh bandit0@bandit.labs.overthewire.org -p 2220` (password: `bandit0`)

| # | Wargame | Focus | Levels |
|---|---------|-------|--------|
| 1 | Bandit | Linux CLI, SSH, permissions, regex | 0–33 |
| 2a | Natas | Web security, SQLi, PHP | 0–34 |
| 2b | Krypton | Classical ciphers & crypto | 0–6 |
| 2c | Leviathan | SUID binaries, no code needed | 0–7 |
| 3 | Narnia | Binary exploitation intro (source provided) | 0–9 |
| 4 | Behemoth | Buffer overflows, race conditions, privesc | 0–8 |
| 5 | Utumno | Harder exploitation, shellcode | 0–8 |
| 6 | Maze | Exploitation + RE in gdb, minimal hints | 0–9 |
| 7 | Vortex | Socket programming → exploitation | 0–26 |
| 8 | Manpage / Drifter / FormulaOne | C pitfalls, heap exploitation, cross-game | varies |

**Tip:** Step 2 is "pick one" — do all three if you can. Natas is the highest-value for most careers.

---

## Phase 2 — Broader Hands-On (After OTW)

OTW gives depth in Linux + exploitation. Now you need breadth and realistic scenarios.

| Platform | What it adds | When |
|----------|-------------|------|
| TryHackMe | Guided paths: "Pre-Security" → "Jr Penetration Tester" or "SOC Level 1" | Immediately after OTW |
| Hack The Box | Unguided machines, harder, closer to real pentesting | After THM beginner paths |
| PortSwigger Web Security Academy | Deep web app security (Burp Suite, XSS, SSRF, etc.) | Parallel with Natas/THM |
| PicoCTF / CTFtime | Timed competition pressure, diverse categories | Once you can solve OTW without hints |

---

## Phase 3 — Certifications

### Order of attack:

1. **CompTIA Security+** — universal entry-level baseline.
   - Study: Professor Messer (free) or Jason Dion (Udemy)
   - Target: 85%+ on practice exams

2. **Track-specific second cert** (pick one):

   | Track | Cert |
   |-------|------|
   | SOC / Blue Team | CySA+ or SANS BTL1 |
   | Pentesting / Red Team | eJPT → OSCP |
   | Cloud Security | AWS Security Specialty or AZ-500 |
   | GRC / Compliance | CISA or ISO 27001 Lead Implementer |

3. **CISSP** — only after 4–5 years of experience.

---

## Phase 4 — Specialize & Build Proof (Months 6–12+)

Pick **one** track and go deep:

### SOC Analyst
- SIEM: Splunk / ELK
- MITRE ATT&CK framework
- Incident response playbooks
- Practice: LetsDefend, LogRhythm

### Penetration Tester
- Active Directory attacks
- Metasploit, reporting
- Crack 10+ HTB retired machines

### Cloud Security
- AWS/Azure IAM
- Misconfiguration detection
- Shared responsibility model

### AppSec / DevSecOps
- SAST/DAST: Semgrep, OWASP ZAP
- CI/CD pipeline security

### Portfolio (what actually gets you hired)
- [ ] GitHub repo with scripts, tool configs, and lab notes
- [ ] 3–5 public writeups (CTF solutions, HTB machines, bug bounty reports)
- [ ] Home lab: VirtualBox + Kali + Metasploitable or Active Directory

---

## Phase 5 — Get the Job (Month 10–18)

### Target first roles
- SOC Analyst L1 / Junior Security Analyst
- Cybersecurity Intern
- Junior Penetration Tester
- Cloud Security Associate

### Interview prep
- Networking & Linux questions (you'll crush these after OTW)
- "Walk me through how you'd investigate this alert" (SOC)
- "How would you exploit this / what's your methodology" (pentest)

---

## TL;DR Timeline

| Months | Milestone |
|--------|-----------|
| 1–3 | Finish all OTW wargames (Bandit → FormulaOne) |
| 3–6 | TryHackMe paths + PortSwigger + first CTFs |
| 4–8 | Study for and pass **Security+** |
| 6–12 | Pick a track, go deep, build portfolio, pass track cert |
| 12–18 | Apply, interview, **get hired** |

---

## Key Principle

> The single biggest mistake: spending too long on OTW's later games (Maze, Vortex, Drifter are genuinely hard with low career ROI). **Finish Bandit + Natas + Leviathan solidly, then move to TryHackMe and real-world tools.** Binary exploitation deep-dive is a differentiator but not a prerequisite for most first jobs.

---

## Resources

| Resource | URL |
|----------|-----|
| OverTheWire | overthewire.org |
| TryHackMe | tryhackme.com |
| Hack The Box | hackthebox.com |
| PortSwigger Academy | portswigger.net/web-security |
| PicoCTF | picoctf.org |
| CTFtime | ctftime.org |
| LetsDefend | letsdefend.io |
| Professor Messer (Sec+) | youtube.com/@ProfessorMesser |   
