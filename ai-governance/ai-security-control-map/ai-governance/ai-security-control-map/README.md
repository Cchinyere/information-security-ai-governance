# AI Security Control Map

![AI Security Control Map](assets/ai_security_control_map_github_banner.png)

## Overview

The **AI Security Control Map** is a practitioner reference for **GRC, compliance, internal audit, cyber security, and AI governance professionals** working with regulated financial services and enterprise AI systems.

The purpose of this resource is to help organisations assess whether AI systems are being designed, deployed, monitored, and governed securely. It translates AI security and governance concerns into practical control objectives that can be used for risk assessments, audit reviews, compliance checks, third-party assurance, and governance reporting.

This control map is built around:

| Component | Description |
|---|---|
| **55 Control Objectives** | Practical control objectives covering AI security, governance, monitoring, accountability, and assurance. |
| **7 Control Domains** | A structured control model covering the main areas of AI security risk. |
| **4 Columns per Control** | A simple format to support review, testing, evidence gathering, and reporting. |
| **6 Regulatory Frameworks** | Mapped references to support compliance, assurance, and governance alignment. |

---

## Why This Control Map Matters

AI introduces risks that traditional cyber security and IT governance controls do not always address fully. These risks include insecure training data, model manipulation, weak prompt controls, unreliable outputs, poor explainability, third-party AI dependency, and limited auditability.

In regulated financial services and enterprise environments, these risks can affect:

- Customer outcomes
- Data protection
- Operational resilience
- Regulatory compliance
- Security monitoring
- Decision accountability
- Third-party risk management
- Internal audit assurance

This control map helps practitioners move from broad AI governance principles to practical control questions that can be assessed, evidenced, and improved.

---

## Control Domains

The AI Security Control Map is organised into **7 control domains**.

| Domain | Focus Area | Description |
|---|---|---|
| **1. Data Governance and Training Data Security** | Data quality, privacy, integrity, and authorised use | Ensures that data used in AI systems is appropriate, protected, lawful, traceable, and fit for purpose. |
| **2. Model Security and Supply Chain** | Model development, procurement, dependency, and integrity | Addresses risks linked to model sourcing, model updates, third-party components, and AI supply chain exposure. |
| **3. Prompt and Input Security** | Prompt injection, malicious input, and misuse prevention | Focuses on controls that reduce the risk of unsafe, manipulated, or unauthorised input influencing AI behaviour. |
| **4. Output Security and Reliability** | AI-generated content, accuracy, validation, and human review | Ensures outputs are reviewed, explainable where required, reliable for their intended use, and not blindly trusted. |
| **5. Access Control and Identity** | User access, privileged access, and segregation of duties | Covers identity controls, role-based access, administrative access, and accountability for AI system use. |
| **6. Monitoring, Logging and Incident Response** | Detection, audit trails, escalation, and response | Ensures AI systems are monitored for misuse, abnormal behaviour, control failure, and security incidents. |
| **7. Vendor and Third-Party AI Risk** | Supplier assurance, contractual controls, and external dependency | Addresses risks from AI vendors, SaaS tools, embedded AI, APIs, cloud-hosted models, and outsourced services. |

---

## Control Format

Each control objective is structured using **4 practical columns**.

| Column | Purpose |
|---|---|
| **Control Objective** | Defines what should be controlled or achieved. |
| **Risk Addressed** | Explains the AI security, governance, compliance, or operational risk the control is intended to reduce. |
| **Assurance Activity** | Describes how the control can be reviewed, tested, or assessed. |
| **Evidence Examples** | Provides examples of documents, logs, approvals, records, or artefacts that may support assurance. |

This structure is designed to make the control map useful for both implementation and assurance.

---

## Regulatory and Framework Alignment

The control map is designed to support alignment with **6 key regulatory and governance frameworks** commonly relevant to AI security, risk, compliance, and assurance.

| Framework | Relevance |
|---|---|
| **ISO/IEC 27001** | Information security management, control governance, risk treatment, and security assurance. |
| **ISO/IEC 42001** | AI management system governance, accountability, lifecycle management, and responsible AI oversight. |
| **NIST AI Risk Management Framework** | AI risk identification, measurement, management, governance, and trustworthiness. |
| **NIST Cybersecurity Framework** | Cybersecurity governance, protection, detection, response, and recovery for AI-enabled systems. |
| **EU AI Act** | AI risk classification, governance expectations, transparency, accountability, and high-risk AI requirements. |
| **DORA / Financial Services Operational Resilience** | ICT risk management, third-party dependency, resilience, incident reporting, and control assurance in financial services. |

---

## How This Resource Can Be Used

This control map can support:

### 1. AI Risk Assessments

Use the control objectives to identify security, governance, compliance, and operational risks before AI systems are deployed or expanded.

### 2. Internal Audit Reviews

Use the control domains to scope AI audit activity, define control testing areas, request evidence, and assess control effectiveness.

### 3. GRC and Compliance Mapping

Use the framework alignment to connect AI control activity with recognised governance, regulatory, and assurance expectations.

### 4. Third-Party AI Risk Management

Use the vendor and supply chain controls to assess external AI providers, embedded AI tools, APIs, SaaS solutions, and outsourced AI capabilities.

### 5. AI Governance Reporting

Use the control structure to support governance forums, risk committees, management reporting, and accountable ownership of AI risks.

### 6. Control Gap Assessments

Use the map to identify missing, weak, or immature AI controls and prioritise remediation based on risk exposure.

---

## Example Control Objective Format

| Control Objective | Risk Addressed | Assurance Activity | Evidence Examples |
|---|---|---|---|
| AI systems should have defined ownership and accountability before deployment. | Lack of ownership may result in unclear accountability for risk decisions, system behaviour, monitoring, and control failures. | Review governance records to confirm named system owner, business owner, technical owner, and risk owner. | AI system register, RACI matrix, governance approval record, risk assessment, committee minutes. |
| Sensitive data should not be used in AI systems without appropriate approval, protection, and lawful basis. | Unauthorised or inappropriate use of sensitive data may result in privacy breaches, regulatory exposure, and loss of trust. | Review data flow documentation, DPIA, access controls, and data usage approvals. | DPIA, data inventory, access review records, privacy assessment, approval logs. |
| AI-generated outputs should be subject to human review where decisions may affect customers, employees, or regulated outcomes. | Overreliance on AI outputs may lead to unfair, inaccurate, harmful, or non-compliant decisions. | Test whether human review is embedded into workflow design and decision approval processes. | Workflow design, review logs, decision records, escalation procedure, quality assurance reports. |


## Repository Structure

ai-governance/
└── ai-security-control-map/
    ├── README.md
    ├── ai-risk-classification-example.md
    ├── control-prioritisation-matrix.md
    ├── ai-security-control-attestation-template.md
    └── assets/
        └── ai_security_control_map_github_banner.png


## Supporting Files

| File | Purpose |
|---|---|
| [AI Risk Classification Example](ai-risk-classification-example.md) | Shows how AI systems can be classified by risk level using business impact, data sensitivity, autonomy, regulatory exposure, and customer impact. |
| [Control Prioritisation Matrix](control-prioritisation-matrix.md) | Provides a practical way to rank AI security controls by risk severity, implementation urgency, assurance priority, and business impact. |
| [AI Security Control Attestation Template](ai-security-control-attestation-template.md) | A reusable template for control owners to confirm whether AI security controls are implemented, evidenced, reviewed, and operating effectively. |
