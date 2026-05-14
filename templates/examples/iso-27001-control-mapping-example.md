# ISO 27001 Control Mapping Example

## Purpose

This example demonstrates how selected ISO/IEC 27001:2022 requirements and Annex A controls can be mapped to other security and assurance frameworks, such as the NIST Cybersecurity Framework and SOC 2 Trust Services Criteria.

Control mapping helps organisations reduce duplication, improve assurance efficiency, and show how one control activity can support multiple compliance or governance requirements.

> Note: This is an illustrative example for learning and portfolio purposes. Organisations should validate mappings against the official standards, business context, risk assessment, and audit requirements.

---

## Mapping Approach

This example uses the following structure:

| Field | Description |
|---|---|
| ISO 27001 Reference | Relevant ISO/IEC 27001 clause or Annex A control reference |
| Control Theme | The main governance, security, or operational theme |
| Control Objective | What the control is intended to achieve |
| NIST CSF Alignment | Related NIST Cybersecurity Framework function or category |
| SOC 2 Alignment | Related SOC 2 Trust Services Criteria area |
| Example Evidence | Evidence that may support audit or assurance review |
| Control Owner | Suggested accountable role or team |

---

## ISO 27001 Control Mapping Example

| ISO 27001 Reference | Control Theme | Control Objective | NIST CSF Alignment | SOC 2 Alignment | Example Evidence | Control Owner |
|---|---|---|---|---|---|---|
| Clause 4.3 | ISMS Scope | Define the boundaries and applicability of the Information Security Management System. | Govern | Security | ISMS scope document, system boundary diagram, list of in-scope services, interested party analysis | Information Security Manager |
| Clause 5.3 | Roles and Responsibilities | Ensure information security roles, responsibilities, and authorities are assigned and communicated. | Govern | Security | RACI matrix, role descriptions, governance committee terms of reference, policy approval records | Senior Management / GRC Lead |
| Clause 6.1.2 | Risk Assessment | Establish and apply an information security risk assessment process. | Govern / Identify | Security / Confidentiality | Risk assessment methodology, risk register, risk scoring criteria, assessment records | Risk Owner / GRC Lead |
| Clause 6.1.3 | Risk Treatment | Define treatment actions and select appropriate controls to manage identified risks. | Govern / Protect | Security | Risk treatment plan, Statement of Applicability, control implementation records, risk acceptance approvals | Risk Owner / Control Owner |
| Clause 7.2 | Competence | Ensure personnel have the required competence to perform security-related responsibilities. | Protect | Security | Training records, competency matrix, role-based awareness records, certification evidence | HR / Security Awareness Lead |
| Clause 7.5 | Documented Information | Control documents and records required by the ISMS. | Govern | Security | Document control procedure, version history, approval records, policy review logs | GRC Lead |
| Clause 9.2 | Internal Audit | Conduct internal audits to confirm whether the ISMS conforms to requirements. | Govern | Security | Internal audit plan, audit checklist, audit report, nonconformity log, corrective actions | Internal Audit / GRC Lead |
| Clause 9.3 | Management Review | Ensure top management reviews ISMS performance and improvement opportunities. | Govern | Security | Management review agenda, minutes, risk updates, KPI reports, action tracker | Senior Management |
| Clause 10.2 | Corrective Action | Address nonconformities and prevent recurrence. | Govern / Respond | Security | Corrective action plan, root cause analysis, closure evidence, follow-up review | GRC Lead / Control Owner |
| Annex A 5.1 | Information Security Policies | Establish and communicate policies that direct information security expectations. | Govern | Security | Information Security Policy, approval record, communication evidence, review schedule | Information Security Manager |
| Annex A 5.7 | Threat Intelligence | Collect and use threat intelligence to support risk-informed security decisions. | Identify / Detect | Security | Threat intelligence reports, monitoring records, risk updates, advisory reviews | Security Operations |
| Annex A 5.9 | Inventory of Information and Associated Assets | Maintain an accurate inventory of information assets and related systems. | Identify | Security / Confidentiality | Asset inventory, ownership records, classification records, review logs | IT Asset Owner |
| Annex A 5.15 | Access Control | Restrict access to information and systems based on business and security requirements. | Protect | Security / Confidentiality | Access control policy, RBAC matrix, access approval records, access review evidence | IAM / IT Operations |
| Annex A 5.19 | Supplier Relationships | Manage security risks associated with suppliers and third parties. | Govern / Identify | Security / Confidentiality | Supplier register, risk assessments, contracts, security questionnaires, review records | Procurement / Third-Party Risk |
| Annex A 5.24 | Information Security Incident Management Planning and Preparation | Establish incident management responsibilities, processes, and procedures. | Respond | Security / Availability | Incident response plan, escalation matrix, tabletop exercise results, communication plan | Incident Response Lead |
| Annex A 5.30 | ICT Readiness for Business Continuity | Ensure ICT services can support business continuity requirements. | Recover | Availability | Business continuity plan, disaster recovery plan, backup test results, recovery objectives | IT Operations / BCM Lead |
| Annex A 8.8 | Management of Technical Vulnerabilities | Identify, assess, and remediate technical vulnerabilities. | Identify / Protect | Security | Vulnerability scan reports, remediation tracker, patch records, exception approvals | Vulnerability Management Lead |
| Annex A 8.15 | Logging | Produce and maintain logs to support monitoring, investigation, and accountability. | Detect | Security | Logging standard, SIEM logs, log retention settings, monitoring evidence | Security Operations |
| Annex A 8.16 | Monitoring Activities | Monitor networks, systems, and applications to detect anomalous activity. | Detect | Security / Availability | Alert records, monitoring dashboards, triage notes, incident tickets | SOC / Security Operations |
| Annex A 8.24 | Use of Cryptography | Protect information through appropriate cryptographic controls. | Protect | Security / Confidentiality | Encryption standard, key management records, TLS configuration evidence, encryption settings | IT Security / Infrastructure |

---

## Example Control Detail

### Control Theme: Access Control

| Area | Example |
|---|---|
| ISO 27001 Reference | Annex A 5.15 Access Control |
| Related Requirement | Access to information and systems should be controlled based on business and security requirements. |
| NIST CSF Alignment | Protect |
| SOC 2 Alignment | Security and Confidentiality |
| Control Objective | Ensure only authorised users can access systems, applications, and data required for their role. |
| Implementation Example | Role-based access control is implemented for business applications. Access requests require manager approval. Privileged access is restricted, monitored, and reviewed periodically. |
| Evidence Required | Access control policy, user access review records, joiner-mover-leaver process, privileged access list, approval tickets, exception records |
| Testing Approach | Select a sample of users and confirm that access was approved, appropriate to role, reviewed, and removed when no longer required. |
| Control Owner | Identity and Access Management Team |
| Review Frequency | Quarterly or based on risk |

---

## Sample Evidence Matrix

| Control Area | Evidence Type | Evidence Description | Frequency | Owner |
|---|---|---|---|---|
| Access Control | Policy | Approved access control policy | Annual review | Information Security |
| Access Control | Operational Record | User access request and approval tickets | Per request | IT Operations |
| Access Control | Review Evidence | Quarterly user access review results | Quarterly | System Owner |
| Access Control | Exception Record | Documented access exceptions and approvals | As required | GRC Lead |
| Vulnerability Management | Technical Evidence | Vulnerability scan results and remediation tracker | Monthly | Vulnerability Management |
| Incident Response | Procedure | Incident response plan and escalation matrix | Annual review | Incident Response Lead |
| Monitoring | System Evidence | SIEM alert logs and investigation records | Continuous | SOC Team |
| Supplier Risk | Assessment | Supplier security review and risk rating | Annual or contract renewal | Third-Party Risk |

---

## Practical Notes for Auditors and Assessors

When reviewing control mappings, consider whether:

- The mapping is relevant and defensible.
- The control is implemented and operating effectively.
- Evidence is current, complete, and traceable.
- Control ownership is clearly assigned.
- Exceptions are documented and risk accepted.
- The control addresses the organisation’s actual risk context.
- The same control can support multiple frameworks without overstating compliance.

---

## Common Mapping Mistakes to Avoid

| Mistake | Why It Matters |
|---|---|
| Mapping controls too broadly | Creates weak assurance and may not satisfy audit expectations. |
| Treating policy documents as full implementation evidence | A policy shows intent, but operational records prove activity. |
| Ignoring control ownership | Controls without owners are difficult to monitor and improve. |
| Using outdated evidence | Evidence must reflect current operation of the control. |
| Assuming one-to-one framework equivalence | Different frameworks have different objectives, wording, and assurance expectations. |
| Claiming compliance without validation | Compliance should be supported by evidence, testing, and formal review. |

---

## Summary

This example shows how ISO 27001 controls can be mapped to NIST CSF and SOC 2 to support integrated governance, risk management, and assurance activities.

A strong control mapping should be:

- Risk-based
- Evidence-focused
- Clear enough for audit review
- Linked to accountable owners
- Supported by current documentation and operational records
- Reviewed regularly as systems, risks, and requirements change
