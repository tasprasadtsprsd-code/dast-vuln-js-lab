# JavaScript DAST Vulnerability Lab

A self-contained HTML page with **8 live client-side vulnerabilities** and inline remediation — built for practicing DAST scanners (OWASP ZAP, Burp Suite, Nikto) against known flaws, then fixing them.

> ⚠️ **For authorized local security testing only.** Never deploy on a public server with real users.

## Live demo

👉 [Open the lab](https://tasprasadtsprsd-code.github.io/dast-vuln-js-lab/)

## Vulnerabilities covered

| # | Vulnerability | Severity |
|---|---|---|
| 1 | Reflected XSS via `innerHTML` | Critical |
| 2 | Stored XSS via localStorage | Critical |
| 3 | Open redirect (?next= parameter) | High |
| 4 | Client-side SQL injection | High |
| 5 | IDOR — broken access control | High |
| 6 | CSRF — no token on mutations | Medium |
| 7 | Sensitive data in localStorage | High |
| 8 | Missing security headers | Medium |

## How to use

1. Open `index.html` in a browser (or use the GitHub Pages link above)
2. Click any vulnerability card to expand it
3. Try the **Live demo** tab — payloads are suggested in the hints
4. Switch to the **Remediation** tab to see the secure code fix
5. Point OWASP ZAP at the GitHub Pages URL and compare scanner findings to the known list

## Suggested DAST workflow

```
Scan → Reproduce manually → Apply fix → Re-scan → Confirm finding disappears
```

## Stack

Pure HTML + vanilla JavaScript. No build step, no dependencies, no server required.
