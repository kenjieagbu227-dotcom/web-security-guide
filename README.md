# 03 — Web Security Guide

**Learn common web application vulnerabilities and how developers prevent them.**

This repository focuses on the OWASP Top 10 and practical defensive coding practices.

---

## About

Web applications are frequent targets of attacks. Understanding vulnerabilities from a **defensive** perspective helps developers build more secure software.

---

## Learning Objectives

- Understand the OWASP Top 10
- Learn authentication and authorization security
- Understand injection vulnerabilities
- Learn XSS and CSRF concepts
- Understand API security
- Learn secure session management
- Understand file-upload and access-control risks
- Learn how to perform defensive code reviews

---

## Topics Covered

| Folder / Topic | Focus |
|----------------|-------|
| Authentication | Secure login systems |
| Authorization | Proper access control |
| Injection | SQL, command, and other injections |
| XSS | Cross-Site Scripting |
| CSRF | Cross-Site Request Forgery |
| File Upload | Secure file handling |
| Session Security | Cookies and session management |
| API Security | Protecting APIs |
| Security Headers | HTTP security headers |
| Logging & Monitoring | Detecting attacks |

---

## Structure of Each Topic

Every vulnerability follows this pattern:

1. What is it?
2. Why does it happen?
3. Safe demonstration (in controlled environments only)
4. How to detect it
5. How to fix it
6. How to prevent it

---

## Defensive Fixes

- Always perform **server-side authorization**
- Use **parameterized queries** / prepared statements
- Apply **context-aware output encoding**
- Implement **CSRF protection**
- Use **secure session cookies** (HttpOnly, Secure, SameSite)
- Validate and sanitize all input
- Set strong **security headers**
- Apply **rate limiting**
- Handle file uploads securely
- Keep dependencies updated

---

## Legal & Authorized Testing Notice

> Use only personal applications, authorized applications, CTFs, or deliberately vulnerable training environments (such as DVWA, Juice Shop, WebGoat, etc.).

---

## References

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [CWE](https://cwe.mitre.org)

---

## Disclaimer

Educational material only. Never test systems without explicit permission.

---

**Series:** Cybersecurity Learning Path  
**Previous:** [ethical-hacking-guide](https://github.com/kenjieagbu227-dotcom/ethical-hacking-guide)  
**Next:** [network-security-guide](https://github.com/kenjieagbu227-dotcom/network-security-guide)