# 🔐 Security Policy – Paichal Calculator

## 🐂 About This Project
Paichal Calculator is a public open-source platform designed to digitize traditional
Eruthu Vidum Vizha (Bull Race) events across Tamil Nadu. The application manages
race timing, results, finances, and event data for village committees and bull owners.

Because this platform handles real event data and public verification systems,
security, fairness, and responsible disclosure are extremely important.

---

## ✅ Supported Versions

We actively maintain and provide security updates for the following versions:

| Version | Supported |
|---------|-----------|
| Latest Release | ✅ Yes |
| Previous Major Version | ⚠️ Limited Support |
| Older Releases | ❌ No |

Users are strongly encouraged to upgrade to the latest stable release.

---

## 🚨 Reporting a Vulnerability

If you discover a security issue, please **DO NOT open a public GitHub issue**.

Instead, report responsibly using one of the following methods:

📧 Email: security@paichal.app  
📩 GitHub Private Advisory: Use GitHub Security Advisories  
📄 Include:
- Description of the vulnerability
- Steps to reproduce
- Screenshots or proof-of-concept (if available)
- Affected version
- Possible impact

We aim to respond within **72 hours**.

---

## 🤝 Responsible Disclosure Guidelines

We request that security researchers:

- Do NOT publicly disclose vulnerabilities before a fix is released
- Avoid accessing private event or personal data
- Avoid modifying production data
- Avoid disrupting live village events or competitions
- Test only on local/dev environments whenever possible

We will credit responsible reporters (if requested).

---

## 🔒 Security Scope

Security areas relevant to this project include:

### 📊 Event Data & Race Results
- Timing accuracy
- Result integrity
- Leaderboard manipulation prevention

### 🧾 Document Verification
- QR-based certificate validation
- Tamper-proof result PDFs

### 👥 Authentication & Accounts
- Firebase Authentication
- Organizer access control
- Role-based permissions

### 🌐 Web Verification Portal
- Public certificate verification
- Input validation
- Data exposure prevention

### 📦 Offline Data Sync
- Secure local storage
- Safe sync conflict handling

---

## 🔐 Best Practices for Contributors

When contributing code:

- Never commit API keys or Firebase secrets
- Use environment variables
- Validate all user input
- Avoid storing sensitive personal information
- Follow Flutter secure coding practices
- Review dependencies for known vulnerabilities

---

## ⚠️ Known Non-Security Issues

The following are NOT considered security vulnerabilities:

- UI bugs
- Performance issues
- Feature requests
- Styling improvements
- Non-sensitive data inconsistencies

Please use normal GitHub Issues for these.

---

## 🛡️ Legal & Ethical Notice

Paichal supports traditional cultural events.  
Contributors and users must:

- Respect local laws and animal welfare regulations
- Avoid using the software for illegal activities
- Avoid manipulating race outcomes or financial data

---

## 🙏 Acknowledgement

We appreciate the open-source community for helping keep Paichal safe,
fair, and trustworthy for village committees and bull owners across Tamil Nadu.

---

**Maintained by:** Paichal Tech  
**Project Repository:** https://github.com/bhktools/Paichal_App_Public
