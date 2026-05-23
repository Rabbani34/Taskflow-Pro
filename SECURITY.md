# 🔒 Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| 4.x     | ✅ Yes    |
| 3.x     | ⚠️ Critical fixes only |
| < 3.0   | ❌ No     |

---

## ⚠️ Known Security Considerations

TaskFlow Pro is a **client-side only** application. Please be aware:

1. **localStorage is not encrypted** — data is stored in plain text in the browser. Do not store highly sensitive information.
2. **Password hashing is client-side** — SHA-256 hashing happens in the browser. This protects against casual inspection but is not a substitute for server-side auth.
3. **No HTTPS enforcement** — when running locally from a file, there is no TLS. Use GitHub Pages or a proper host for HTTPS.
4. **AI API calls** — if you use the AI subtask feature, task text is sent to the Anthropic API. Do not use this feature with confidential task data.

---

## 🐛 Reporting a Vulnerability

If you discover a security vulnerability, please **do not open a public issue**.

Instead:
1. Email the maintainer directly (add your email here)
2. Or use GitHub's [private vulnerability reporting](../../security/advisories/new)

Include:
- A description of the vulnerability
- Steps to reproduce
- Potential impact
- Any suggested fixes

You will receive a response within **72 hours**. We appreciate responsible disclosure and will credit you in the fix's release notes.
