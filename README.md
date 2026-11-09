# FinSecure | Third-Party Cybersecurity Risk Assessment & GRC Portfolio

> **Portfolio case study · Simulated scenario · November 2026**

A practical, end-to-end Third-Party Risk Management (TPRM) case study demonstrating how a cybersecurity / GRC analyst can assess a cloud service provider before the provider is permitted to process sensitive customer information.

**Decision outcome:** *Conditional approval in principle — not cleared for production onboarding.*

All organisations, vendor responses, assessment results, ratings and evidence-status records in this repository are fictional and created for learning and portfolio demonstration. This is **not** a real client engagement, vendor audit, certification assessment, legal opinion or independent validation exercise.

---

## 1. Project at a glance

| Item | Description |
|---|---|
| Client (fictional) | FinSecure Technologies |
| Third party (fictional) | CloudNova Solutions |
| Service | Cloud hosting and backup of customer / transaction data |
| Role simulated | Third-Party Risk Management (TPRM) Analyst |
| Assessment type | Pre-onboarding cybersecurity, privacy and resilience review |
| Overall posture | High / provisional |
| Recommendation | Conditional approval in principle; no production data transfer until critical gates are closed |

### Business scenario

FinSecure Technologies is considering CloudNova Solutions to host and back up customer database services. The proposed data scope includes customer identifiers and contact details, account information, transaction records, personal identification information and backups.

The analyst's task is to evaluate the vendor's reported security posture, identify gaps, document risks, recommend remediation and provide a risk-based onboarding recommendation to management.

## 2. Objectives

- Establish a structured third-party due diligence and assessment workflow.
- Classify the vendor and proposed service based on criticality and data sensitivity.
- Review simulated vendor questionnaire responses and identify evidence requirements.
- Assess security, privacy, subcontractor and business continuity controls.
- Record inherent risk, control gaps, remediation actions and residual-risk considerations.
- Map selected control themes to recognised frameworks.
- Communicate the findings and onboarding recommendation to management.

## 3. Repository guide

| Folder / file | Purpose |
|---|---|
| `01_Project_Overview/` | Project brief, scope, scenario and workflow |
| `02_Methodology/` | Assessment method, scoring model and decision logic |
| `03_Assessment_Deliverables/` | Five completed assessment artefacts |
| `04_Simulated_Evidence/` | Fictional vendor response snapshot and evidence request tracker |
| `05_Reference_and_Governance/` | Framework references, limitations and responsible-use notes |

### Completed deliverables

1. **Vendor Risk Assessment Workbook** — vendor profile, classification, due diligence questionnaire, evidence register, risk register, control assessment, remediation tracker, residual-risk decision and monitoring.
2. **Third-Party Risk Assessment Report** — executive summary, scope, methodology, findings, risks, remediation and conclusion.
3. **GRC Framework & Compliance Mapping** — selected mappings and preliminary gap analysis against ISO/IEC 27001:2022, NIST CSF 2.0, GDPR (where applicable), India's DPDP framework and ISO 22301:2019.
4. **Privacy & Business Continuity Assessment** — data protection considerations, BIA, MTD, RTO, RPO, BCP / DRP and recovery testing recommendations.
5. **Executive Risk Presentation** — management-level findings, risk posture, remediation gates and approval recommendation.

## 4. Assessment workflow

1. Define the business service, data types and assessment boundary.
2. Classify the vendor and service criticality.
3. Issue due diligence questions and request supporting evidence.
4. Review responses; distinguish reported controls from verified controls.
5. Identify control gaps and assess likelihood × impact.
6. Document findings, owners, remediation and target gates.
7. Consider privacy, subcontractor, continuity and contractual requirements.
8. Recommend onboarding disposition and monitoring.
9. Escalate residual-risk acceptance to an authorised business / risk owner.

## 5. Key simulated findings

| ID | Finding | Illustrative rating |
|---|---|---|
| F-01 | Disaster recovery exercise / restoration evidence not confirmed | Critical |
| F-02 | Subprocessor inventory and oversight only partially established | Critical |
| F-03 | Periodic access reviews only partially established | High |
| F-04 | Independent assurance not provided / not validated | High |
| F-05 | Retention and secure deletion procedures partially documented | High |

The ratings are provisional and based on the fictional scenario and the illustrative scoring criteria in this repository.

## 6. Risk scoring

**Risk score = Likelihood (1–5) × Impact (1–5)**

| Score | Illustrative band |
|---:|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

These are case-study scoring bands, not a universal regulatory or industry standard. Actual organisations should use their approved risk methodology and calibrate ratings to their risk appetite.

## 7. Management recommendation

**Conditional approval in principle — NOT CLEARED FOR PRODUCTION ONBOARDING.**

Do not transfer production customer data until the critical evidence and remediation gates are completed, contractual safeguards are agreed, and an authorised risk owner has formally accepted any remaining residual risk.

Priority gates include:
- Execute and document a disaster recovery exercise and database restoration test; establish achieved RTO / RPO.
- Obtain a complete subprocessor inventory, risk reviews and contractual flow-down commitments.
- Agree data processing, security, breach notification, data location / transfer, retention, return and secure deletion terms.
- Validate privileged access, MFA and periodic access review controls.
- Review independent assurance or complete an appropriate alternative control assessment.

The TPRM analyst documents and recommends; the authorised business / risk owner makes the formal risk acceptance decision.

## 8. Frameworks considered

- **ISO/IEC 27001:2022** — information security management systems and control themes.
- **NIST Cybersecurity Framework 2.0** — Govern, Identify, Protect, Detect, Respond and Recover.
- **ISO 22301:2019** — business continuity management.
- **GDPR** — only where its territorial and processing scope applies.
- **India Digital Personal Data Protection Act, 2023 and DPDP Rules, 2025** — applicability and obligations must be assessed in light of phased commencement and the facts of the processing.

Mappings in this project are illustrative crosswalks, not claims of certification or complete legal compliance.

## 9. How to review this project

Recommended reading order:
1. Start with this README.
2. Open the Executive Risk Presentation for the management narrative.
3. Review the Third-Party Risk Assessment Report for detailed findings.
4. Explore the Vendor Risk Assessment Workbook for working registers.
5. Review the GRC Mapping Workbook and Privacy / Business Continuity Assessment.
6. Inspect the simulated evidence folder and methodology notes to understand assumptions and traceability.

## 10. Disclaimer

This repository is an educational portfolio case study. FinSecure Technologies and CloudNova Solutions are fictional names. All vendor responses and findings are simulated. No real vendor documentation, penetration test, audit report, certificate, contractual document or personal data is represented as having been obtained. No control was independently tested. The project is not legal advice, an audit opinion, a certification or a statement that any real organisation complies with a framework.

---

**Suggested portfolio description:**  
Designed an end-to-end simulated TPRM assessment for a fictional cloud service provider, including due diligence, risk scoring, control gap analysis, privacy and business continuity considerations, remediation tracking and an executive onboarding recommendation.
