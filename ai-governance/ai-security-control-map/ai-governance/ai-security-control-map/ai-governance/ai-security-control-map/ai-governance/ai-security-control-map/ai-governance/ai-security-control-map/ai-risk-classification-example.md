# AI Risk Classification Example

## Purpose

This example provides a practical way to classify AI systems by risk level before deployment, review, or audit. It is designed to support AI governance, GRC, compliance, cyber security, and internal audit activities.

AI systems should not be assessed only by the technology used. Risk classification should consider the business process, data involved, level of automation, impact on people, regulatory exposure, third-party dependency, and the level of human oversight.

---

## Example Risk Classification Criteria

| Criteria | Low Risk | Medium Risk | High Risk |
|---|---|---|---|
| **Business Impact** | Supports low-impact internal tasks with limited operational dependency. | Supports business processes where errors may affect productivity, reporting, or decision quality. | Supports critical business processes, regulated activity, customer outcomes, or operational resilience. |
| **Data Sensitivity** | Uses public, non-sensitive, or anonymised data. | Uses internal business data or limited personal data. | Uses sensitive personal data, confidential business data, regulated data, or customer financial data. |
| **Decision Influence** | Provides general assistance with no direct decision-making impact. | Supports decision-making but requires human review before action is taken. | Directly influences or automates decisions affecting customers, employees, finance, compliance, or risk outcomes. |
| **Human Oversight** | Human user fully controls the final output and decision. | Human review is required but may not always be consistently documented. | Limited human oversight or risk of overreliance on AI-generated output. |
| **Regulatory Exposure** | No material regulatory or legal impact. | Some relevance to compliance, reporting, privacy, or operational controls. | Strong regulatory relevance, including financial services, data protection, consumer duty, audit, or legal accountability. |
| **Third-Party Dependency** | Internally managed tool with limited external dependency. | Uses third-party AI tools, APIs, or cloud-based services with contractual controls. | Relies heavily on external AI providers, opaque models, cross-border processing, or outsourced decision support. |
| **Security Exposure** | Limited access, low integration, and no sensitive workflow. | Integrated with internal systems or business data. | Integrated with critical systems, privileged workflows, customer data, or security-sensitive processes. |

---

## Example AI System Classification

| AI Use Case | Description | Suggested Risk Level | Rationale |
|---|---|---|---|
| Internal meeting summary assistant | Summarises internal meeting notes for staff productivity. | Low to Medium | Risk depends on whether confidential or personal data is processed. Human review remains necessary before sharing summaries. |
| Customer complaint analysis tool | Uses AI to categorise complaints and identify themes. | Medium | May involve customer data and influence management reporting, but decisions should still be reviewed by staff. |
| AI-powered fraud detection model | Supports fraud detection and transaction monitoring. | High | May affect customer outcomes, financial crime controls, regulatory reporting, and operational resilience. |
| HR CV screening tool | Scores or ranks candidates during recruitment. | High | May affect individuals directly and requires fairness, transparency, bias monitoring, and documented human oversight. |
| AI chatbot for public customer support | Responds to customer queries on products or services. | Medium to High | Risk depends on whether it provides regulated advice, handles personal data, or influences customer decisions. |
| AI code generation assistant | Supports developers by generating or reviewing code. | Medium | Risk includes insecure code, intellectual property exposure, dependency risk, and lack of secure review. |
| AI tool for regulatory report drafting | Drafts compliance or regulatory reporting content. | High | Inaccurate outputs may result in regulatory, legal, reputational, and assurance failures. |

---

## Recommended Risk Decision

Before approving or deploying an AI system, the organisation should document:

| Area | Required Evidence |
|---|---|
| AI system owner | Named business owner, technical owner, and risk owner. |
| Purpose and use case | Clear explanation of what the AI system is intended to do. |
| Data used | Data inventory, data classification, lawful basis, and privacy review. |
| Risk classification | Documented low, medium, or high risk rating with rationale. |
| Human oversight | Description of review, approval, escalation, and override mechanisms. |
| Security controls | Access control, logging, monitoring, testing, and incident response arrangements. |
| Third-party review | Vendor due diligence, contract terms, assurance reports, and data processing terms. |
| Approval record | Governance forum approval, risk acceptance, or remediation action plan. |

---

## Example Risk Rating Outcome

| Field | Example Response |
|---|---|
| AI System Name | AI-powered fraud detection model |
| Business Area | Financial Crime Operations |
| Risk Level | High |
| Key Risks | False positives, false negatives, customer impact, regulatory reporting failure, explainability gaps, model drift, third-party dependency. |
| Required Controls | Model validation, access control, monitoring, explainability review, human oversight, audit logging, incident response, periodic assurance testing. |
| Approval Requirement | AI Governance Committee and Risk Owner sign-off required before production deployment. |
| Review Frequency | Quarterly or after material model, data, vendor, or regulatory change. |

---

## Notes for Practitioners

Risk classification should not be treated as a one-time activity. It should be reviewed when:

- The AI use case changes.
- The model or vendor changes.
- New data sources are introduced.
- The AI system is integrated with additional business systems.
- Regulatory expectations change.
- A material incident, complaint, or control failure occurs.
