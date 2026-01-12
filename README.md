# 🔓 Darkly

A web security CTF (Capture The Flag) project from 42 School. This project focuses on discovering and exploiting common web vulnerabilities in a controlled environment.

## 📋 Overview

Darkly is designed to teach web security fundamentals through hands-on exploitation of a vulnerable web application. The project covers 14 different security challenges, each targeting a specific vulnerability class.

## 👥 Authors

- orizhiy
- ioleksiu

## 🎯 Challenges

| # | Vulnerability | Description |
|---|---------------|-------------|
| 00 | **CSRF - Unsafe Redirection** | Cross-Site Request Forgery via unvalidated redirect parameter |
| 01 | **XSS - Password Recovery** | Cross-Site Scripting in password recovery form |
| 02 | **XSS - Cookie/Admin** | Cookie manipulation and admin access via XSS |
| 03 | **XSS - Invalid Vote** | Input validation bypass in voting system |
| 04 | **SQL Injection - Members** | SQL injection in member search functionality |
| 05 | **SQL Injection - Images** | SQL injection in image gallery |
| 06 | **XSS - Unprotected Include** | Local File Inclusion via unsanitized page parameter |
| 07 | **Unrestricted File Upload** | Bypassing file type validation to upload malicious files |
| 08 | **Directory Traversal** | Path traversal to access sensitive system files |
| 09 | **htaccess Bypass** | Authentication bypass via htaccess misconfiguration |
| 10 | **Web Crawler - Hidden Files** | Discovering hidden directories and sensitive data |
| 11 | **XSS - Feedback Form** | Input validation bypass in feedback form |
| 12 | **Login Bruteforce** | Credential enumeration via brute force attack |
| 13 | **XSS - HTTP Headers** | Exploiting User-Agent and Referer header validation |

## 🛠️ Vulnerabilities Covered

### Injection Attacks
- **SQL Injection**: Exploiting database queries to extract sensitive information
- **Command Injection**: Executing arbitrary system commands

### Cross-Site Scripting (XSS)
- Reflected XSS
- Stored XSS
- DOM-based XSS

### Authentication & Access Control
- Brute force attacks
- Session hijacking
- Cookie manipulation
- htaccess bypass

### File Operations
- Directory traversal (Path traversal)
- Unrestricted file upload
- Local File Inclusion (LFI)

### Other Vulnerabilities
- Cross-Site Request Forgery (CSRF)
- Open redirects
- Information disclosure
- HTTP header manipulation

## 📁 Project Structure

```
Darkly/
├── 00 - CSRF/
│   ├── flag              # Captured flag
│   └── Ressources/
│       └── answer        # Exploitation steps
├── 01 - XSS/
│   ├── flag
│   └── Ressources/
│       └── answer
├── ...
├── 13 - XSS Headers/
│   ├── flag
│   └── Ressources/
│       └── answer
├── author
├── en.subject.pdf        # Original project subject
└── README.md
```

## 🔧 Tools Used

- **curl** - Command-line HTTP client
- **Burp Suite** - Web vulnerability scanner and proxy
- **sqlmap** - Automated SQL injection tool
- **Python requests** - HTTP library for scripting
- **Browser Developer Tools** - DOM inspection and manipulation

## 🚀 Getting Started

1. Set up the vulnerable VM provided with the project
2. Note the IP address of the target machine
3. Navigate through each challenge directory
4. Read the `answer` file for exploitation methodology
5. Verify successful exploitation by comparing with the `flag` file

## ⚠️ Disclaimer

This project is for **educational purposes only**. The techniques demonstrated here should only be used in authorized environments. Always obtain proper permission before testing for vulnerabilities.

## 📚 Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [HackTheBox](https://www.hackthebox.eu/)

## 📝 License

This project is part of the 42 School curriculum.

---

*"With great power comes great responsibility"* 🕷️
