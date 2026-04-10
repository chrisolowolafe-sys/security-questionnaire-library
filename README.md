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
- **Evidence Tips** — suggested evidence artifacts for each response
- **Export to JSON** — full library export
- **Print-optimized** — all responses visible for PDF printing
- **Light/dark mode** — persisted via localStorage

---

## Response Categories

| Category | Responses | Key Topics |
|---|---|---|
| Data Security | 5 | Encryption at rest/transit, classification, retention, DLP |
| Access Controls | 5 | Provisioning, MFA, privileged access, UARs, SoD |
| Incident Response | 4 | IRP, breach notification, SIEM, post-incident reviews |
| Vulnerability Management | 3 | Vuln scanning, penetration testing, patch management |
| Business Continuity | 3 | BCP/DRP, RTO/RPO, backup and restoration |
| Third-Party Risk | 3 | TPRM, DPAs, sub-processor register |
| Compliance & Certifications | 4 | ISO 27001, SOC 2, GDPR, PIPEDA compliance |
| Security Governance | 4 | InfoSec policy, governance, risk assessments, training |
| Privacy | 3 | DSARs, DPIAs, Privacy by Design |

---

## Framework Coverage

| Framework | Version | Controls Referenced |
|---|---|---|
| ISO 27001 | 2022 | A.5.x, A.6.x, A.7.x, A.8.x, Cl.6.x |
| SOC 2 Type II | AICPA TSC 2017 | CC1–CC9, A1, C1 |
| NIST CSF | 2.0 | GV, ID, PR, DE, RS, RC functions |
| GDPR | 2018 | Art. 5, 6, 13, 24, 25, 28, 30, 33, 34, 35 |
| PIPEDA | Current | Principles 1–10, Breach Regulations |

---

## Security Architecture

| Header | Value |
|---|---|
| `X-Frame-Options` | `DENY` |
| `X-Content-Type-Options` | `nosniff` |
| `Referrer-Policy` | `strict-origin-when-cross-origin` |
| `Strict-Transport-Security` | `max-age=63072000; includeSubDomains; preload` |
| `Content-Security-Policy` | Strict allowlist — no CDN dependencies |
| `Permissions-Policy` | Geolocation, microphone, camera, payment denied |

Additional: HTTPS enforcement, GitHub Pages redirect, XSS prevention, localStorage try/catch, prefers-reduced-motion, no cookies, no tracking, no analytics. Note: No Chart.js dependency in this tool — no CDN scripts required.

---

## Repository Structure

```
security-questionnaire-library/
├── index.html    ← Full application (no external JS dependencies)
├── _headers      ← Cloudflare security headers
└── README.md     ← This file
```

---

## Part of the GRC Portfolio

| Project | Status |
|---|---|
| [ShomriTech GRC Platform](https://chris-olowo-grc-portfolio.pages.dev/grc-platform) | ✅ Live |
| [Vendor Risk Assessment Tool](https://vendor-risk-assessment-tool.chrisolowolafe.workers.dev) | ✅ Live |
| [User Access Review Tracker](https://user-access-review-tracker.chrisolowolafe.workers.dev) | ✅ Live |
| [SOC 2 Evidence Tracker](https://soc2-evidence-tracker.chrisolowolafe.workers.dev) | ✅ Live |
| [NIST AI RMF Gap Assessment](https://nist-ai-rmf-assessment.chrisolowolafe.workers.dev) | ✅ Live |
| **Security Questionnaire Library** *(this repo)* | ✅ Live |

---

## Author

**Chris Olowo, PMP®**  
GRC Analyst & Risk Practitioner · Calgary, Canada  
ISO 27001 Lead Auditor · NIST CSF 2.0 · ISO 42001 · GRC · PrivacyOps · PMP®

[Portfolio](https://chris-olowo-grc-portfolio.pages.dev) · [LinkedIn](https://www.linkedin.com/in/chris-o-742316135)

---

*Responses are illustrative and should be customized to reflect your organization's actual controls. For demonstration and educational purposes only. Not legal or compliance advice.*
