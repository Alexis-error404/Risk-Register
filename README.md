# Cybersecurity Risk Register

A cybersecurity risk register for a fictional enterprise environment, covering risk identification, analysis, control mapping, treatment, ownership, remediation, and residual risk.

> **Scope note:** The organization, risks, ratings, owners, and treatment decisions in this repository are fictional and are used to model a structured cybersecurity risk-management process.

## Environment
The modeled organization uses Active Directory, cloud services, remote access, endpoints, third-party vendors, and centralized IT services.

## Risk Method
**Risk Score = Likelihood × Impact**, using 1–5 scales.

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–14 | High |
| 15–25 | Critical |

## Risk Summary
| ID | Risk | Inherent | Treatment | Target Residual |
|---|---|---:|---|---:|
| R-001 | Privileged account compromise without MFA | 20 Critical | Mitigate | 10 High |
| R-002 | Excessive privileged access | 15 Critical | Mitigate | 8 Moderate |
| R-003 | Unpatched critical vulnerabilities | 20 Critical | Mitigate | 8 Moderate |
| R-004 | Insufficient security-log monitoring | 16 Critical | Mitigate | 8 Moderate |
| R-005 | Third-party compromise | 15 Critical | Mitigate / Transfer | 10 High |
| R-006 | Phishing-driven credential theft | 20 Critical | Mitigate | 10 High |
| R-007 | Backup recovery failure | 15 Critical | Mitigate | 6 Moderate |
| R-008 | Unsupported systems | 12 High | Avoid / Mitigate | 4 Low |
| R-009 | Cloud misconfiguration | 15 Critical | Mitigate | 8 Moderate |
| R-010 | Untested incident response | 12 High | Mitigate | 6 Moderate |

## Repository Artifacts
- `register/risk-register.md` — detailed cybersecurity risk register
- `methodology/risk-methodology.md` — likelihood, impact, scoring, and treatment methodology
- `analysis/risk-treatment-plan.md` — prioritized corrective actions
- `analysis/executive-summary.md` — consolidated risk posture and priorities

## Risk Management Areas
Risk identification · likelihood and impact analysis · inherent risk · residual risk · NIST control mapping · risk treatment · risk ownership · third-party risk · remediation tracking · executive risk reporting
