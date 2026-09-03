# High-Risk AI Classification & Regulatory Change Monitoring Programme

A fictional portfolio project demonstrating an enterprise methodology for inventorying AI systems, classifying them under **EU AI Act Article 6** (high-risk classification) and **Article 7** (changes to high-risk use cases), documenting exceptions, and monitoring regulatory and system changes over time.

## About this repository

This repository contains a single-file portfolio project covering:

- An enterprise AI inventory of six fictional AI systems across HR, finance, customer service, corporate services, and cybersecurity
- A 12-question Article 6 classification questionnaire and a high-risk classification decision tree
- Six completed, evidence-based classification assessments
- A formal High-Risk AI Register linking classified systems to their required governance workstreams
- An Exception Justification Template, with a worked example
- A Regulatory Change Monitoring Log tracking regulatory, system, and incident-driven triggers
- A Quarterly Reclassification Review Procedure
- An executive dashboard, framework-alignment/reference register, governance controls, and management recommendations

**Fictional scenario:** The project is built around **Meridian Digital Services**, a fictional organization operating six AI systems: a recruitment screening tool, an invoice anomaly detector, a customer support chatbot, a creditworthiness assessment system, a meeting transcription assistant, and a security alert prioritization agent. Of these, **two were classified High-Risk** (recruitment screening, creditworthiness assessment), **two Not High-Risk**, **one Not High-Risk with Conditions** (customer support chatbot), and **one flagged for Review Required** (security alert prioritization agent).

## Frameworks referenced

- Regulation (EU) 2024/1689 (EU AI Act) — Articles 6 and 7
- NIST AI Risk Management Framework — MAP and GOVERN functions
- ISO/IEC 42001:2023
- ISO 31000:2018

> **Disclaimer:** This is a fictional portfolio project using synthetic data. It demonstrates a classification and monitoring methodology, not legal advice or a formal EU AI Act compliance determination. Final classification requires review of the official regulation, applicable Annexes, and qualified legal or compliance advice.

---

# Project 3: High-Risk AI Classification & Regulatory Change Monitoring

**Prepared by:** Augustine Tetteh Ozor · **Fictional organization:** Meridian Digital Services · **Systems assessed:** Six · **Portfolio status:** Complete demonstration project · **Data status:** Synthetic examples only

This project demonstrates governance methodology. It is not legal advice or a formal EU AI Act classification opinion.

## 1. Executive Summary

Meridian Digital Services, a fictional technology organization, uses six AI systems across recruitment, finance, customer service, corporate services and cybersecurity. Management requires a defensible process to determine which systems need enhanced governance under the EU AI Act and how classification decisions should be revisited as regulation and system use evolve.

The project establishes an AI inventory, an Article 6 questionnaire, a decision tree, six documented classification assessments, a formal high-risk register, an exception template, a regulatory monitoring log, and a quarterly reclassification procedure.

| 6 systems assessed | 2 high-risk | 2 not high-risk | 2 conditional or pending |
|---|---|---|---|

## 2. Regulatory and Framework Basis

Article 6 provides pathways for classifying certain AI systems as high-risk, including product-safety-related systems and specified use cases. Article 7 provides a mechanism for changes to high-risk use cases. The official regulation and its Annexes remain the controlling legal source. The portfolio supplements this legal analysis with governance concepts from the NIST AI Risk Management Framework, ISO/IEC 42001, and ISO 31000.

A critical design principle is to **separate legal classification from internal risk scoring**. A system may be legally outside the Article 6 high-risk category while still presenting material privacy, cybersecurity, operational, or reputational risk that requires controls.

### EU AI Act Article 6

Article 6 establishes whether an AI system should be classified as a High-Risk AI System. The assessment focuses on whether the system:

- Operates in a listed high-impact area (Annex III).
- Influences decisions affecting individuals.
- Profiles individuals.
- Could significantly affect rights, opportunities, or safety.
- Is part of a regulated product requiring third-party conformity assessment.

### EU AI Act Article 7

Article 7 supports ongoing review and modification of High-Risk AI categories. Organizations must be able to: track regulatory developments; reassess systems when use cases change; reassess when harm evidence emerges; and reassess when deployment expands.

## 3. Business Scenario and Systems

| System | Business Purpose |
|---|---|
| Recruitment Screening Tool | Score and rank applications to support candidate shortlisting |
| Invoice Anomaly Detector | Flag invoices with unusual patterns for analyst review |
| Customer Support Chatbot | Answer routine questions using approved knowledge content |
| Creditworthiness Assessment System | Generate a risk score and recommendation for consumer credit applications |
| Meeting Transcription Assistant | Transcribe meetings and produce draft summaries |
| Security Alert Prioritization Agent | Prioritize alerts and recommend investigation steps |

The Compliance and Governance Office must determine: which systems are High-Risk AI Systems; which require enhanced governance; which qualify for exceptions; how regulatory changes should be monitored; and how classification decisions should be reassessed.

### 3.1 Governance Objectives

The programme establishes a governance capability to:

- ✓ Maintain an AI inventory
- ✓ Identify High-Risk AI Systems
- ✓ Document classification decisions
- ✓ Document exceptions
- ✓ Conduct regulatory horizon scanning
- ✓ Trigger reclassification reviews
- ✓ Maintain governance evidence
- ✓ Demonstrate compliance readiness

## 4. Methodology

**Step 1 — Inventory and context:** Record the system owner, provider, intended purpose, users, affected people, data, output, decision impact, oversight, lifecycle, and deployment context.

**Step 2 — Article 6 pathway analysis:** Assess the product-safety pathway and whether the intended use maps to an Annex III area.

**Step 3 — Materiality and profiling:** Determine whether the system profiles individuals or materially influences a decision affecting health, safety, rights, or opportunities.

**Step 4 — Exception analysis:** Where an Annex III system appears limited or preparatory, document the exact limitation, human review, lack of material influence, and evidence supporting the conclusion.

**Step 5 — Independent review and approval:** Require Legal or Compliance review and governance approval for high-risk, conditional, exception, or unclear decisions.

**Step 6 — Monitoring and reassessment:** Track regulatory changes and system changes, with event-driven and scheduled reclassification.

### Governance Workflow

```
AI Inventory
     ↓
Article 6 Assessment
     ↓
Classification Decision
     ↓
Governance Review
     ↓
   Approval
     ↓
High-Risk Register
     ↓
Regulatory Monitoring
     ↓
Quarterly Review
     ↓
Reclassification Decision
     ↓
Inventory Update
```

## 5. Deliverable 1: AI Inventory Register

Every AI system deployed, piloted, tested, or procured must be recorded. **Inventory ownership:** AI Governance Office. **Review cycle:** Quarterly.

| System ID | AI System | Business Function | Business Owner | Provider | Provider Role | Intended Purpose | Primary Users | Affected Individuals | Human Oversight | Lifecycle Stage | Deployment / Reach | Annex III Area | Initial Risk Tier | Classification Status | Next Review |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| AI-001 | Recruitment Screening Tool | Human Resources | Head of Talent Acquisition | TalentSelect Cloud | Third-party provider | Score and rank applications to support candidate shortlisting | Recruiters | Job applicants | Human approves shortlist and may override ranking | Pilot | EU cloud region; EU and non-EU applicants | Employment and worker management | High | High-Risk | 2026-09-30 |
| AI-002 | Invoice Anomaly Detector | Finance | Finance Operations Manager | Meridian Data Science | Internal provider | Flag invoices with unusual patterns for analyst review | Accounts payable analysts | Suppliers and finance staff | Analyst reviews every alert | Production | Private cloud; internal operations | None identified | Medium | Not High-Risk | 2026-12-31 |
| AI-003 | Customer Support Chatbot | Customer Service | Customer Experience Director | SupportAI Ltd. | Third-party provider | Answer routine questions using approved knowledge content | Customers and support agents | Customers | Escalation to human agent | Production | EU SaaS; EU customers | Access to services requires case-specific review | Medium | Not High-Risk with Conditions | 2026-10-31 |
| AI-004 | Creditworthiness Assessment System | Financial Services | Chief Credit Officer | Meridian Analytics | Internal provider | Generate risk score and recommendation for consumer credit applications | Credit analysts | Credit applicants | Analyst reviews recommendation and records final decision | Development | EU private cloud; EU applicants | Access to essential private services | High | High-Risk | 2026-09-30 |
| AI-005 | Meeting Transcription Assistant | Corporate Services | Collaboration Services Lead | MeetingCloud | Third-party provider | Transcribe meetings and produce draft summaries | Employees | Meeting participants | Meeting organizer reviews and controls sharing | Production | EU SaaS; internal users | None identified | Low | Not High-Risk | 2027-01-31 |
| AI-006 | Security Alert Prioritization Agent | Cybersecurity | SOC Manager | Meridian Security Engineering | Internal provider | Prioritize alerts and recommend investigation steps | Security analysts | Employees, customers, and system users may be indirectly affected | Analyst approves any containment action | Pilot | Private cloud; enterprise systems | Critical infrastructure relevance requires legal review | High | Review Required | 2026-09-15 |

*(Data categories per system: AI-001 — CVs, employment history, qualifications, assessment scores; AI-002 — invoice details, supplier records, payment history; AI-003 — queries, account category, help articles, no payment data; AI-004 — identity, income, repayment history, financial behavior; AI-005 — audio, names, transcript, meeting metadata; AI-006 — security logs, asset data, identity events.)*

## 6. Deliverable 2: Article 6 Classification Questionnaire

A twelve-question, evidence-led assessment covering product pathways, Annex III mapping, profiling, material influence, exceptions, monitoring, and approval.

| # | Assessment Question | If Yes | If No | Reviewer Guidance |
|---|---|---|---|---|
| Q1 | Is the AI system intended to be used as a safety component of a product, or is the AI system itself a product, covered by relevant EU harmonisation legislation? | Continue to Q2 | Continue to Q3 | Do not infer product regulation without legal review. |
| Q2 | Is the product required to undergo a third-party conformity assessment before being placed on the market or put into service? | Article 6(1) high-risk pathway indicated | Continue to Q3 | Both Article 6(1) conditions should be evidenced. |
| Q3 | Does the intended purpose fall within a use case listed in Annex III? | Continue to Q4 | Normally not high-risk under Article 6(2), subject to other rules | Map the actual purpose, not the marketing label. |
| Q4 | Does the system perform profiling of natural persons? | Treat as high-risk when within Annex III; obtain compliance review | Continue to Q5 | Record why profiling is or is not present. |
| Q5 | Does the system pose a significant risk of harm to health, safety, or fundamental rights by materially influencing decision-making? | High-risk classification indicated | Continue to Q6 | Assess actual influence and reasonably foreseeable use. |
| Q6 | Does the system only perform a narrow procedural task? | Potential exception; continue through Q9 | Continue to Q7 | An exception requires documented justification. |
| Q7 | Does the system improve the result of a previously completed human activity without replacing or influencing the human assessment? | Potential exception; continue through Q9 | Continue to Q8 | Verify that the prior human activity is genuinely completed. |
| Q8 | Does the system detect decision-making patterns or deviations without replacing or influencing the prior human assessment without proper review? | Potential exception; continue through Q9 | Continue to Q9 | Document how the output is prevented from becoming determinative. |
| Q9 | Does the system perform a preparatory task that does not materially influence the outcome of the Annex III use case? | Potential exception if Q4 is No and justification is approved | High-risk classification likely | Record the evidence and approval for any exception. |
| Q10 | Could a change in intended purpose, functionality, users, scale, geography, data, or autonomy alter this result? | Add monitoring trigger and reassessment condition | Retain normal review schedule | This supports ongoing Article 7 and change monitoring. |
| Q11 | Has legal or compliance reviewed the classification and underlying evidence? | Proceed to governance approval | Classification remains pending | Independent review strengthens defensibility. |
| Q12 | Has the accountable governance body approved the decision and next review date? | Record final status | Do not close assessment | Maintain version and reclassification history. |

Each question expects response options **Yes / No / Unclear**, evidence (product description, applicable legislation mapping, functional description, impact assessment, process maps, etc.), and a recorded status (Required / Conditional / Exception test / Monitoring / Approval).

## 7. Deliverable 3: High-Risk Classification Decision Tree

| Step | Guidance |
|---|---|
| **START** | Define the intended purpose, provider/deployer roles, affected people, data, outputs, and decision impact. |
| **Pathway A** | Is the AI a safety component, or itself a product, under relevant EU product legislation? |
| **A2** | Does that product require third-party conformity assessment? |
| **Result A** | If both answers are Yes, classify through the Article 6(1) high-risk pathway. |
| **Pathway B** | Does the intended purpose fall within an Annex III use case? |
| **B2** | If No, record Not High-Risk under Article 6, while assessing other AI Act obligations. |
| **B3** | If Yes, does the system profile individuals or materially influence a decision affecting health, safety, or fundamental rights? |
| **Result B** | If Yes, classify as High-Risk. If potentially non-material, assess the Article 6 exception conditions. |
| **Exception** | Document the limited task, lack of material influence, human review, evidence, and approval. Profiling within Annex III should be escalated. |
| **Control** | Record the decision, rationale, reviewer, approver, conditions, and next review date. |
| **Monitor** | Reassess after regulatory changes, intended-purpose changes, material functionality changes, scale expansion, incidents, complaints, or evidence of harm. |

**Simplified visual flow:**

```
                     Start
                       │
                       ▼
      Does the system operate in a high-impact
              (Annex III) area?
               │                    │
              No                   Yes
               │                    │
               ▼                    ▼
          Not High-Risk    Does it materially influence
                                   decisions?
                                │           │
                               No          Yes
                                │           │
                                ▼           ▼
                        Assess Exception   Does it profile individuals,
                                            or could outcomes significantly
                                            affect rights, opportunities,
                                            or safety?
                                                    │
                                                   Yes
                                                    │
                                                    ▼
                                            High-Risk AI System
```

## 8. Deliverable 4: Six Completed Classification Assessments

| Assessment ID | System | Intended Purpose | Article 6(1) Product Pathway | Annex III Mapping | Profiles Individuals? | Material Decision Influence? | Potential Exception? | Preliminary Outcome | Governance Approval | Conditions / Actions | Assessment Date | Next Review |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CA-001 | Recruitment Screening Tool | Score and rank candidates for shortlisting | No product pathway identified | Employment, recruitment and selection | Yes, candidate profiling | Yes | No | **High-Risk** | Approved for controlled pilot | Complete Article 8–15 controls before production | 2026-08-20 | 2026-09-30 |
| CA-002 | Invoice Anomaly Detector | Flag unusual invoices for analyst review | No product pathway identified | No Annex III use identified | No | No binding decision | Not needed | **Not High-Risk** | Approved | Maintain human review and monitor purpose changes | 2026-08-20 | 2026-12-31 |
| CA-003 | Customer Support Chatbot | Provide routine information from approved content | No product pathway identified | Could relate to access to services only if used for eligibility or binding action | Limited interaction data; no eligibility profiling | No under current design | Yes, if treated as preparatory/informational only | **Not High-Risk with Conditions** | Approved with restrictions | No eligibility decisions, account termination, or binding action; reassess if scope expands | 2026-08-21 | 2026-10-31 |
| CA-004 | Creditworthiness Assessment System | Score and recommend outcomes for consumer credit | No product pathway identified | Access to essential private services and creditworthiness | Yes | Yes | No | **High-Risk** | Development approved; production pending | Complete high-risk compliance programme and conformity route | 2026-08-21 | 2026-09-30 |
| CA-005 | Meeting Transcription Assistant | Transcribe and summarize meetings | No product pathway identified | No Annex III use identified | No decision profiling | No | Not needed | **Not High-Risk** | Approved | Apply privacy, transparency, security, and acceptable-use controls | 2026-08-22 | 2027-01-31 |
| CA-006 | Security Alert Prioritization Agent | Prioritize cyber alerts and recommend investigation actions | No product pathway established | Potential critical-infrastructure relevance depends on deployment context | May profile account or device behavior | Could materially affect response priorities; containment remains human-approved | Unclear | **Review Required** | Not approved for autonomous containment | Clarify sector scope; complete impact and product-law analysis; maintain human approval | 2026-08-22 | 2026-09-15 |

Each assessment's key evidence draws on workflow documentation, vendor documentation, impact assessments, bias-testing plans, process maps, user procedures, sample alerts, architecture diagrams, tool permissions, and oversight/shutdown design — reviewed by Legal/Compliance and recorded in the assessment record.

## 9. Classification Outcomes Summary

| System | Outcome | Primary Rationale | Required Next Step |
|---|---|---|---|
| Recruitment Screening Tool | **High-Risk** | Ranks applicants and materially influences employment shortlisting. | Complete the high-risk governance requirements before production. |
| Invoice Anomaly Detector | **Not High-Risk** | Provides an internal advisory flag with mandatory analyst review. | Maintain controls and monitor purpose or automation changes. |
| Customer Support Chatbot | **Not High-Risk with Conditions** | Informational use only; no eligibility or binding account action. | Preserve restrictions and reassess before adding binding actions. |
| Creditworthiness Assessment System | **High-Risk** | Profiles applicants and influences access to consumer credit. | Complete the full high-risk provider and system compliance programme. |
| Meeting Transcription Assistant | **Not High-Risk** | Administrative transcription and summarization without material decision influence. | Apply privacy, security, retention, and transparency controls. |
| Security Alert Prioritization Agent | **Review Required** | Classification depends on deployment context, affected operations, and degree of influence. | Obtain legal and sector review before expansion or autonomous action. |

## 10. Deliverable 5: High-Risk AI Register

| System ID | AI System | High-Risk Pathway | Annex / Domain | Provider | Business Owner | Classification Date | Decision Reference | Lifecycle Stage | Required Governance Workstream | Open Preconditions | Compliance Owner | Status | Next Review |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| AI-001 | Recruitment Screening Tool | Article 6(2), Annex III | Employment and recruitment | TalentSelect Cloud | Head of Talent Acquisition | 2026-08-20 | CA-001 | Pilot | Risk management; data governance; technical documentation; logging; transparency; human oversight; accuracy/security; QMS | Bias assessment; provider evidence; monitoring thresholds; user training | AI Compliance Manager | Controlled Pilot | 2026-09-30 |
| AI-004 | Creditworthiness Assessment System | Article 6(2), Annex III | Access to essential private services / creditworthiness | Meridian Analytics | Chief Credit Officer | 2026-08-21 | CA-004 | Development | Full high-risk compliance programme and provider obligations | Impact assessment; data representativeness; fairness testing; conformity strategy; instructions for use | AI Compliance Manager | Development Only | 2026-09-30 |

*Evidence for both entries is retained at Portfolio/Project3/AI-001 and Portfolio/Project3/AI-004 respectively.*

## 11. Deliverable 6: Exception Justification Template

**Template fields:** System ID/Name · Assessment reference · Annex III use area · Intended purpose · Why the task is narrow, procedural, preparatory or supportive · Why the output does not materially influence the relevant decision · Human review and override arrangements · Does the system perform profiling of natural persons? (Yes/No/Unclear) · Affected individuals and potential impacts · Evidence reviewed · Conditions required to preserve the exception · Change triggers requiring reassessment (purpose, functionality, data, users, scale, autonomy, geography, incidents, complaints, regulatory update) · Legal/compliance reviewer · Governance approver · Decision (Exception supported / Exception not supported / More evidence required) · Decision date and next review.

### Worked Example: Customer Support Chatbot

| Field | Detail |
|---|---|
| AI System | Customer Support Chatbot |
| Sensitive Context | Customer service interaction |
| Why Task Is Limited | Provides informational responses only. |
| Why Decision Influence Is Not Material | Does not approve, deny, or determine outcomes. |
| Human Review | Human agent escalation available. |
| Supporting Evidence | System design documents; user workflow analysis; functional testing reports |
| Approved By | AI Governance Committee |
| Approval Date | 15 March 2026 |
| Next Review | 15 June 2026 |

## 12. Deliverable 7: Regulatory Change Monitoring Log

The monitoring process records the official or internal source, change summary, potentially affected systems, classification impact, owner, due date, outcome, and retained evidence. Official EU sources are prioritized; internal product roadmaps, change requests, incident systems, and complaint channels feed into the same governance process.

| Monitor ID | Date Identified | Source Type | Source / Authority | Change Summary | Systems Affected | Classification Impact | Required Action | Owner | Due Date | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| MON-001 | 2026-08-31 | Official regulation baseline | EUR-Lex | Baseline review of Article 6, Article 7 and Annex III for portfolio methodology | All six systems | Establishes initial criteria | Maintain controlled copy and legal interpretation record | AI Compliance Manager | 2026-09-15 | Open |
| MON-002 | 2026-08-31 | Regulatory guidance | European Commission AI policy portal | Monitor Commission guidance and implementation material affecting classification | All systems | Potential clarification or change | Monthly review and log relevant updates | Regulatory Affairs Lead | 2026-09-30 | Open |
| MON-003 | 2026-08-31 | System change | Internal product roadmap | Customer chatbot may add refund recommendations and account actions | AI-003 | Could materially influence access to service | Block release until reclassification and impact assessment | Customer Experience Director | 2026-09-20 | Open |
| MON-004 | 2026-08-31 | Deployment expansion | Security programme plan | Security agent may be deployed in an environment supporting essential operations | AI-006 | Could change Annex III or sector risk analysis | Obtain legal/sector review before expansion | CISO | 2026-09-15 | In Progress |
| MON-005 | 2026-08-31 | Incident / complaint trigger | Operational monitoring | Any complaint indicating discriminatory, unsafe, or rights-impacting outcomes triggers reassessment | AI-001 and AI-004 | May challenge classification controls or exception rationale | Create automatic governance escalation rule | AI Governance Lead | 2026-09-30 | Open |

### Event-Driven Reassessment Triggers

- Change in intended purpose
- New output, recommendation, or automated action
- Increase in autonomy or tool access
- New data category or profiling activity
- Expansion to a new population, geography, or business process
- Provider, model, or architecture change
- Incident, complaint, audit finding, or new evidence of harm
- Regulatory amendment, guidance, or enforcement interpretation

## 13. Deliverable 8: Quarterly Reclassification Review Procedure

| Step | Detail |
|---|---|
| 1. Purpose | Confirm that each AI system classification remains valid and that changes are identified, assessed, approved, and evidenced. |
| 2. Scope | All inventoried AI systems in development, pilot, production, suspended, or retirement — including third-party, embedded, and internally developed AI. |
| 3. Frequency | Quarterly, plus event-driven reassessment when a trigger occurs. Organizations should set frequency based on risk and applicable obligations. |
| 4. Participants | AI Governance Lead, Compliance, Legal, Information Security, Data Governance, system owner, provider or procurement representative, and subject-matter experts as needed. |
| 5. Inputs | Current inventory; previous classification; intended-purpose statement; release and change logs; incidents; complaints; audit findings; performance and override data; regulatory monitoring log. |
| 6. Review steps | A. Confirm inventory completeness. B. Review system and regulatory changes. C. Re-run relevant questionnaire items. D. Validate exception conditions. E. Decide classification. F. Assign actions. G. Approve and archive evidence. |
| 7. Trigger events | New purpose; material feature; new output or action; autonomy increase; new data type; geographic expansion; additional affected population; provider/model change; incident; complaint; new evidence of harm; regulatory update. |
| 8. Outcomes | No change; classification changed to high-risk; classification changed to not high-risk; exception retained with conditions; exception withdrawn; legal review required; system paused pending evidence. |
| 9. Approval | Classification owner prepares the assessment; Legal or Compliance reviews; accountable governance body approves significant or high-risk decisions. |
| 10. Records | Retain the questionnaire, evidence list, decision rationale, reviewer comments, approval, conditions, actions, prior version, and next review date. |
| 11. Escalation | Escalate unclear classifications, profiling in an Annex III context, potential product-safety pathways, significant rights or safety impacts, and disputed exceptions. |
| 12. Metrics | Inventory coverage; assessments completed; overdue reviews; classification changes; exceptions; open evidence gaps; incidents triggering reassessment; actions closed on time. |

**Quarterly Review Record fields:** Review ID · Review Date · Systems Reviewed · Regulatory Updates · System Changes · Incidents/Complaints · Decisions · Actions · Approver

## 14. Executive Dashboard

| AI Systems | High-Risk | Conditional / Review | Not High-Risk |
|---|---|---|---|
| 6 | 2 | 2 | 2 |

| Classification | Count |
|---|---|
| High-Risk | 2 |
| Not High-Risk | 2 |
| Not High-Risk with Conditions | 1 |
| Review Required | 1 |

**Management Priorities:**

1. Complete Articles 8–15 governance controls for recruitment and creditworthiness systems.
2. Resolve the classification of the security alert prioritization agent before deployment expansion.
3. Preserve customer chatbot restrictions and reassess before enabling binding actions.
4. Formalize monthly regulatory monitoring and evidence retention.
5. Conduct quarterly and event-driven reclassification reviews.

## 15. Framework Alignment & Reference Register

| Project Component | EU AI Act | NIST AI RMF | ISO/IEC 42001 | ISO 31000 | Portfolio Evidence | Use Note |
|---|---|---|---|---|---|---|
| AI inventory and context | Articles 6–7; Annex III | MAP 1 and MAP 3 concepts | AI system inventory, context and lifecycle governance concepts | Scope, context and risk identification | Inventory register | Use the official consolidated legal text and applicable annexes. |
| Classification assessment | Article 6 | MAP context and impact understanding | Risk and impact assessment concepts | Risk identification and analysis | Questionnaire and six assessments | NIST AI RMF is voluntary guidance, used here for supporting governance structure. |
| Regulatory monitoring | Article 7 and relevant implementing material | GOVERN policy and legal requirements concepts | Compliance obligations and change management concepts | Monitoring and review | Monitoring log | Monitor official European Commission and EU sources. |
| Management system alignment | Supports ongoing Articles 6–7 governance | GOVERN and MAP | AI management system standard | Risk management principles | Review procedure and evidence | ISO pages describe the standard; full standard text may require licensed access. |
| Enterprise risk alignment | Risk-based classification support | MAP and GOVERN | Risk-management integration | Principles, framework and process | Decision rationale and approvals | Use organizational risk criteria; do not confuse risk tier with legal classification. |

NIST describes **MAP** as understanding context, intended purpose, affected individuals, and risks, while **GOVERN** focuses on accountability, oversight, and organizational processes.

## 16. Governance Controls

- No system enters production without inventory registration and classification.
- High-risk, conditional, and unclear results require independent Compliance or Legal review.
- Exceptions require written evidence and governance approval.
- Material changes cannot rely on the previous classification without reassessment.
- Regulatory updates, incidents, complaints, and evidence of harm are formal triggers.
- Classification versions, approvals, and evidence are retained as an audit trail.
- The high-risk register links each system to the required Articles 8–17 workstreams.

## 17. Compliance Matrix

| Requirement | Evidence |
|---|---|
| Article 6 Classification | Classification Assessments |
| High-Risk Register | High-Risk AI Register |
| Exception Review | Exception Templates |
| Governance Approval | Committee Records |
| Regulatory Monitoring | Monitoring Log |
| Reassessment Process | Quarterly Review Procedure |
| Continuous Governance | Reclassification History |

## 18. Evidence Index

- ☐ Controlled AI inventory
- ☐ Completed system questionnaires
- ☐ Intended-purpose statements
- ☐ Process and decision-flow diagrams
- ☐ Annex mapping and legal review
- ☐ Impact assessments
- ☐ Exception justifications
- ☐ Governance approvals and committee minutes
- ☐ Regulatory monitoring entries
- ☐ Change requests and release notes
- ☐ Incident and complaint records
- ☐ Prior classification versions and reclassification history

## 19. Management Recommendations

1. Prioritize compliance work for the recruitment and creditworthiness systems.
2. Do not permit autonomous containment by the security agent until classification and oversight are resolved.
3. Keep the chatbot limited to informational support unless reassessed.
4. Formalize monthly monitoring of official regulatory sources.
5. Review the inventory quarterly and after defined trigger events.
6. Integrate classification into procurement, change management, and product approval.

## 20. Skills Demonstrated

EU AI Act interpretation (Articles 6 & 7) · AI inventory management · High-risk classification · Evidence-based compliance analysis · Exception documentation · Regulatory horizon scanning · Change-impact assessment · Governance approval design · Stakeholder coordination · Executive reporting and audit evidence · NIST AI RMF and ISO/IEC 42001 application · Governance committee processes · Audit readiness

## 21. Portfolio Statement

Built a complete AI inventory and high-risk classification methodology for six fictional AI systems, documented classification decisions and conditional exceptions, established a formal high-risk AI register, and designed regulatory monitoring and reclassification processes aligned with EU AI Act Articles 6 and 7, NIST AI RMF, ISO/IEC 42001, and ISO 31000.

**Resume bullet:** Designed and implemented a High-Risk AI Classification and Regulatory Change Monitoring Programme, creating AI inventories, Article 6 classification methodologies, governance approval workflows, exception frameworks, regulatory monitoring processes, and reclassification procedures to support enterprise AI compliance and risk management under the EU AI Act.

## 22. References

- Regulation (EU) 2024/1689, official text: <https://eur-lex.europa.eu/eli/reg/2024/1689/oj>
- European Commission regulatory framework for AI: <https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai>
- European AI Office: <https://digital-strategy.ec.europa.eu/en/policies/ai-office>
- NIST AI Risk Management Framework: <https://www.nist.gov/itl/ai-risk-management-framework>
- ISO/IEC 42001 standard overview: <https://www.iso.org/standard/81230.html>
- ISO 31000 risk management overview: <https://www.iso.org/iso-31000-risk-management.html>

## 23. Limitations

This case study uses synthetic data and simplified workflows. Classification under the EU AI Act depends on the official legal text, applicable annexes, system facts, provider and deployer roles, sector law, and implementation guidance. Organizations should obtain qualified legal, regulatory, technical, security, and data-protection review before relying on a classification decision.
