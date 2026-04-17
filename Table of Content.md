# CRTA - Certified Red Team Analyst Syllabus

1. Introduction to Web App Pentesting
    - Web Applications Basics
    - OWASP Top 10
    - WSTG
2. Tools
    - Burp Suite
        - Proxy, Intruder, Repeater
    - Nuclei
        - Templates
3. Recon & Discovery
    - OSINT
        - Fingerprinting (Passive, Active)
        - DNS, Subdomains, WHOIS, Google Dorking
    - Fuzzing (FFUF)
4. WAF Bypass
    - Header Manipulation
    - CORS, CSP, SOP
5. Injection Attacks
    - SQL Injection
        - Error, Union, Boolean, Time-based
    - XXE
        - Classic, Error, Blind    
    - Command Injection
    - SSTI
    - NoSQL Injection
    - GraphQL Injection
6. Auth & Access Attacks
    - Brute Force
    - Session Attacks
        - Fixation, Poisoning, Cookies
    - IDOR
        - Horizontal, Vertical
    - OAuth Attacks
    - JWT Attacks
7. Other Attacks
    - Insecure Deserialization
    - SSRF
    - File Inclusion (LFI/RFI)
    - Path Traversal
    - Prototype Pollution
    - File Upload Bypass
8. Chained Attacks
    - LFI → RCE
    - SQLi → XXE → RCE
    - JWT → SSRF
    - Session → SSTI → RCE
    - OAuth → Account Takeover → RCE

# Practice Labs

| Platform / Category                            | Key free labs / paths / series (for CRTA‑style skills)                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **OverTheWire**                                | - **Bandit** – Linux privilege escalation, basic Linux security, file‑perms, shell usage. [detectx.com](https://www.detectx.com.au/free-labs-to-test-your-redteam-blueteam-and-ctf-skills/)  <br>- **Natas** – Web‑app CTFs (auth, XSS‑style, basic logic flaws). [detectx.com](https://www.detectx.com.au/free-labs-to-test-your-redteam-blueteam-and-ctf-skills/)                                                                                                                                                       |
| **PortSwigger Academy**                        | - **SQL injection** – 16 labs (classic, boolean, time‑based, auth bypass). github+1  <br>- **XSS** – 30 labs (reflected, stored, DOM‑based). [github](https://github.com/michelbernardods/labs-pentest)  <br>- **CSRF, XXE, SSRF, Command Injection, Path Traversal, Access Control, JWT, API, Web‑LLM** – all labs in Web Security Academy. github+1                                                                                                                                                                     |
| **DVWA (Damn Vulnerable Web App)**             | - Self‑hosted: **SQL injection, XSS, Command Injection, File Inclusion (LFI/RFI), CSRF, Brute‑force, Login bypass**. detectx.com+1                                                                                                                                                                                                                                                                                                                                                                                        |
| **TryHackMe**                                  | - **Red Teaming** path – 36 rooms: recon, initial access, post‑compromise, pivoting, AD attacks, evasion. tryhackme+1  <br>- **Web Application Red Teaming** path – 23 advanced web‑app exploit‑chain rooms. [tryhackme](https://tryhackme.com/path/outline/webappredteaming)  <br>- **Wreath, Attacktive Directory, Breaching AD, Vulnnet Roasted, VulnNet domain series, Juicy Details, Injection, LFI Basics, OWASP Mutillidae II, WebGOAT, DVWA room** – AD‑focused and web‑app‑focused rooms. phyothuraoo.substack+2 |
| **Hack The Box (HTB – free tier)**             | - **Active Directory 101** – AD fundamentals, enumeration, basic attacks. [detectx.com](https://www.detectx.com.au/free-labs-to-test-your-redteam-blueteam-and-ctf-skills/)[youtube](https://www.youtube.com/watch?v=Fpo5x8iW5DY)  <br>- **Machine(s) focused on Windows/AD** (e.g., `Active`, `Forest`, `Resolute`, `Legacy`, etc.) – chosen from free tier. [detectx.com](https://www.detectx.com.au/free-labs-to-test-your-redteam-blueteam-and-ctf-skills/)[youtube](https://www.youtube.com/watch?v=Fpo5x8iW5DY)     |
| **VulnHub**                                    | - Self‑hosted VMs: **AD‑heavy labs** such as `hti`, `devilbox`, `Bulldog`, and other AD‑oriented OVA images (search for “AD”/“domain”‑branded VMs). detectx.com+1                                                                                                                                                                                                                                                                                                                                                         |
| **ImmersiveLabs**                              | - **Free‑tier labs** (if available): incident‑response‑style, CTF‑style, web‑app, and OS‑level forensics / exploit labs. detectx.com+1                                                                                                                                                                                                                                                                                                                                                                                    |
| **Practical Pentest Labs / Exploit‑Education** | - **Protostar, Nebula, Fawn, Fusion** – binary exploitation, stack overflows, format‑string, and memory‑corruption labs. detectx.com+1                                                                                                                                                                                                                                                                                                                                                                                    |
| **CryptoHack**                                 | - **Crypto‑oriented CTFs**: hash‑collisions, RSA, AES‑CBC/CTR, XOR, Shamir sharing, discrete‑log, etc. (good for breaking crypto in challenges). detectx.com+1                                                                                                                                                                                                                                                                                                                                                            |
| **CMD Challenge (cmdchallenge.com)**           | - **Command‑line challenges**: common Linux shell‑puzzles (grep, awk, sed, pipes) useful for quick‑enumeration‑style practice. detectx.com+1                                                                                                                                                                                                                                                                                                                                                                              |
