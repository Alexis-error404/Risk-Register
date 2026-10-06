# Cybersecurity Risk Register

| ID | Risk Statement | L | I | Inherent | NIST | Treatment | Owner | Residual | Status |
|---|---|---:|---:|---:|---|---|---|---:|---|
| R-001 | Password-only privileged authentication could enable administrative compromise. | 4 | 5 | 20 Critical | IA-2 | Mitigate | IAM/Security | 10 High | Open |
| R-002 | Excessive privileged access could enable unauthorized changes if an account is misused/compromised. | 3 | 5 | 15 Critical | AC-6 | Mitigate | IT Ops | 8 Moderate | In Progress |
| R-003 | Delayed critical patching could allow exploitation and operational/data impact. | 4 | 5 | 20 Critical | SI-2 | Mitigate | IT Ops | 8 Moderate | Open |
| R-004 | Inconsistent log review could allow malicious activity to remain undetected. | 4 | 4 | 16 Critical | AU-6 | Mitigate | SecOps | 8 Moderate | Open |
| R-005 | A critical vendor compromise could expose organizational data/services. | 3 | 5 | 15 Critical | SR family | Mitigate/Transfer | Vendor Mgmt | 10 High | Open |
| R-006 | Successful phishing could result in credential theft, fraud, or data exposure. | 4 | 5 | 20 Critical | AT-2/IA-2 | Mitigate | Security | 10 High | In Progress |
| R-007 | Untested backups could fail during ransomware/system failure and extend downtime. | 3 | 5 | 15 Critical | CP-9/CP-10 | Mitigate | Infrastructure | 6 Moderate | Open |
| R-008 | Unsupported systems could retain exploitable known vulnerabilities. | 3 | 4 | 12 High | SI-2/CM-8 | Avoid/Mitigate | IT Ops | 4 Low | Open |
| R-009 | Cloud misconfiguration could expose data/services to unauthorized parties. | 3 | 5 | 15 Critical | AC/CM | Mitigate | Cloud Owner | 8 Moderate | Open |
| R-010 | Untested incident procedures could cause delayed/inconsistent response. | 3 | 4 | 12 High | IR-3/IR-4 | Mitigate | Security Lead | 6 Moderate | Open |

## Risk Statement Formula
**If [condition], then [event] could occur, resulting in [business impact].**

A good register communicates why the issue matters, not merely the technical weakness.
