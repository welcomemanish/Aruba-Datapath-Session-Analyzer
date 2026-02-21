# Security Policy

## Supported Versions

| Version | Supported |
|---|---|
| Version 1 (Feb 2026) | ✅ Active |

---

## Reporting a Vulnerability

This project is a **client-side only, single HTML file** — it processes log files entirely within your browser. No data is transmitted to any server, and there is no backend, database, or authentication system.

However, if you discover a security concern (for example, a vulnerability in how the file parses log content, or a potential XSS issue), please **do not open a public GitHub issue**.

Instead, report it privately by contacting the maintainer directly:

**GitHub:** [@welcomemanish](https://github.com/welcomemanish)

Please include:
- A clear description of the vulnerability
- Steps to reproduce it
- The potential impact
- Any suggested fix if you have one

You can expect an acknowledgement within **7 days** and a resolution or update within **30 days** depending on severity.

---

## Security Notes for Users

- Your `tech-support.log` file is **never uploaded anywhere** — all parsing happens locally in your browser
- No cookies are set except `localStorage` for theme preference
- The only external resources loaded are **Chart.js** (cdnjs.cloudflare.com) and **Google Fonts** — both over HTTPS
- If you are in a sensitive/air-gapped environment, you can download Chart.js and the fonts locally and update the HTML file to reference local copies
