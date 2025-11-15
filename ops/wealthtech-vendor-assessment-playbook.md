# WealthTech Vendor Assessment Playbook  
*A Platinum-Standard Operational Playbook for HNWI, SFO, and MFO Clients*  
**Version 1.0 — Complete Document**

---

## 1. Purpose & Scope

This playbook defines a complete, end-to-end methodology for assessing WealthTech vendors used by High-Net-Worth Individuals (HNWI), Single-Family Offices (SFO), and Multi-Family Offices (MFO). The purpose is to:

- Protect client assets and private family information  
- Assess and monitor vendor cybersecurity posture  
- Evaluate operational maturity and financial stability  
- Create a defensible record of due diligence  
- Assist advisors in vendor comparison, selection, and oversight  

This framework applies to any technology provider who stores, processes, aggregates, or transmits data belonging to a family office or its clients.

---

## 2. WealthTech Vendor Landscape

WealthTech vendors typically fall into the following categories, each with distinct risk profiles.

### 2.1 Portfolio Accounting & Reporting Platforms
**Examples:** Addepar, Black Diamond, SEI, Orion.

**Key risks:**
- Incorrect or inconsistent data aggregation  
- Black-box calculations with no auditability  
- API instability  
- Poor reconciliation workflows  
- Data transformations that create reporting inaccuracies  

### 2.2 Financial Planning & Modeling Tools
**Examples:** eMoney, MoneyGuidePro.

**Key risks:**
- Divergent assumptions that lead to flawed planning output  
- Data sync reliability issues  
- Weak role-based access models for multi-generational families  

### 2.3 Account Aggregators & Data Connectivity Vendors
**Examples:** Plaid, MX, Yodlee.

**Key risks:**
- Token misuse or over-permissioned access  
- Excessive data retention  
- Aggregator outages impacting mission-critical reporting  
- Cross-platform exposure if aggregator suffers a breach  

### 2.4 Trading, Rebalancing & Execution Tools
**Key risks:**
- Trade execution delays  
- Integration failures with custodians  
- Weak approval workflows  
- Entitlement misconfiguration  

### 2.5 Digital Vaults, Estate, Tax & Legal Collaboration Tools
**Key risks:**
- Sensitive documents stored in third-party environments  
- Poor deletion workflows leading to shadow data  
- Data broker risk if vendor monetizes or shares metadata  
- Weak mobile app protections  

---

## 3. Due Diligence Framework (End-to-End)

The due diligence process consists of five structured phases.

---

### 3.1 Phase 1 — Discovery & Scoping
Establish foundations:

- Define primary use case(s)  
- Identify all data classes involved (PII, PHI, financial data, account tokens)  
- Map internal + external stakeholders  
- Identify vendor dependencies (subprocessors, hosting platforms)  
- Identify whether the vendor requires:  
  - View-only access  
  - Transactional authority  
  - Data aggregation tokens  
  - API connectivity to custodians  

Deliverable: **Vendor Data Exposure Map**

---

### 3.2 Phase 2 — Security Assessment

Evaluate the vendor’s security posture across:

#### Identity & Access Management
- MFA availability  
- SSO/SCIM support  
- Privileged access management  
- Customer-level segregation  

#### Infrastructure Security
- Cloud platform (AWS/Azure/GCP) maturity  
- Network segmentation  
- Encryption at rest/in transit  
- Key management ownership  
- Infrastructure-as-code governance  

#### Application Security
- Secure SDLC documentation  
- Static/dynamic code scanning  
- Dependency vulnerability monitoring  
- Bug bounty program  
- Penetration testing frequency and scope  

#### Incident Response
- Disclosure timeline commitments  
- Recent incidents (5-year lookback)  
- Post-incident transparency  
- Disaster recovery maturity  

Deliverable: **Security Risk Evaluation Worksheet**

---

### 3.3 Phase 3 — Privacy Assessment

Evaluate:

- Data collection minimization  
- Legal basis for processing  
- Data profiling practices  
- Data retention/deletion timelines  
- Data broker partnerships  
- Cross-border data transfers  
- Ability to honor right-to-delete  
- Clarity and honesty in privacy policies  

Deliverable: **PII Exposure Index**

---

### 3.4 Phase 4 — Operational & Financial Assessment

#### Operational Resilience
- Uptime history (rolling 12 months)  
- Quality of customer support  
- SLAs for incidents & response  
- Versioning & change management  

#### Financial Health
- Funding history  
- Cash runway calculation  
- Customer concentration risks  
- Executive turnover  
- Regulatory investigations  
- Litigation history  

Deliverable: **Operational Maturity Scorecard**

---

### 3.5 Phase 5 — Scoring, Recommendation & Documentation

Each vendor receives a weighted, quantitative score.

---

## 4. Scoring Model (Weighted & Complete)

| Domain | Weight | Description |
|--------|--------|-------------|
| **Security** | 30% | Security engineering maturity, infrastructure robustness, incident history |
| **Privacy** | 20% | Data handling discipline, regulatory compliance, transparency |
| **Operational Reliability** | 20% | Platform stability, DR/BCP design, support quality |
| **Financial Viability** | 15% | Long-term stability & continuity risk |
| **Capability Fit** | 10% | Alignment with client needs & integration quality |
| **Partner Quality** | 5% | Cultural fit, transparency, communication style |

Scoring:
- **5 — Platinum**  
- **4 — Strong**  
- **3 — Acceptable with conditions**  
- **2 — Weak**  
- **1 — Not viable**

Deliverable: **Vendor Score Summary**

---

## 5. Required Documents Checklist

The vendor must provide:

- SOC 2 Type II (mandatory)  
- Penetration test report (summary OK)  
- Security & privacy policies  
- Subprocessor list  
- Data flow diagrams  
- Cyber insurance certificate  
- Incident response plan  
- Breach notification timeline  
- BCP/DR testing results  
- Architecture overview  
- Audit logging overview  

Missing or withheld documents automatically increase risk severity.

---

## 6. Questionnaire (Full Version)

### 6.1 Questions for the Vendor
- Do you use customer data to train machine learning models?  
- What data do you store that is not strictly required for your service?  
- Describe your data isolation model.  
- What is your RTO/RPO objective and tested capability?  
- Do you conduct annual pen tests by independent parties?  
- How soon do you notify customers after detecting an incident?  
- Who are your subprocessors and what data do they receive?  

### 6.2 Questions for Internal Stakeholders
- What is the vendor’s criticality level?  
- How sensitive is the data they will receive?  
- Does the vendor require transactional authority or trading access?  
- Is there an alternative vendor with lower risk?  
- Is the vendor’s feature set essential or “nice to have”?  

---

## 7. Comparison Matrix (Template)

| Vendor | Security | Privacy | Reliability | Fit | Financials | Overall |
|--------|----------|---------|-------------|------|-------------|---------|
| Vendor A | 4.7 | 4.3 | 4.8 | 4.9 | 4.1 | **4.6** |
| Vendor B | 3.8 | 3.9 | 3.6 | 4.1 | 3.4 | **3.8** |
| Vendor C | 2.9 | 3.1 | 3.2 | 3.6 | 2.8 | **3.1** |

Deliverable: **Final Vendor Recommendation Report**

---

## 8. Implementation Controls

If vendor is approved:

- Use least-privilege access  
- Enable MFA by default  
- Require SSO + SCIM provisioning  
- Rotate API access tokens every 90 days  
- Prohibit shared family member logins  
- Export audit logs to your environment  
- Isolate vendor inside a vendor-specific network segment  

---

## 9. Vendor Offboarding Checklist

Upon termination:

1. Request certificate of deletion  
2. Revoke SSO access  
3. Delete or rotate API keys  
4. Export final data set  
5. Validate that no shadow data exists  
6. Update asset registry  
7. Archive due diligence file  

Deliverable: **Vendor Offboarding Record**

---

## 10. Executive Summary Template

[Vendor Name] was evaluated across security, privacy, operational resilience, financial stability, and capability fit. Based on weighted scoring, the vendor received an overall score of [X.X]. The vendor is recommended / recommended with  conditions / not recommended for use within the Family Office  environment.

Key Strengths:
- [List]

Key Risks:
- [List]

Required Mitigations:
- [List]

---

# **End of Document**

