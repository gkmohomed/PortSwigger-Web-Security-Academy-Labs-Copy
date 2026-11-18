# PortSwigger Web Security Academy - Web Application Security Testing

A practical learning project documenting five completed **Apprentice-level** labs from PortSwigger Web Security Academy.

## Project overview

This project focused on recognizing common web application vulnerabilities, reviewing HTTP requests and responses, carrying out controlled tests in PortSwigger's intentionally vulnerable training environment, and documenting the potential impact and recommended mitigations.

**Scope:** All testing described here was performed only in PortSwigger Web Security Academy labs. No production systems or third-party websites were tested.

## Labs completed

| # | Lab | Vulnerability area | Status |
|---|---|---|---|
| 1 | SQL Injection Vulnerability in WHERE Clause Allowing Retrieval of Hidden Data | SQL Injection | Completed |
| 2 | Reflected XSS into HTML Context with Nothing Encoded | Cross-Site Scripting (XSS) | Completed |
| 3 | File Path Traversal, Simple Case | Path Traversal | Completed |
| 4 | Unprotected Admin Functionality | Broken Access Control / Security Misconfiguration | Completed |
| 5 | Information Disclosure in Error Messages | Information Disclosure / Security Misconfiguration | Completed |

## Tools and technologies

- Kali Linux
- PortSwigger Web Security Academy
- Burp Suite Community Edition
- Web browser

## Methodology

1. Open the selected PortSwigger lab and review its initial state.
2. Observe normal application behavior and relevant HTTP requests.
3. Inspect selected requests in Burp Suite where applicable.
4. Perform controlled tests that match the lab objective.
5. Review the application response and PortSwigger's completion status.
6. Record evidence and document impact, mitigations, and lessons learned.

## Repository structure

```text
.
├── README.md
├── PortSwigger_Web_Security_Academy_Project_Report.docx
├── PortSwigger_Web_Security_Academy_Project_Report.pdf
└── evidence/
    ├── 01-SQL-Injection/
    ├── 02-Reflected-XSS/
    ├── 03-Path-Traversal/
    ├── 04-Broken-Access-Control/
    └── 05-Information-Disclosure/
```

## Evidence

The `evidence/` directory contains screenshots from the original project report. They show initial lab pages, selected request analysis, and PortSwigger completion confirmations. Request/response detail panes in four Burp-related screenshots have been masked in this public-sharing copy to avoid exposing session-specific values.

## Key learning outcomes

- Understanding how user input can affect database query behavior.
- Recognizing reflected XSS caused by missing output encoding.
- Understanding risks associated with unsafe file path handling.
- Recognizing that hidden administrative URLs do not replace authorization.
- Understanding how verbose error messages can disclose technical information.
- Practicing HTTP request and response analysis with Burp Suite.
- Documenting potential impact and practical mitigation recommendations.

## References

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [SQL Injection lab](https://portswigger.net/web-security/sql-injection/lab-retrieve-hidden-data)
- [Reflected XSS lab](https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded)
- [Path Traversal lab](https://portswigger.net/web-security/file-path-traversal/lab-simple)
- [Unprotected Admin Functionality lab](https://portswigger.net/web-security/access-control/lab-unprotected-admin-functionality)
- [Information Disclosure in Error Messages lab](https://portswigger.net/web-security/information-disclosure/exploiting/lab-infoleak-in-error-messages)

---

**Author:** Mohamed Naasif  
**Project type:** Hands-on web application security lab practice
