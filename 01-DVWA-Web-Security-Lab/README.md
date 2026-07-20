# DVWA Vulnerability Assessment

Lab penetration test write-up against DVWA (Damn Vulnerable Web Application), covering SQL Injection, XSS, and OS Command Injection.

**Author:** Abinesh Sivakumar
**Environment:** Kali Linux (attacker) + DVWA on Apache/MySQL (target), isolated VirtualBox/VMware host-only network
**Scope:** Self-hosted, intentionally vulnerable application — no external or production systems tested


## Findings

| # | Vulnerability | Severity | Status |
|---|---|---|---|
| 1 | SQL Injection | High | Reproduced & documented |
| 2 | Cross-Site Scripting (XSS) | Medium | Reproduced & documented |
| 3 | OS Command Injection | Critical | Reproduced & documented |

## Methodology

Recon → Exploitation → Proof-of-Concept → Remediation

## Disclaimer

All testing was performed exclusively against a self-hosted, intentionally vulnerable lab application (DVWA) for educational purposes only.
