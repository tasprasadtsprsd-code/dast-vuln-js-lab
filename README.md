# EduVuln Academy — OWASP Top 10 Student Lab

A 10-page student security education website covering every OWASP Top 10 (2021) vulnerability category with **live exploitable demos** and **inline remediation code**.

> ⚠️ **For authorized educational use only.** All demos are in-memory. Never deploy with real users or data.

## 🔴 Live Site
👉 **https://tasprasadtsprsd-code.github.io/dast-vuln-js-lab/**

## 📚 Pages

| Page | OWASP Category | Severity |
|------|----------------|----------|
| [Home](index.html) | Overview & navigation | — |
| [A01](a01-broken-access.html) | Broken Access Control | 🔴 Critical |
| [A02](a02-crypto.html) | Cryptographic Failures | 🔴 Critical |
| [A03](a03-injection.html) | Injection (XSS + SQLi) | 🔴 Critical |
| [A04](a04-insecure-design.html) | Insecure Design | 🟠 High |
| [A05](a05-security-misc.html) | Security Misconfiguration | 🟠 High |
| [A06](a06-vuln-components.html) | Vulnerable Components | 🟠 High |
| [A07](a07-auth-failures.html) | Auth Failures | 🔴 Critical |
| [A08](a08-integrity.html) | Software Integrity Failures | 🟠 High |
| [A09](a09-logging.html) | Logging Failures | 🟡 Medium |
| [A10](a10-ssrf.html) | SSRF | 🔴 Critical |

## 🧪 How to use

1. Open any page and click a vulnerability card
2. **Vulnerable demo tab** — trigger the flaw yourself with the suggested payload
3. **Remediation tab** — see the secure code fix
4. Point **OWASP ZAP** at the GitHub Pages URL and compare scanner findings to the known list
5. Apply fixes and re-scan to confirm findings disappear

## 🛠 Stack

Pure HTML + vanilla JavaScript. No build step, no framework, no server required. Open `index.html` locally or use the GitHub Pages link.
