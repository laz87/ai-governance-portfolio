# AI Compliance Mapping: Kenya AI Bill 2026, EU AI Act & NIST AI RMF

**Version:** 1.0  
**Date:** October 2025  
**Author:** laz87  
**Purpose:** Cross-reference regulatory requirements with practical controls for AI governance

---

## How to Use This Document

This mapping helps organizations understand what controls they need to implement to comply with multiple AI regulations simultaneously. Each requirement is mapped to:
- The specific regulation and article
- A practical control to implement
- The NIST AI RMF function it supports
- The relevant document in this portfolio

---

## 1. Governance & Accountability

| # | Requirement | Kenya AI Bill 2026 | EU AI Act | NIST AI RMF | Practical Control | Portfolio Doc |
|---|-------------|-------------------|-----------|-------------|-------------------|---------------|
| G1 | Designate AI governance body | Art. 12 — AI Commissioner | Art. 24 — Provider obligations | Govern: Organizational culture | Establish AI governance committee with defined roles | Risk Assessment §6.1 |
| G2 | Appoint responsible person | Art. 13 — Roles & responsibilities | Art. 15 — Governance measures | Govern: Roles & responsibilities | Assign AI system owner and accountability matrix | Acceptable Use Policy §5 |
| G3 | Document AI policies | Art. 14 — Policy framework | Art. 9 — Quality management | Govern: Policy development | Create and maintain AI acceptable use policy | Acceptable Use Policy |
| G4 | Stakeholder engagement | Art. 15 — Public consultation | Art. 61 — Stakeholder input | Govern: Stakeholder mapping | Maintain stakeholder register and engagement log | Risk Assessment §6.1 |
| G5 | Training & awareness | Art. 16 — Capacity building | Recital 32 — Training | Govern: Competency development | Conduct annual AI training for all staff | Acceptable Use Policy §9 |

---

## 2. Risk Assessment & Management

| # | Requirement | Kenya AI Bill 2026 | EU AI Act | NIST AI RMF | Practical Control | Portfolio Doc |
|---|-------------|-------------------|-----------|-------------|-------------------|---------------|
| R1 | Conduct risk assessment | Art. 18 — Risk classification | Art. 9 — Risk management | Map: Risk identification | Complete AI risk assessment template before deployment | Risk Assessment |
| R2 | Classify AI system risk level | Art. 18 — Unacceptable/High/Low risk | Art. 5-9 — Risk categories | Map: Context of operation | Classify each AI system by risk tier | Risk Assessment §1.2 |
| R3 | Prohibit unacceptable risk AI | Art. 19 — Banned practices | Art. 5 — Prohibited practices | Map: Impact assessment | Maintain list of prohibited AI use cases | Acceptable Use Policy §5.2 |
| R4 | Document risk treatment plan | Art. 20 — Mitigation measures | Art. 9(3) — Risk mitigation | Map: Risk characterization | Create risk treatment plan with owners and deadlines | Risk Assessment §7 |
| R5 | Monitor risks continuously | Art. 21 — Ongoing monitoring | Art. 61 — Post-market monitoring | Measure: Ongoing measurement | Implement continuous monitoring and alerting | Vendor Checklist §6.4 |

---

## 3. Data Governance

| # | Requirement | Kenya AI Bill 2026 | EU AI Act | NIST AI RMF | Practical Control | Portfolio Doc |
|---|-------------|-------------------|-----------|-------------|-------------------|---------------|
| D1 | Data quality & integrity | Art. 22 — Data requirements | Art. 10 — Data governance | Map: Data management | Audit training data for quality, bias, and provenance | Risk Assessment §3 |
| D2 | Data protection compliance | Art. 23 — Privacy protection | Art. 10(3) — Data protection | Map: Privacy risks | Ensure compliance with Kenya Data Protection Act 2019 | Acceptable Use Policy §4 |
| D3 | Data minimization | Art. 23(2) — Minimization | Art. 5(1)(c) — Data minimization | Map: Data inventory | Collect only data necessary for the AI purpose | Acceptable Use Policy §4.3 |
| D4 | Data provenance tracking | Art. 24 — Data documentation | Art. 10(3) — Data documentation | Map: Data lineage | Document all data sources and processing steps | Risk Assessment §3.3 |
| D5 | Consent for personal data | Kenya DPA §27 — Consent | GDPR Art. 6 — Lawful basis | Map: Consent management | Obtain and document consent before using personal data | Vendor Checklist §2.4 |
| D6 | Data retention limits | Kenya DPA §31 — Retention | GDPR Art. 5(1)(e) — Storage limitation | Map: Retention policy | Define and enforce data retention periods | Acceptable Use Policy §4.4 |
| D7 | Right to erasure | Kenya DPA §33 — Erasure | GDPR Art. 17 — Right to erasure | Map: Data subject rights | Implement process for data deletion requests | Vendor Checklist §2.9 |

---

## 4. Transparency & Explainability

| # | Requirement | Kenya AI Bill 2026 | EU AI Act | NIST AI RMF | Practical Control | Portfolio Doc |
|---|-------------|-------------------|-----------|-------------|-------------------|---------------|
| T1 | Inform users of AI interaction | Art. 26 — Disclosure | Art. 50 — Transparency obligations | Map: Transparency | Clearly label AI-generated content and interactions | Acceptable Use Policy §6.2 |
| T2 | Explain AI decisions | Art. 27 — Explainability | Art. 14 — Explainability | Measure: Performance | Provide explanations for AI-generated decisions | Risk Assessment §5.3 |
| T3 | Document system capabilities | Art. 28 — Technical documentation | Art. 11 — Documentation | Map: System documentation | Maintain technical documentation and model cards | Vendor Checklist §4 |
| T4 | Log AI interactions | Art. 29 — Record keeping | Art. 12 — Logging | Manage: Logging | Implement audit logging for all AI interactions | Acceptable Use Policy §7.2 |
| T5 | Watermark AI-generated content | Art. 30 — Content labeling | Art. 50(3) — Watermarking | Map: Content labeling | Apply watermarks or labels to AI-generated media | Acceptable Use Policy §6.2 |

---

## 5. Security & Robustness

| # | Requirement | Kenya AI Bill 2026 | EU AI Act | NIST AI RMF | Practical Control | Portfolio Doc |
|---|-------------|-------------------|-----------|-------------|-------------------|---------------|
| S1 | Cybersecurity measures | Art. 31 — Security requirements | Art. 15 — Security | Map: Security threats | Implement encryption, access controls, and MFA | Vendor Checklist §3 |
| S2 | Protect against attacks | Art. 32 — Adversarial robustness | Art. 15(2) — Robustness | Map: Adversarial risks | Test for prompt injection and adversarial attacks | Risk Assessment §4.3 |
| S3 | Accuracy & reliability | Art. 33 — Performance standards | Art. 15(3) — Accuracy | Measure: Accuracy testing | Define and monitor accuracy metrics | Vendor Checklist §6 |
| S4 | Incident reporting | Art. 34 — Breach notification | Art. 70 — Incident reporting | Manage: Incident response | Create AI-specific incident response plan | Acceptable Use Policy §7.3 |
| S5 | Human oversight | Art. 35 — Human control | Art. 14 — Human oversight | Manage: Human oversight | Implement human-in-the-loop for high-risk decisions | Acceptable Use Policy §8 |

---

## 6. Bias & Fairness

| # | Requirement | Kenya AI Bill 2026 | EU AI Act | NIST AI RMF | Practical Control | Portfolio Doc |
|---|-------------|-------------------|-----------|-------------|-------------------|---------------|
| F1 | Bias assessment | Art. 36 — Non-discrimination | Art. 10(2) — Bias assessment | Measure: Bias metrics | Test models for bias across demographic groups | Risk Assessment §4.2 |
| F2 | Fairness monitoring | Art. 37 — Ongoing fairness | Art. 61 — Post-market monitoring | Measure: Fairness metrics | Monitor outputs for discriminatory patterns | Vendor Checklist §5 |
| F3 | Remediation process | Art. 38 — Corrective action | Art. 61(2) — Corrective measures | Manage: Remediation | Establish process to address identified bias | Vendor Checklist §5.6 |
| F4 | Accessibility | Art. 39 — Equal access | Recital 11 — Accessibility | Map: Accessibility | Ensure AI systems are accessible to all users | Vendor Checklist §5.4 |

---

## 7. High-Risk AI Systems (Additional Requirements)

| # | Requirement | Kenya AI Bill 2026 | EU AI Act | NIST AI RMF | Practical Control | Portfolio Doc |
|---|-------------|-------------------|-----------|-------------|-------------------|---------------|
| H1 | Conformity assessment | Art. 40 — Certification | Art. 49 — Conformity | Map: Compliance | Obtain third-party certification for high-risk AI | Vendor Checklist §3 |
| H2 | CE marking / registration | Art. 41 — Registration | Art. 49 — Registration | Govern: Registration | Register high-risk AI systems with regulator | Risk Assessment §9 |
| H3 | Post-market monitoring | Art. 42 — Ongoing review | Art. 61 — Post-market | Measure: Monitoring | Implement continuous performance monitoring | Vendor Checklist §6.4 |
| H4 | Regulatory sandbox | Art. 43 — Innovation sandbox | Art. 57 — Sandboxes | Govern: Innovation | Participate in regulatory sandbox for testing | — |
| H5 | Product liability | Art. 44 — Liability framework | AI Liability Directive | Govern: Liability | Review insurance and liability coverage | Vendor Checklist §8 |

---

## 8. Third-Party & Supply Chain

| # | Requirement | Kenya AI Bill 2026 | EU AI Act | NIST AI RMF | Practical Control | Portfolio Doc |
|---|-------------|-------------------|-----------|-------------|-------------------|---------------|
| V1 | Vendor due diligence | Art. 45 — Third-party obligations | Art. 28 — Importers/distributors | Map: Supply chain | Complete vendor AI due diligence checklist | Vendor Checklist |
| V2 | Contractual safeguards | Art. 46 — Contract requirements | Art. 28(2) — Contracts | Govern: Contracts | Include AI-specific clauses in vendor contracts | Acceptable Use Policy §10 |
| V3 | Model provenance | Art. 47 — Model documentation | AI Act Annex III | Map: Provenance | Verify model source, training data, and version | Vendor Checklist §4 |
| V4 | Exit strategy | Art. 48 — Termination rights | Art. 28(3) — Exit | Govern: Exit planning | Ensure data portability and vendor exit options | Vendor Checklist §8 |

---

## 9. Enforcement & Penalties

| Regulation | Max Penalty | Enforcement Body |
|------------|-------------|-----------------|
| **Kenya AI Bill 2026** | KES 50 million or 5% of turnover | Office of the Data Protection Commissioner |
| **EU AI Act** | €35 million or 7% of global turnover | National competent authorities |
| **Kenya Data Protection Act** | KES 5 million or 1% of turnover | Office of the Data Protection Commissioner |
| **GDPR** | €20 million or 4% of global turnover | Data protection authorities |

---

## 10. Implementation Roadmap

### Phase 1: Foundation (Months 1-3)

| Action | Responsible | Deliverable |
|--------|-------------|-------------|
| Establish AI governance committee | CEO / Board | Committee charter |
| Inventory all AI systems in use | IT / AI team | AI system register |
| Classify AI systems by risk level | AI governance | Risk classification report |
| Adopt AI acceptable use policy | Legal / HR | Signed policy |
| Conduct initial risk assessments | AI governance | Completed risk assessments |

### Phase 2: Controls (Months 4-6)

| Action | Responsible | Deliverable |
|--------|-------------|-------------|
| Implement data governance controls | DPO | Data inventory & classification |
| Deploy monitoring and logging | IT security | AI monitoring dashboard |
| Complete vendor due diligence | Procurement | Vendor assessment reports |
| Train all employees on AI policy | HR / Training | Training completion records |
| Create incident response plan | CISO | AI incident response plan |

### Phase 3: Maturity (Months 7-12)

| Action | Responsible | Deliverable |
|--------|-------------|-------------|
| Conduct bias and fairness testing | AI team | Bias testing report |
| Perform red teaming exercises | Security team | Red team report |
| Register high-risk systems | Compliance | Registration certificates |
| Conduct first compliance audit | Internal audit | Audit report |
| Review and update all policies | AI governance | Updated policy suite |

---

## 11. Quick Compliance Checklist

Use this for rapid self-assessment:

### Must-Have (All Organizations Using AI)

- [ ] AI governance committee or designated owner
- [ ] AI acceptable use policy adopted
- [ ] Inventory of all AI systems in use
- [ ] Risk assessment completed for each system
- [ ] Data protection impact assessment (DPIA) for systems using personal data
- [ ] Employee AI training completed
- [ ] Incident response plan for AI incidents
- [ ] Vendor due diligence for third-party AI tools

### Should-Have (Organizations with High-Risk AI)

- [ ] Bias and fairness testing documented
- [ ] Human-in-the-loop processes for critical decisions
- [ ] Technical documentation and model cards
- [ ] Continuous monitoring and logging
- [ ] Post-deployment evaluation schedule
- [ ] User transparency and disclosure mechanisms
- [ ] Third-party conformity assessment

### Nice-to-Have (Mature AI Programs)

- [ ] ISO/IEC 42001 certification
- [ ] AI ethics board or advisory panel
- [ ] Participating in regulatory sandboxes
- [ ] Published AI transparency report
- [ ] Automated compliance monitoring tools
- [ ] AI insurance coverage

---

## 12. References

| Document | URL |
|----------|-----|
| Kenya AI Bill 2026 | [Parliament of Kenya](https://www.parliament.go.ke) |
| Kenya Data Protection Act 2019 | [ODPC Kenya](https://www.odpc.go.ke) |
| EU AI Act | [EUR-Lex](https://eur-lex.europa.eu) |
| NIST AI RMF 1.0 | [NIST](https://www.nist.gov/itl/ssd/software-quality-group/artificial-intelligence-rmf) |
| ISO/IEC 42001 | [ISO](https://www.iso.org) |
| GDPR | [EUR-Lex](https://eur-lex.europa.eu/eli/reg/2016/679/oj) |

---

*This mapping is for educational purposes and should be reviewed by legal counsel for compliance decisions. Regulations are subject to change.*
