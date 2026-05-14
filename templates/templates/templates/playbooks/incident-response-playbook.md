# Incident Response Playbook

## Purpose

This playbook provides a structured approach for preparing for, detecting, triaging, containing, eradicating, recovering from, and learning from cyber security incidents.

It is designed for use as a practical GitHub portfolio resource and can be adapted for internal incident response planning.

---

## Scope

This playbook applies to suspected or confirmed cyber security incidents affecting:

- User accounts
- Endpoints
- Servers
- Cloud environments
- SaaS platforms
- Networks
- Business applications
- Data repositories
- Third-party services
- Personal or confidential data

---

## Incident Response Principles

| Principle | Description |
|---|---|
| Act quickly but carefully | Prioritise containment and evidence preservation. |
| Protect people and critical services | Focus on safety, continuity, and business impact. |
| Preserve evidence | Maintain logs, timelines, alerts, screenshots, and forensic artefacts. |
| Communicate clearly | Use approved communication channels and avoid speculation. |
| Escalate based on risk | High-impact incidents require senior, legal, privacy, and communications involvement. |
| Learn and improve | Use post-incident reviews to strengthen controls. |

---

## Incident Severity Levels

| Severity | Description | Examples | Escalation |
|---|---|---|---|
| Critical | Major business impact, active compromise, data exfiltration, ransomware, or critical service outage. | Ransomware, confirmed breach, domain admin compromise, public data leak. | Executive, Legal, Privacy, Communications, Incident Lead. |
| High | Significant security event with potential business or data impact. | Privileged account compromise, malware spread, cloud key exposure. | Security Lead, IT Lead, Business Owner, Privacy if data involved. |
| Medium | Security incident contained to limited systems or users. | Single compromised account, isolated malware, suspicious login. | Security Operations, IT Support, System Owner. |
| Low | Suspicious event requiring investigation but no confirmed compromise. | Phishing email reported, blocked malware, failed login spike. | Security Operations. |

---

## Incident Roles and Responsibilities

| Role | Responsibilities |
|---|---|
| Incident Commander | Coordinates the response, assigns actions, manages priorities, and maintains decision records. |
| Security Operations | Investigates alerts, analyses logs, identifies indicators of compromise, and recommends containment. |
| IT Operations | Supports containment, system isolation, restoration, patching, and technical recovery. |
| Business Owner | Assesses operational impact and supports business continuity decisions. |
| Legal / Compliance | Advises on contractual, regulatory, and legal obligations. |
| Data Protection / Privacy | Assesses personal data impact and breach notification requirements. |
| Communications Lead | Manages internal and external communications where required. |
| Senior Management | Approves major decisions, external notifications, and significant recovery actions. |
| Third-Party Provider | Supports investigation or recovery for outsourced systems or services. |

---

## Incident Response Lifecycle

```text
Prepare → Detect → Triage → Contain → Eradicate → Recover → Review
```

---

## 1. Preparation

| Activity | Description | Owner | Evidence |
|---|---|---|---|
| Maintain response plan | Keep incident response plans, contacts, and escalation routes current. | Incident Response Lead | Approved plan, review history |
| Define severity levels | Maintain clear criteria for incident classification. | Security Lead | Severity matrix |
| Maintain asset inventory | Ensure critical systems, owners, and dependencies are known. | IT Operations | Asset register |
| Enable logging | Ensure critical logs are collected, protected, and retained. | Security Operations | SIEM/logging evidence |
| Test response | Run tabletop exercises and lessons learned reviews. | Incident Response Lead | Exercise report |
| Prepare communication templates | Maintain templates for internal, customer, regulator, and supplier communications. | Communications / Legal | Template library |
| Maintain backup and recovery | Ensure backups are protected, tested, and recoverable. | IT Operations | Backup test evidence |

---

## 2. Detection and Reporting

### Common Detection Sources

- SIEM alerts
- XDR or EDR alerts
- User reports
- Phishing mailbox
- Cloud security alerts
- Identity and access alerts
- Vulnerability exploitation alerts
- Third-party notifications
- Law enforcement or regulator notification
- Dark web or threat intelligence findings

### Initial Detection Record

| Field | Details |
|---|---|
| Date and Time Detected |  |
| Reported By |  |
| Detection Source |  |
| Affected User / System |  |
| Initial Description |  |
| Suspected Incident Type |  |
| Initial Severity | Low / Medium / High / Critical |
| Incident Ticket / Reference |  |

---

## 3. Triage

| Triage Question | Response |
|---|---|
| What happened? |  |
| When was it detected? |  |
| Is the activity still ongoing? |  |
| Which users, systems, data, or services are affected? |  |
| Is there evidence of unauthorised access? |  |
| Is there evidence of data exfiltration? |  |
| Is personal data involved? |  |
| Is a third party involved? |  |
| What is the business impact? |  |
| What immediate containment is required? |  |

### Triage Actions

| Action | Owner | Status | Notes |
|---|---|---|---|
| Validate alert or report. | Security Operations |  |  |
| Collect relevant logs and evidence. | Security Operations |  |  |
| Identify affected accounts, hosts, applications, and data. | Security / IT |  |  |
| Assign severity level. | Incident Commander |  |  |
| Open incident bridge or response channel if required. | Incident Commander |  |  |
| Notify appropriate stakeholders. | Incident Commander |  |  |

---

## 4. Containment

Containment should reduce harm while preserving evidence.

| Incident Type | Immediate Containment Actions |
|---|---|
| Compromised Account | Disable or reset account, revoke sessions, reset credentials, require MFA re-registration, review mailbox rules and OAuth grants. |
| Malware Infection | Isolate endpoint, block malicious indicators, preserve forensic evidence, scan related systems. |
| Ransomware | Disconnect affected systems, preserve ransom notes and logs, disable lateral movement paths, protect backups, activate crisis response. |
| Data Exfiltration | Block active channels, preserve logs, identify affected data, engage legal and privacy teams. |
| Cloud Credential Exposure | Revoke exposed keys, rotate secrets, review audit logs, restrict access, check for persistence. |
| Web Application Compromise | Take vulnerable service offline if necessary, preserve logs, block malicious IPs, patch exploited weakness. |
| Phishing / BEC | Remove emails from mailboxes, block sender/domain/URL, review account activity, notify affected users. |

### Containment Record

| Action | Owner | Time Completed | Evidence |
|---|---|---|---|
|  |  |  |  |

---

## 5. Eradication

| Activity | Description | Owner | Evidence |
|---|---|---|---|
| Remove malicious artefacts | Delete malware, scripts, persistence mechanisms, rogue accounts, or unauthorised tools. | Security / IT | EDR records, forensic notes |
| Patch exploited vulnerabilities | Apply patches or configuration changes. | IT Operations | Patch records |
| Remove unauthorised access | Revoke tokens, rotate credentials, disable accounts, remove malicious rules. | IAM / IT | Access records |
| Validate clean state | Confirm malicious activity has stopped. | Security Operations | Logs, scans, monitoring evidence |
| Review related systems | Check for lateral movement or repeated compromise. | Security Operations | Investigation notes |

---

## 6. Recovery

| Activity | Description | Owner | Evidence |
|---|---|---|---|
| Restore services | Restore affected services in a controlled manner. | IT Operations | Recovery records |
| Validate integrity | Confirm systems and data are safe to return to operation. | Security / IT | Validation results |
| Monitor closely | Increase monitoring for recurrence. | Security Operations | SIEM/EDR dashboards |
| Communicate recovery status | Provide updates to stakeholders. | Incident Commander | Communication log |
| Confirm business readiness | Business owner confirms service readiness. | Business Owner | Approval record |

---

## 7. Communication and Escalation

### Internal Escalation Triggers

Escalate immediately where there is:

- Confirmed unauthorised access
- Critical system outage
- Ransomware or destructive malware
- Suspected personal data breach
- Regulatory or contractual notification concern
- Supplier or customer impact
- Media or reputational risk
- Executive or privileged account compromise
- Law enforcement involvement

### Communication Log

| Time | Audience | Message Summary | Owner | Channel |
|---|---|---|---|---|
|  |  |  |  |  |

### Communication Rules

- Use factual language.
- Avoid speculation.
- Mark sensitive communications appropriately.
- Keep legal, privacy, and senior management informed for high-impact incidents.
- Do not delete evidence or alter logs unless instructed as part of approved containment.

---

## 8. Personal Data Breach Assessment

Complete this section where personal data may be involved.

| Question | Response |
|---|---|
| What personal data may be affected? |  |
| How many individuals may be affected? |  |
| What is the likely risk to individuals? |  |
| Was data accessed, altered, lost, disclosed, or exfiltrated? |  |
| Was the data encrypted or otherwise protected? |  |
| Is regulatory notification required? |  |
| Is notification to affected individuals required? |  |
| Who approved the notification decision? |  |

---

## 9. Scenario Playbooks

### 9.1 Phishing or Business Email Compromise

| Phase | Actions |
|---|---|
| Detect | Review reported email, headers, URLs, attachments, and sender. |
| Triage | Identify recipients, clicks, credential submissions, and suspicious mailbox activity. |
| Contain | Remove email, block indicators, reset credentials, revoke sessions, remove malicious mailbox rules. |
| Eradicate | Remove OAuth grants, persistence rules, forwarding rules, and suspicious inbox delegates. |
| Recover | Restore account access securely, monitor login activity, notify affected stakeholders. |
| Review | Update mail filtering, awareness guidance, detection rules, and reporting process. |

### 9.2 Ransomware

| Phase | Actions |
|---|---|
| Detect | Confirm encryption activity, ransom notes, EDR alerts, and affected systems. |
| Triage | Identify spread, critical services affected, backup status, and data exfiltration indicators. |
| Contain | Isolate affected systems, disable compromised accounts, block command-and-control, protect backups. |
| Eradicate | Remove malware, patch initial access vector, rebuild compromised hosts where required. |
| Recover | Restore from clean backups, validate systems, monitor for reinfection. |
| Review | Conduct root cause analysis and strengthen access, backup, segmentation, and detection controls. |

### 9.3 Cloud Credential Compromise

| Phase | Actions |
|---|---|
| Detect | Review cloud audit logs, unusual API calls, impossible travel, and abnormal privilege use. |
| Triage | Identify exposed keys, affected resources, data accessed, and persistence mechanisms. |
| Contain | Revoke keys, rotate secrets, disable compromised accounts, restrict network access. |
| Eradicate | Remove unauthorised users, roles, access policies, workloads, and persistence. |
| Recover | Validate cloud configuration, restore services, monitor for suspicious activity. |
| Review | Improve secret management, least privilege, MFA, logging, and alerting. |

### 9.4 Web Application Compromise

| Phase | Actions |
|---|---|
| Detect | Review WAF alerts, application logs, unusual requests, file changes, and admin activity. |
| Triage | Identify exploited vulnerability, affected data, attacker actions, and service impact. |
| Contain | Block exploit traffic, disable vulnerable function, isolate server, or take service offline if required. |
| Eradicate | Patch vulnerability, remove web shells, rotate credentials, rebuild compromised components. |
| Recover | Validate application integrity, restore service, monitor for repeated exploitation. |
| Review | Improve secure development, testing, patching, WAF rules, and logging. |

---

## 10. Evidence Collection Checklist

| Evidence Type | Collected? | Location / Reference | Owner |
|---|---|---|---|
| Alert details |  |  |  |
| System logs |  |  |  |
| Authentication logs |  |  |  |
| Endpoint telemetry |  |  |  |
| Network logs |  |  |  |
| Cloud audit logs |  |  |  |
| Screenshots |  |  |  |
| Malicious files or hashes |  |  |  |
| Email headers |  |  |  |
| Timeline of events |  |  |  |
| Actions taken |  |  |  |
| Communications |  |  |  |
| Approvals and decisions |  |  |  |

---

## 11. Post-Incident Review

Conduct a post-incident review after containment and recovery.

| Review Question | Response |
|---|---|
| What happened? |  |
| What was the root cause? |  |
| How was the incident detected? |  |
| What worked well? |  |
| What did not work well? |  |
| Were escalation routes effective? |  |
| Were logs and evidence sufficient? |  |
| Were business impacts managed effectively? |  |
| Are policy, process, or technical control changes required? |  |
| What actions must be completed? |  |

### Lessons Learned Action Plan

| Action | Owner | Priority | Due Date | Status |
|---|---|---|---|---|
|  |  | High / Medium / Low |  | Open / In Progress / Closed |
