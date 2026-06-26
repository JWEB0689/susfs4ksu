# Security Policy

## Supported Versions

We release security patches for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| latest   | ✅ Yes |
| previous | ✅ Security fixes only |
| < older | ❌ No longer supported |

## Reporting a Vulnerability

**Please do NOT report security vulnerabilities via public GitHub issues.**

Instead, please report them via:

- **Email**: security@jeremyweber.dev
- **GitHub Security Advisory**: [Report a vulnerability](https://github.com/JWEB0689/susfs4ksu/security/advisories/new)

We will acknowledge receipt within 48 hours and provide a more detailed response within 7 days.

## Disclosure Policy

- We follow [Coordinated Vulnerability Disclosure](https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure)
- We aim to patch critical vulnerabilities within 7 days
- We will credit reporters in the security advisory (unless anonymity requested)
- Public disclosure coordinated after fix is available

## Security Best Practices

### For Users

- Always use the latest stable release
- Verify signatures/checksums of downloads
- Keep dependencies updated
- Report suspicious behavior

### For Contributors

- Never commit secrets, keys, or tokens
- Run security scans before PR: `{{SECURITY_CMD}}`
- Follow secure coding practices for {{LANGUAGE}}
- Review dependencies for known vulnerabilities

## Security Features

Kernel-level VFS path redirection, SUSFS integration, bootloop guard, strategy fallback

## Audit History

| Date | Version | Type | Description |
|------|---------|------|-------------|
| 2026-06-26 | current | Code review | Initial security audit after CI hardening |

---

*Template based on rtk/odysseus security policies*