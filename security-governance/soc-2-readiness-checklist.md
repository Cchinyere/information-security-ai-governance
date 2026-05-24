# SOC 2 Readiness Checklist

## 1. Document Control

| Field | Details |
|---|---|
| Organisation |  |
| Service / Product Scope |  |
| Assessment Date |  |
| Assessor |  |
| Version | 1.0 |
| Review Status | Draft / Reviewed / Approved |

---

## 2. Purpose

This checklist supports SOC 2 readiness preparation by helping organisations assess the design and evidence of controls aligned with the Trust Services Categories.

This checklist is for readiness planning and does not replace auditor judgement, formal SOC 2 scoping, or the official Trust Services Criteria.

---

## 3. SOC 2 Scope

| Area | Details |
|---|---|
| Service or System in Scope |  |
| Trust Services Categories in Scope | Security / Availability / Confidentiality / Processing Integrity / Privacy |
| Locations in Scope |  |
| Infrastructure in Scope | Cloud / On-premise / Hybrid / SaaS |
| Key Applications |  |
| Key Third Parties |  |
| Reporting Period |  |
| Type of Report | Type I / Type II |

---

## 4. Readiness Rating

| Rating | Definition |
|---|---|
| Ready | Control is designed, implemented, documented, and supported by evidence. |
| Partially Ready | Control exists but requires improvement, consistency, testing, or stronger evidence. |
| Not Ready | Control is missing, undocumented, ineffective, or unsupported by evidence. |
| Not Applicable | Control area is outside the agreed SOC 2 scope. |

---

## 5. Security Checklist

| Control Area | Readiness Question | Status | Evidence Required | Gap / Action | Owner |
|---|---|---|---|---|---|
| Governance | Are security roles, responsibilities, and accountability clearly defined? | Ready / Partial / Not Ready / N/A | Security policy, RACI, governance minutes |  |  |
| Risk Management | Is there a documented risk assessment and treatment process? | Ready / Partial / Not Ready / N/A | Risk register, risk methodology, treatment plan |  |  |
| Policies | Are security policies approved, communicated, and reviewed periodically? | Ready / Partial / Not Ready / N/A | Policy set, approval records, review history |  |  |
| Access Control | Are user access rights approved, reviewed, and removed when no longer required? | Ready / Partial / Not Ready / N/A | Access review records, joiner-mover-leaver evidence |  |  |
| Privileged Access | Is privileged access restricted, approved, monitored, and periodically reviewed? | Ready / Partial / Not Ready / N/A | Privileged access list, approvals, review logs |  |  |
| Authentication | Are strong authentication controls implemented for key systems? | Ready / Partial / Not Ready / N/A | MFA configuration, identity policy |  |  |
| Change Management | Are system changes authorised, tested, approved, and documented? | Ready / Partial / Not Ready / N/A | Change tickets, approvals, test evidence |  |  |
| Vulnerability Management | Are vulnerabilities identified, prioritised, remediated, and tracked? | Ready / Partial / Not Ready / N/A | Scan results, remediation tickets, exception records |  |  |
| Logging and Monitoring | Are security logs collected, reviewed, and escalated where appropriate? | Ready / Partial / Not Ready / N/A | SIEM logs, alert triage records, escalation evidence |  |  |
| Incident Response | Is there a documented and tested incident response process? | Ready / Partial / Not Ready / N/A | IR plan, test reports, incident tickets |  |  |
| Vendor Risk | Are third-party security risks assessed and monitored? | Ready / Partial / Not Ready / N/A | Supplier assessments, contracts, due diligence |  |  |
| Security Awareness | Are employees trained on security responsibilities? | Ready / Partial / Not Ready / N/A | Training records, awareness materials |  |  |

---

## 6. Availability Checklist

| Control Area | Readiness Question | Status | Evidence Required | Gap / Action | Owner |
|---|---|---|---|---|---|
| Availability Commitments | Are availability commitments defined and monitored? | Ready / Partial / Not Ready / N/A | SLA/SLO documents, reporting dashboards |  |  |
| Capacity Management | Is system capacity monitored and managed? | Ready / Partial / Not Ready / N/A | Capacity reports, monitoring alerts |  |  |
| Backup and Recovery | Are backups performed, monitored, and periodically tested? | Ready / Partial / Not Ready / N/A | Backup logs, restore test evidence |  |  |
| Business Continuity | Is business continuity planning documented and tested? | Ready / Partial / Not Ready / N/A | BCP, test results, action logs |  |  |
| Disaster Recovery | Is disaster recovery defined, tested, and aligned to recovery objectives? | Ready / Partial / Not Ready / N/A | DR plan, RTO/RPO, test evidence |  |  |

---

## 7. Confidentiality Checklist

| Control Area | Readiness Question | Status | Evidence Required | Gap / Action | Owner |
|---|---|---|---|---|---|
| Data Classification | Is confidential data identified and classified? | Ready / Partial / Not Ready / N/A | Data classification standard, data inventory |  |  |
| Data Handling | Are handling requirements defined for confidential information? | Ready / Partial / Not Ready / N/A | Handling procedures, training records |  |  |
| Encryption | Is confidential data protected in transit and at rest where appropriate? | Ready / Partial / Not Ready / N/A | Encryption configuration, architecture evidence |  |  |
| Data Retention | Are retention and disposal requirements defined and followed? | Ready / Partial / Not Ready / N/A | Retention schedule, disposal records |  |  |
| Data Loss Prevention | Are controls in place to reduce unauthorised disclosure? | Ready / Partial / Not Ready / N/A | DLP policy, alerts, exception records |  |  |

---

## 8. Processing Integrity Checklist

| Control Area | Readiness Question | Status | Evidence Required | Gap / Action | Owner |
|---|---|---|---|---|---|
| Processing Requirements | Are processing requirements documented and approved? | Ready / Partial / Not Ready / N/A | Requirements documentation, approvals |  |  |
| Input Controls | Are data inputs validated for completeness and accuracy? | Ready / Partial / Not Ready / N/A | Validation rules, test evidence |  |  |
| Processing Controls | Are processing errors detected, logged, and resolved? | Ready / Partial / Not Ready / N/A | Error logs, reconciliation evidence |  |  |
| Output Controls | Are outputs reviewed or reconciled where required? | Ready / Partial / Not Ready / N/A | Output review records, reconciliation logs |  |  |

---

## 9. Privacy Checklist

| Control Area | Readiness Question | Status | Evidence Required | Gap / Action | Owner |
|---|---|---|---|---|---|
| Privacy Notice | Are privacy notices accurate, accessible, and aligned to processing activities? | Ready / Partial / Not Ready / N/A | Privacy notice, review record |  |  |
| Personal Data Inventory | Is personal data identified and mapped? | Ready / Partial / Not Ready / N/A | Data inventory, data flow maps |  |  |
| Consent / Lawful Basis | Is the basis for processing personal data documented where applicable? | Ready / Partial / Not Ready / N/A | Privacy assessment, consent records |  |  |
| Data Subject Rights | Are requests from individuals managed through a defined process? | Ready / Partial / Not Ready / N/A | DSAR procedure, request log |  |  |
| Privacy Incidents | Are privacy incidents identified, escalated, and managed? | Ready / Partial / Not Ready / N/A | Incident logs, breach assessment records |  |  |

---

## 10. Evidence Tracker

| Evidence ID | Evidence Name | Control Area | Owner | Evidence Location | Frequency | Status | Notes |
|---|---|---|---|---|---|---|---|
| SOC2-EV-001 | Security Policy | Governance |  |  | Annual | Missing / Partial / Complete |  |

---

## 11. Readiness Action Plan

| Action ID | Gap | Recommended Action | Priority | Owner | Due Date | Evidence Required | Status |
|---|---|---|---|---|---|---|---|
| SOC2-001 |  |  | High / Medium / Low |  |  |  | Open / In Progress / Closed |

---

## 12. Management Summary

### Overall Readiness

- 

### Key Strengths

- 

### Key Gaps

- 

### Priority Remediation Actions

1. 
2. 
3. 

---

## 13. Assumptions and Limitations

- This checklist is a readiness aid, not a SOC 2 audit opinion.
- Final scope, control expectations, and evidence requirements should be agreed with the appointed auditor.
- Legal, contractual, and customer-specific obligations should be reviewed separately.
