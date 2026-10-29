# Vendor AI Due Diligence Checklist

**Version:** 1.0  
**Date:** October 2025  
**Author:** laz87  
**Purpose:** Evaluate third-party AI tools before organizational adoption

---

## Instructions

Complete this checklist before procuring or adopting any third-party AI tool. Each section must be reviewed by the relevant stakeholder. Tools scoring below 70% should not be adopted without remediation of critical items.

**Scoring:** ✅ Pass (1) | ⚠️ Partial (0.5) | ❌ Fail (0) | N/A (skip)

---

## 1. Vendor Information

| Field | Response |
|-------|----------|
| **Vendor name** | |
| **AI product name** | |
| **Product URL** | |
| **Contact person** | |
| **Evaluation date** | |
| **Evaluated by** | |
| **Intended use case** | |
| **Number of users** | |
| **Contract value** | |

---

## 2. Data Privacy & Protection (Weight: 25%)

| # | Question | ✅ | ⚠️ | ❌ | N/A | Evidence |
|---|----------|----|----|----|-----|----------|
| 2.1 | Does the vendor have a clear privacy policy? | ☐ | ☐ | ☐ | ☐ | |
| 2.2 | Is user data encrypted in transit (TLS 1.2+)? | ☐ | ☐ | ☐ | ☐ | |
| 2.3 | Is user data encrypted at rest (AES-256)? | ☐ | ☐ | ☐ | ☐ | |
| 2.4 | Does the vendor offer a Data Processing Agreement (DPA)? | ☐ | ☐ | ☐ | ☐ | |
| 2.5 | Can users opt out of data being used for model training? | ☐ | ☐ | ☐ | ☐ | |
| 2.6 | Where is data stored geographically? | ☐ | ☐ | ☐ | ☐ | |
| 2.7 | Does the vendor comply with Kenya Data Protection Act 2019? | ☐ | ☐ | ☐ | ☐ | |
| 2.8 | Does the vendor comply with GDPR (if EU users)? | ☐ | ☐ | ☐ | ☐ | |
| 2.9 | Can users request deletion of their data? | ☐ | ☐ | ☐ | ☐ | |
| 2.10 | Does the vendor notify users of data breaches within 72 hours? | ☐ | ☐ | ☐ | ☐ | |
| 2.11 | Does the vendor share data with third parties? If yes, which? | ☐ | ☐ | ☐ | ☐ | |
| 2.12 | Is there a data residency option (e.g., data stays in Africa/EU)? | ☐ | ☐ | ☐ | ☐ | |

**Section Score:** ___ / 12

---

## 3. Security Posture (Weight: 20%)

| # | Question | ✅ | ⚠️ | ❌ | N/A | Evidence |
|---|----------|----|----|----|-----|----------|
| 3.1 | Does the vendor have SOC 2 Type II certification? | ☐ | ☐ | ☐ | ☐ | |
| 3.2 | Does the vendor have ISO 27001 certification? | ☐ | ☐ | ☐ | ☐ | |
| 3.3 | Does the vendor conduct regular penetration testing? | ☐ | ☐ | ☐ | ☐ | |
| 3.4 | Is multi-factor authentication (MFA) supported? | ☐ | ☐ | ☐ | ☐ | |
| 3.5 | Is Single Sign-On (SSO/SAML) supported? | ☐ | ☐ | ☐ | ☐ | |
| 3.6 | Does the vendor have an incident response plan? | ☐ | ☐ | ☐ | ☐ | |
| 3.7 | Are API keys and credentials securely managed? | ☐ | ☐ | ☐ | ☐ | |
| 3.8 | Does the vendor provide audit logs? | ☐ | ☐ | ☐ | ☐ | |
| 3.9 | Has the vendor had any public security incidents in the last 2 years? | ☐ | ☐ | ☐ | ☐ | |
| 3.10 | Does the vendor offer role-based access control (RBAC)? | ☐ | ☐ | ☐ | ☐ | |

**Section Score:** ___ / 10

---

## 4. Model Transparency & Explainability (Weight: 15%)

| # | Question | ✅ | ⚠️ | ❌ | N/A | Evidence |
|---|----------|----|----|----|-----|----------|
| 4.1 | Does the vendor disclose the model architecture used? | ☐ | ☐ | ☐ | ☐ | |
| 4.2 | Is the training data source documented? | ☐ | ☐ | ☐ | ☐ | |
| 4.3 | Does the vendor provide model cards or technical reports? | ☐ | ☐ | ☐ | ☐ | |
| 4.4 | Can users understand why the model made a specific decision? | ☐ | ☐ | ☐ | ☐ | |
| 4.5 | Does the vendor disclose model limitations? | ☐ | ☐ | ☐ | ☐ | |
| 4.6 | Is the model version tracked and documented? | ☐ | ☐ | ☐ | ☐ | |
| 4.7 | Does the vendor provide confidence scores with outputs? | ☐ | ☐ | ☐ | ☐ | |

**Section Score:** ___ / 7

---

## 5. Bias & Fairness (Weight: 15%)

| # | Question | ✅ | ⚠️ | ❌ | N/A | Evidence |
|---|----------|----|----|----|-----|----------|
| 5.1 | Has the model been tested for bias across demographic groups? | ☐ | ☐ | ☐ | ☐ | |
| 5.2 | Does the vendor publish bias testing results? | ☐ | ☐ | ☐ | ☐ | |
| 5.3 | Is the training data representative of diverse populations? | ☐ | ☐ | ☐ | ☐ | |
| 5.4 | Does the model support multiple languages (including Swahili)? | ☐ | ☐ | ☐ | ☐ | |
| 5.5 | Can users report biased outputs? | ☐ | ☐ | ☐ | ☐ | |
| 5.6 | Does the vendor have a process to address identified bias? | ☐ | ☐ | ☐ | ☐ | |

**Section Score:** ___ / 6

---

## 6. Performance & Reliability (Weight: 10%)

| # | Question | ✅ | ⚠️ | ❌ | N/A | Evidence |
|---|----------|----|----|----|-----|----------|
| 6.1 | Is the model accuracy documented and measurable? | ☐ | ☐ | ☐ | ☐ | |
| 6.2 | Does the vendor provide SLA guarantees (uptime, response time)? | ☐ | ☐ | ☐ | ☐ | |
| 6.3 | Are performance metrics available for different use cases? | ☐ | ☐ | ☐ | ☐ | |
| 6.4 | Does the vendor monitor for model drift in production? | ☐ | ☐ | ☐ | ☐ | |
| 6.5 | Is there a fallback mechanism if the AI service is unavailable? | ☐ | ☐ | ☐ | ☐ | |

**Section Score:** ___ / 5

---

## 7. Intellectual Property & Licensing (Weight: 5%)

| # | Question | ✅ | ⚠️ | ❌ | N/A | Evidence |
|---|----------|----|----|----|-----|----------|
| 7.1 | Who owns the output generated by the AI tool? | ☐ | ☐ | ☐ | ☐ | |
| 7.2 | Does the vendor claim rights to user-generated content? | ☐ | ☐ | ☐ | ☐ | |
| 7.3 | Are there restrictions on commercial use of AI outputs? | ☐ | ☐ | ☐ | ☐ | |
| 7.4 | Is the licensing model clear and documented? | ☐ | ☐ | ☐ | ☐ | |

**Section Score:** ___ / 4

---

## 8. Business Continuity & Exit Strategy (Weight: 5%)

| # | Question | ✅ | ⚠️ | ❌ | N/A | Evidence |
|---|----------|----|----|----|-----|----------|
| 8.1 | Can data be exported in a standard format? | ☐ | ☐ | ☐ | ☐ | |
| 8.2 | Is there an API for programmatic data access? | ☐ | ☐ | ☐ | ☐ | |
| 8.3 | What happens to data if the contract is terminated? | ☐ | ☐ | ☐ | ☐ | |
| 8.4 | Is the vendor financially stable? | ☐ | ☐ | ☐ | ☐ | |
| 8.5 | Are there alternative vendors for similar functionality? | ☐ | ☐ | ☐ | ☐ | |

**Section Score:** ___ / 5

---

## 9. AI-Specific Security (Weight: 5%)

| # | Question | ✅ | ⚠️ | ❌ | N/A | Evidence |
|---|----------|----|----|----|-----|----------|
| 9.1 | Does the vendor protect against prompt injection attacks? | ☐ | ☐ | ☐ | ☐ | |
| 9.2 | Does the vendor filter harmful or inappropriate outputs? | ☐ | ☐ | ☐ | ☐ | |
| 9.3 | Is there rate limiting to prevent abuse? | ☐ | ☐ | ☐ | ☐ | |
| 9.4 | Does the vendor monitor for adversarial attacks? | ☐ | ☐ | ☐ | ☐ | |
| 9.5 | Does the vendor have a responsible AI policy? | ☐ | ☐ | ☐ | ☐ | |

**Section Score:** ___ / 5

---

## 10. Scoring Summary

| Section | Max Score | Weight | Weighted Score |
|---------|-----------|--------|----------------|
| 2. Data Privacy & Protection | 12 | 25% | ___ × 0.25 = ___ |
| 3. Security Posture | 10 | 20% | ___ × 0.20 = ___ |
| 4. Model Transparency | 7 | 15% | ___ × 0.15 = ___ |
| 5. Bias & Fairness | 6 | 15% | ___ × 0.15 = ___ |
| 6. Performance & Reliability | 5 | 10% | ___ × 0.10 = ___ |
| 7. IP & Licensing | 4 | 5% | ___ × 0.05 = ___ |
| 8. Business Continuity | 5 | 5% | ___ × 0.05 = ___ |
| 9. AI-Specific Security | 5 | 5% | ___ × 0.05 = ___ |
| **TOTAL** | **54** | **100%** | **___ / 54** |

---

## 11. Decision

### 11.1 Score Interpretation

| Score | Percentage | Decision |
|-------|-----------|----------|
| 43-54 | 80-100% | ✅ **Approved** — Low risk, proceed with adoption |
| 32-42 | 60-79% | ⚠️ **Conditional Approval** — Address medium-risk items within 30 days |
| 27-31 | 50-59% | ⚠️ **Conditional Approval** — Address all high-risk items before go-live |
| Below 27 | Below 50% | ❌ **Rejected** — Too many risks, do not adopt |

### 11.2 Critical Items (Must Pass)

The following items are **mandatory**. Failure on any blocks approval:

- [ ] 2.4 — Data Processing Agreement available
- [ ] 2.5 — Opt out of training data usage
- [ ] 3.4 — Multi-factor authentication supported
- [ ] 3.6 — Incident response plan exists
- [ ] 7.1 — Clear output ownership
- [ ] 8.1 — Data export capability
- [ ] 9.2 — Output filtering for harmful content

### 11.3 Recommendation

| Role | Name | Recommendation | Signature | Date |
|------|------|----------------|-----------|------|
| AI Governance Lead | | ☐ Approve ☐ Conditional ☐ Reject | | |
| Data Protection Officer | | ☐ Approve ☐ Conditional ☐ Reject | | |
| CISO / Security Lead | | ☐ Approve ☐ Conditional ☐ Reject | | |
| Legal Counsel | | ☐ Approve ☐ Conditional ☐ Reject | | |

### 11.4 Conditions for Approval

[List any conditions that must be met before or after adoption]

1. 
2. 
3. 

---

## 12. Ongoing Monitoring

If approved, the following monitoring is required:

| Activity | Frequency | Owner |
|----------|-----------|-------|
| Review vendor security certifications | Annually | CISO |
| Assess vendor incident reports | As they occur | Security team |
| Re-evaluate bias testing results | Semi-annually | AI Governance |
| Review contract and DPA terms | Annually | Legal |
| User satisfaction and issue survey | Quarterly | Product owner |

---

*This checklist should be completed before any procurement decision. Consult legal counsel for binding decisions.*
