# Security Questionnaire Response Library

**Live Demo:** [security-questionnaire-library.chrisolowolafe.workers.dev](https://security-questionnaire-library.chrisolowolafe.workers.dev)  
**Built by:** [Chris Olowo, PMP®](https://chris-olowo-grc-portfolio.pages.dev) — GRC Analyst & Risk Practitioner

---

## Overview

A structured library of 30+ pre-written, audit-quality responses to the most common enterprise security questionnaire categories. Every response maps to ISO 27001:2022, SOC 2 Type II, NIST CSF 2.0, GDPR, and PIPEDA controls. Includes evidence suggestions for each response. Search, filter by category and framework, and copy responses instantly.

---

## Features

- **30+ pre-written responses** across 9 security domains
- **Framework filter** — ISO 27001, SOC 2, NIST CSF, GDPR, PIPEDA
- **Category filter** — 9 security domains
- **Full-text search** across questions, responses, and controls
- **One-click copy** — copies question + response + controls to clipboard
- **Evidence Tips** — suggested evidence artifacts per response
- **Export to JSON** — full library export
- **Print-optimized** — all responses visible for PDF printing
- **No external JS dependencies** — lightest and most secure of the five tools

---

## Response Categories

| Category | Key Topics |
|---|---|
| Data Security | Encryption, classification, retention, DLP |
| Access Controls | Provisioning, MFA, privileged access, UARs, SoD |
| Incident Response | IRP, breach notification, SIEM, post-incident reviews |
| Vulnerability Management | Scanning, penetration testing, patch management |
| Business Continuity | BCP/DRP, RTO/RPO, backup and restoration |
| Third-Party Risk | TPRM, DPAs, sub-processor register |
| Compliance & Certifications | ISO 27001, SOC 2, GDPR, PIPEDA |
| Security Governance | InfoSec policy, governance, risk assessments, training |
| Privacy | DSARs, DPIAs, Privacy by Design |

---

## Framework Coverage

| Framework | Controls Referenced |
|---|---|
| ISO 27001 | A.5.x, A.6.x, A.7.x, A.8.x, Cl.6.x |
| SOC 2 Type II | CC1–CC9, A1, C1 |
| NIST CSF 2.0 | GV, ID, PR, DE, RS, RC functions |
| GDPR | Art. 5, 6, 13, 24, 25, 28, 30, 33, 34, 35 |
| PIPEDA | Principles 1–10, Breach Regulations |

---

## Security Architecture

All security headers enforced server-side via Cloudflare `_headers`. No CDN script dependencies — strictest CSP of all five tools. Additional: HTTPS enforcement, GitHub Pages redirect, XSS prevention, localStorage try/catch, prefers-reduced-motion, no tracking.

---

## Repository Structure

```
security-questionnaire-library/
├── index.html    ← Full application (no external JS)
├── _headers      ← Cloudflare security headers
└── README.md     ← This file
```

---

## Complete GRC Portfolio

| Project | Live URL |
|---|---|
| 🏠 ShomriTech GRC Platform | [chris-olowo-grc-portfolio.pages.dev](https://chris-olowo-grc-portfolio.pages.dev) |
| 1️⃣ Vendor Risk Assessment Tool | [vendor-risk-assessment-tool.chrisolowolafe.workers.dev](https://vendor-risk-assessment-tool.chrisolowolafe.workers.dev) |
| 2️⃣ User Access Review Tracker | [user-access-review-tracker.chrisolowolafe.workers.dev](https://user-access-review-tracker.chrisolowolafe.workers.dev) |
| 3️⃣ SOC 2 Evidence Tracker | [soc2-evidence-tracker.chrisolowolafe.workers.dev](https://soc2-evidence-tracker.chrisolowolafe.workers.dev) |
| 4️⃣ NIST AI RMF Gap Assessment | [nist-ai-rmf-assessment.chrisolowolafe.workers.dev](https://nist-ai-rmf-assessment.chrisolowolafe.workers.dev) |
| 5️⃣ **Security Questionnaire Library** *(this repo)* | [security-questionnaire-library.chrisolowolafe.workers.dev](https://security-questionnaire-library.chrisolowolafe.workers.dev) |

---

## Author

**Chris Olowo, PMP®**  
GRC Analyst & Risk Practitioner · Calgary, Canada  
ISO 27001 Lead Auditor · NIST CSF 2.0 · ISO 42001 · GRC · PrivacyOps · PMP®

*Pro bono ISO 42001 AI governance consulting provided to non-profit organizations in Calgary.*

[Portfolio](https://chris-olowo-grc-portfolio.pages.dev) · [LinkedIn](https://www.linkedin.com/in/chris-o-742316135) · [GitHub](https://github.com/chrisolowolafe-sys)

---

*Responses are illustrative and should be customized to reflect your organization's actual controls. For demonstration and educational purposes only.*
