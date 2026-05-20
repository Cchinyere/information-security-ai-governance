# AI Risk Classification Example

## Example Use Case: Internal Customer Support Knowledge Assistant

This example demonstrates how an AI use case can be assessed using a practical AI risk classification approach.

---

## 1. AI System Overview

| Area | Details |
|---|---|
| AI Use Case Name | Internal Customer Support Knowledge Assistant |
| Business Purpose | Assist support agents by summarising internal knowledge base articles and suggesting response drafts. |
| Intended Users | Customer support agents and team leads. |
| Affected Individuals or Groups | Customers may be indirectly affected if inaccurate responses are sent. |
| System Type | Generative AI, retrieval-assisted response drafting. |
| Internal or Third-Party System | Hybrid: internal knowledge base with third-party AI service. |
| Deployment Environment | Pilot. |
| Data Used | Internal support articles, product documentation, historical support themes. |
| Personal Data Involved | Limited personal data should not be entered into the system during pilot. |
| Sensitive Data Involved | No sensitive data intended. |
| Human Oversight Required | Yes. Agents must review and approve all responses before use. |
| Current Status | Proposed pilot. |

---

## 2. Risk Factor Assessment

| Risk Factor | Rating | Rationale |
|---|---|---|
| Business Impact | Medium | The system supports customer communication but does not send messages automatically. |
| Impact on Individuals | Medium | Customers may receive inaccurate information if staff rely on poor outputs. |
| Data Sensitivity | Medium | Internal business information is used. Personal data use should be restricted. |
| Level of Autonomy | Low | Human review is required before any response is sent. |
| Explainability Need | Medium | Users should understand source references and confidence limitations. |
| Bias / Fairness Risk | Low | Use case is operational support rather than individual decision-making. |
| Security Exposure | Medium | Third-party AI processing and prompt injection risks should be assessed. |
| Legal / Regulatory Exposure | Medium | Customer communications may create contractual or compliance issues if inaccurate. |
| Third-Party Dependency | Medium | The service depends on a third-party AI provider. |
| Operational Criticality | Medium | It supports support operations but is not business-critical during pilot. |

---

## 3. Overall Risk Classification

| Risk Level | Selected | Rationale |
|---|---|---|
| Low | No | More than limited internal use due to customer-facing downstream impact. |
| Medium | Yes | Moderate operational and customer impact, human oversight required, third-party dependency present. |
| High | No | No automated decisions, no direct rights-affecting outcome, and no sensitive data intended. |
| Prohibited or Unacceptable | No | No unacceptable use identified based on current scope. |

**Overall Classification:** Medium Risk

---

## 4. Required Governance Controls

| Control Area | Required Control | Evidence Required |
|---|---|---|
| Use Case Approval | Document and approve the business purpose, scope, and restrictions. | Approved use case assessment. |
| Human Oversight | Require staff review before any AI-generated response is used. | Procedure and user guidance. |
| Data Protection | Prohibit entry of unnecessary personal data during pilot. | Data handling guidance and training record. |
| Security Review | Assess third-party provider, data flow, authentication, and prompt injection risk. | Security review record. |
| Supplier Risk | Complete vendor due diligence for the AI service. | Supplier assessment and contract review notes. |
| Accuracy Control | Require source citation or knowledge base references where possible. | Testing results and sample output review. |
| Monitoring | Track errors, user feedback, and inappropriate outputs. | Monitoring log and issue register. |
| Incident Handling | Define escalation route for harmful, inaccurate, or data-exposing outputs. | AI incident response guidance. |
| User Training | Train support agents on limitations and acceptable use. | Training material and attendance record. |
| Review Gate | Complete pilot review before production approval. | Pilot report and governance approval. |

---

## 5. Key Risks

| Risk ID | Risk Description | Impact | Existing Controls | Recommended Treatment | Owner | Priority |
|---|---|---|---|---|---|---|
| AI-001 | AI generates inaccurate customer response. | Customer dissatisfaction, complaint, contractual issue. | Human review required. | Add output review checklist and source reference requirement. | Support Lead | Medium |
| AI-002 | Staff enter personal or sensitive customer data into the tool. | Privacy breach, regulatory concern. | Acceptable use guidance planned. | Add clear data handling rules and training before pilot. | Privacy Lead | High |
| AI-003 | Third-party provider processes internal information without adequate assurance. | Confidentiality and supplier risk. | Supplier review not yet completed. | Complete vendor due diligence before production use. | Security / Procurement | High |
| AI-004 | Prompt injection manipulates responses or reveals internal content. | Security and data exposure risk. | No dedicated testing yet. | Conduct security testing and implement content filtering. | Security Lead | Medium |

---

## 6. Decision Recommendation

| Decision Area | Recommendation |
|---|---|
| Approved for Pilot | Yes, subject to conditions. |
| Approved for Production | Not yet. Production approval should depend on pilot results and remediation closure. |
| Required Conditions | Complete supplier review, data handling guidance, user training, security review, and monitoring plan. |
| Review Frequency | Review after pilot completion and at least quarterly if moved into production. |

---

## 7. Management Summary

The Internal Customer Support Knowledge Assistant is assessed as a **Medium Risk** AI use case. The primary risks relate to inaccurate outputs, inappropriate data entry, third-party dependency, and security exposure. The use case may proceed to pilot if human oversight, data handling restrictions, supplier review, security review, and monitoring controls are implemented before launch.

The system should not be approved for production until pilot results confirm acceptable accuracy, user compliance with data handling requirements, and effective incident escalation processes.
