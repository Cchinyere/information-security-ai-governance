# AI Security Control Prioritisation Matrix

## Purpose

This matrix helps practitioners prioritise AI security controls based on risk severity, business impact, implementation urgency, regulatory relevance, and assurance priority.

Not every AI control can be implemented at the same time. This matrix supports practical decision-making by helping teams identify which controls should be addressed first.

---

## Prioritisation Criteria

| Criteria | Description |
|---|---|
| **Risk Severity** | The potential harm if the control is missing, weak, or ineffective. |
| **Business Impact** | The effect on customers, operations, regulatory obligations, financial outcomes, or reputation. |
| **Regulatory Relevance** | The extent to which the control supports legal, regulatory, or governance expectations. |
| **Implementation Urgency** | How quickly the control should be implemented based on exposure and dependency. |
| **Assurance Priority** | Whether the control should be prioritised for audit, compliance review, or management reporting. |

---

## Rating Scale

| Score | Rating | Meaning |
|---|---|---|
| 1 | Low | Limited exposure or low operational relevance. |
| 2 | Moderate | Some exposure, but compensating controls may exist. |
| 3 | High | Material risk requiring management attention and planned remediation. |
| 4 | Critical | Significant exposure requiring urgent action, formal tracking, and senior oversight. |

---

## Prioritisation Matrix

| Control Area | Risk Severity | Business Impact | Regulatory Relevance | Implementation Urgency | Assurance Priority | Total Score | Priority |
|---|---:|---:|---:|---:|---:|---:|---|
| AI system ownership and accountability | 4 | 4 | 4 | 4 | 4 | 20 | Critical |
| AI system inventory and use case register | 4 | 4 | 4 | 4 | 4 | 20 | Critical |
| Data classification for AI inputs | 4 | 4 | 4 | 4 | 4 | 20 | Critical |
| Sensitive data approval and protection | 4 | 4 | 4 | 4 | 4 | 20 | Critical |
| Human oversight for high-impact AI decisions | 4 | 4 | 4 | 4 | 4 | 20 | Critical |
| Third-party AI vendor due diligence | 4 | 4 | 4 | 3 | 4 | 19 | Critical |
| AI access control and privileged access review | 4 | 4 | 3 | 4 | 4 | 19 | Critical |
| Logging and monitoring of AI system activity | 4 | 4 | 3 | 4 | 4 | 19 | Critical |
| AI incident response procedure | 4 | 4 | 3 | 4 | 4 | 19 | Critical |
| Prompt injection and input misuse controls | 4 | 3 | 3 | 4 | 3 | 17 | High |
| Output validation and quality assurance | 4 | 4 | 3 | 3 | 3 | 17 | High |
| Model change management | 4 | 4 | 3 | 3 | 3 | 17 | High |
| Explainability and decision rationale | 3 | 4 | 4 | 3 | 3 | 17 | High |
| Bias and fairness review | 3 | 4 | 4 | 3 | 3 | 17 | High |
| AI acceptable use policy | 3 | 3 | 3 | 4 | 3 | 16 | High |
| User training for AI security risks | 3 | 3 | 3 | 3 | 3 | 15 | High |
| Periodic AI control assurance review | 3 | 3 | 3 | 3 | 4 | 16 | High |
| AI risk acceptance process | 3 | 4 | 4 | 3 | 4 | 18 | Critical |
| Data retention and deletion controls | 3 | 4 | 4 | 3 | 3 | 17 | High |
| Vendor exit and continuity planning | 3 | 4 | 3 | 3 | 3 | 16 | High |

---

## Priority Interpretation

| Total Score | Priority | Recommended Action |
|---:|---|---|
| 18 to 20 | Critical | Immediate action required. Assign owner, track remediation, and report to governance forum. |
| 14 to 17 | High | Action required within defined remediation timeline. Include in audit or compliance review. |
| 9 to 13 | Medium | Monitor and improve through planned control maturity activities. |
| 5 to 8 | Low | Maintain awareness and review periodically. |

---

## Example Control Prioritisation Decision

| Field | Example |
|---|---|
| Control | AI system inventory and use case register |
| Total Score | 20 |
| Priority | Critical |
| Reason | Without a complete AI inventory, the organisation cannot understand where AI is being used, what data is involved, who owns the risk, or which systems require assurance. |
| Recommended Action | Establish and maintain a central AI register with ownership, purpose, risk classification, data categories, vendor details, and approval status. |
| Evidence Required | AI register, governance approval record, ownership matrix, risk classification record, periodic review log. |
| Review Frequency | Monthly during initial rollout, then quarterly once embedded. |

---

## Practitioner Notes

Controls with high regulatory relevance or direct impact on customers, employees, financial outcomes, or operational resilience should usually be prioritised first.

A control may also be prioritised if:

- The AI system uses sensitive or regulated data.
- The AI system influences decisions affecting people.
- The AI system is externally hosted or vendor-managed.
- There is limited transparency over how the AI system works.
- There is no clear human oversight.
- There is no audit trail or monitoring process.
- The AI system supports a critical business process.
