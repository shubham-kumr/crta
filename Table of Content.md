
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