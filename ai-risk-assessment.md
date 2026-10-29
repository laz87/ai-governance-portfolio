# AI System Risk Assessment Template

**Based on:** NIST AI Risk Management Framework (AI RMF) v1.0  
**Version:** 1.0  
**Date:** October 2025  
**Author:** laz87

---

## 1. System Overview

| Field | Value |
|-------|-------|
| **System Name** | [e.g., Customer Service Chatbot] |
| **System Owner** | [Department/Team] |
| **Assessor** | [Name] |
| **Assessment Date** | [YYYY-MM-DD] |
| **AI System Type** | [Chatbot / Recommendation / Classification / Generation / Other] |
| **Deployment Scope** | [Internal / Customer-facing / Public] |
| **Data Sources** | [List data sources used by the system] |

### 1.1 System Description

[Briefly describe what the AI system does, who uses it, and what decisions it supports.]

### 1.2 Intended Use

- **Primary purpose:** [Describe]
- **Target users:** [Describe]
- **Decision impact:** [Low / Medium / High / Critical]
- **Human oversight:** [Yes / No — describe level]

---

## 2. Risk Assessment Matrix

### 2.1 Risk Rating Scale

| Level | Score | Description |
|-------|-------|-------------|
| **Critical** | 20-25 | Severe impact, highly likely — immediate action required |
| **High** | 12-16 | Significant impact, likely — urgent remediation |
| **Medium** | 6-9 | Moderate impact, possible — planned remediation |
| **Low** | 1-5 | Minor impact, unlikely — monitor and accept |

**Formula:** Risk Score = Impact (1-5) × Likelihood (1-5)

---

## 3. Data Risks (NIST AI RMF: Map)

### 3.1 Data Quality

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| D1 | Training data contains outdated or inaccurate information | | | | | |
| D2 | Training data has sampling bias (under/over-representation) | | | | | |
| D3 | Data labels are inconsistent or incorrectly assigned | | | | | |
| D4 | Data drift between training and production environments | | | | | |
| D5 | Insufficient data volume for reliable model performance | | | | | |

### 3.2 Data Privacy

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| D6 | Personal data used without proper consent | | | | | |
| D7 | Sensitive data (PII, health, financial) in training set | | | | | |
| D8 | Data retention exceeds policy requirements | | | | | |
| D9 | Data shared with third-party vendors without DPA | | | | | |
| D10 | Model memorization — system can reproduce training data | | | | | |

### 3.3 Data Provenance

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| D11 | Training data source is unknown or unverified | | | | | |
| D12 | Data was synthetically generated without documentation | | | | | |
| D13 | Copyrighted content used without permission | | | | | |

---

## 4. Model Risks (NIST AI RMF: Map)

### 4.1 Model Performance

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| M1 | Model accuracy below acceptable threshold | | | | | |
| M2 | Model performance degrades over time (concept drift) | | | | | |
| M3 | Model performs differently across demographic groups | | | | | |
| M4 | Model produces inconsistent outputs for similar inputs | | | | | |
| M5 | Model fails on edge cases or out-of-distribution inputs | | | | | |

### 4.2 Model Bias & Fairness

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| M6 | Systematic bias against protected groups (race, gender, age) | | | | | |
| M7 | Geographic or linguistic bias (e.g., Swahili vs. English) | | | | | |
| M8 | Socioeconomic bias (favoring certain income groups) | | | | | |
| M9 | Historical bias encoded in training data | | | | | |

### 4.3 Model Security

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| M10 | Adversarial attacks — crafted inputs cause misclassification | | | | | |
| M11 | Model inversion — attacker extracts training data | | | | | |
| M12 | Model extraction — attacker replicates the model | | | | | |
| M13 | Prompt injection (for LLM-based systems) | | | | | |
| M14 | Data poisoning — malicious data in training set | | | | | |

---

## 5. Output Risks (NIST AI RMF: Measure)

### 5.1 Output Accuracy

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| O1 | System generates factually incorrect information (hallucination) | | | | | |
| O2 | System provides outdated recommendations | | | | | |
| O3 | System gives conflicting advice across sessions | | | | | |

### 5.2 Output Safety

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| O4 | System generates harmful or dangerous content | | | | | |
| O5 | System produces discriminatory or offensive language | | | | | |
| O6 | System reveals sensitive information from training data | | | | | |
| O7 | System output can be manipulated to perform actions | | | | | |

### 5.3 Output Transparency

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| O8 | Users cannot tell they are interacting with AI | | | | | |
| O9 | System cannot explain its reasoning or decisions | | | | | |
| O10 | Confidence scores are not provided with outputs | | | | | |

---

## 6. Organizational Risks (NIST AI RMF: Govern)

### 6.1 Governance

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| G1 | No designated AI governance owner or committee | | | | | |
| G2 | No documented AI policies or procedures | | | | | |
| G3 | Lack of employee training on AI risks and responsible use | | | | | |
| G4 | No incident response plan for AI-related incidents | | | | | |

### 6.2 Compliance

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| G5 | Non-compliance with Kenya Data Protection Act 2019 | | | | | |
| G6 | Non-compliance with Kenya AI Bill 2026 requirements | | | | | |
| G7 | Non-compliance with EU AI Act (if serving EU users) | | | | | |
| G8 | Inadequate documentation for regulatory audits | | | | | |

### 6.3 Third-Party Risk

| # | Risk | Impact (1-5) | Likelihood (1-5) | Score | Status | Mitigation |
|---|------|--------------|-----------------|-------|--------|------------|
| G9 | Reliance on opaque third-party AI models (black box) | | | | | |
| G10 | Third-party vendor data handling practices unknown | | | | | |
| G11 | Vendor lock-in — inability to migrate away from provider | | | | | |
| G12 | No exit strategy if vendor service is discontinued | | | | | |

---

## 7. Risk Treatment Plan

### 7.1 Risk Response Options

For each identified risk, select a response:

| Option | Description | When to Use |
|--------|-------------|-------------|
| **Mitigate** | Implement controls to reduce risk | High/Critical risks |
| **Transfer** | Share risk with third party (e.g., insurance) | Medium risks with vendor involvement |
| **Accept** | Acknowledge and monitor risk | Low risks with manageable impact |
| **Avoid** | Discontinue the activity causing the risk | Unacceptable risks with no mitigation |

### 7.2 Treatment Summary

| Risk ID | Risk Description | Response | Owner | Deadline | Status |
|---------|-----------------|----------|-------|----------|--------|
| | | | | | |
| | | | | | |

---

## 8. Controls Mapping (NIST AI RMF)

### 8.1 Govern Function

| Control | Implemented | Evidence |
|---------|-------------|----------|
| AI policy and code of conduct | ☐ Yes ☐ No | |
| AI governance committee established | ☐ Yes ☐ No | |
| Roles and responsibilities defined | ☐ Yes ☐ No | |
| Stakeholder engagement process | ☐ Yes ☐ No | |
| Compliance monitoring program | ☐ Yes ☐ No | |

### 8.2 Map Function

| Control | Implemented | Evidence |
|---------|-------------|----------|
| Data inventory and classification | ☐ Yes ☐ No | |
| Risk assessment completed | ☐ Yes ☐ No | |
| Bias testing methodology | ☐ Yes ☐ No | |
| Adversarial threat modeling | ☐ Yes ☐ No | |
| Impact assessment documented | ☐ Yes ☐ No | |

### 8.3 Measure Function

| Control | Implemented | Evidence |
|---------|-------------|----------|
| Performance metrics defined | ☐ Yes ☐ No | |
| Bias metrics tracked | ☐ Yes ☐ No | |
| Accuracy testing across groups | ☐ Yes ☐ No | |
| Red teaming / adversarial testing | ☐ Yes ☐ No | |
| Continuous monitoring in place | ☐ Yes ☐ No | |

### 8.4 Manage Function

| Control | Implemented | Evidence |
|---------|-------------|----------|
| Incident response plan for AI | ☐ Yes ☐ No | |
| Model versioning and rollback | ☐ Yes ☐ No | |
| Human oversight procedures | ☐ Yes ☐ No | |
| User feedback mechanism | ☐ Yes ☐ No | |
| Regular audit schedule | ☐ Yes ☐ No | |

---

## 9. Overall Risk Rating

| Category | Count: Critical | Count: High | Count: Medium | Count: Low |
|----------|----------------|-------------|---------------|------------|
| Data Risks | | | | |
| Model Risks | | | | |
| Output Risks | | | | |
| Organizational Risks | | | | |
| **TOTAL** | | | | |

### 9.1 Deployment Recommendation

| Overall Risk | Recommendation |
|--------------|---------------|
| Any Critical (unmitigated) | ❌ **Do not deploy** — address critical risks first |
| 1-2 High (unmitigated) | ⚠️ **Deploy with conditions** — implement mitigations within 30 days |
| Medium and below | ✅ **Approved for deployment** — continue monitoring |

---

## 10. Sign-Off

| Role | Name | Signature | Date |
|------|------|-----------|------|
| System Owner | | | |
| AI Governance Lead | | | |
| Data Protection Officer | | | |
| Legal Counsel | | | |
| CISO / Security Lead | | | |

---

## 11. Review Schedule

- **Initial assessment:** [Date]
- **Next review:** [Date + 6 months]
- **Trigger events for reassessment:**
  - Model retraining or version update
  - Change in data sources
  - Regulatory changes
  - Security incident involving the AI system
  - User complaint about AI output

---

*This template is based on the NIST AI Risk Management Framework and adapted for Kenyan regulatory context. Review with legal counsel before organizational use.*
