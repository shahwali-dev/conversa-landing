# 🛡️ Security Policy

We take the security of **Conversa Landing Page** and its open-source community ecosystem seriously. This document outlines our supported version boundaries, security update guarantees, and the proper disclosure compliance pipeline.

---

## 📦 Supported Product Versions

As a cutting-edge open-source frontend template running on top of production-grade dependencies, security patches are aggressively backported solely to the mainstream active deployment releases:

| Version | Supported Security Status | Notes |
| ------- | ------------------------- | ----- |
| **v1.x.x** | :white_check_mark: Active | Current stable version running Next.js 16 & React 19 Engine. |
| **< v1.0.0** | :x: Unsupported | Legacy development pre-releases. |

---

## ⚙️ Automated Dependency & Security Audits

To ensure zero injection footprint and keep the template at a hardened enterprise level, this repository undergoes continuous enforcement:

- **Strict pnpm Engine Constraints:** Using atomic package lock mechanisms to prevent dependency-drift or ghost package hijacking.
- **Automated Dependency Audits:** Integrated with GitHub Dependabot runtime pipelines to flag, isolate, and auto-patch underlying runtime vulnerabilities within the node package graphs (`pnpm audit`).

---

## 🚨 Reporting a Vulnerability

**Please do not open a public GitHub Issue for security bugs or sensitive vulnerabilities.** 

If you discover a security flaw, potential configuration exploit, or credential exposure vector within this landing page layout architecture, please report it via the safe, isolated channel:

1. **Private Email Disclosure:** Direct your vulnerability reports and technical reproduction steps confidentially to: **shahwali.dev@gmail.com**
2. **Evaluation Window:** Our team will review the issue and acknowledge receipt of your report within **24 to 48 hours**.
3. **Patch Execution:** If validated, an optimized security update will be prioritized, committed, and rolled out seamlessly into the `main` stable branch, with proper attribution credited to the discoverer.

Thank you for helping keep the open-source community secure! 🤝
