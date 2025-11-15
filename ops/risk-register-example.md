# Example Risk Register  
*Sample Risk Entries for Family Offices*  
**Version 1.0 — Complete Document**

---

Below are **12 fully developed example risks**, aligned with the master schema. These can be copied directly into your repository or used as templates.

---

## **Risk 1 — Compromise of Family Email Accounts**

- **Risk ID:** FO-RISK-001  
- **Category:** Cybersecurity  
- **Subcategory:** Identity & Access  
- **Risk Title:** Compromise of family email accounts due to weak MFA  
- **Description:**  
  Family email accounts may be compromised if MFA is not consistently enforced across all identities. Attackers can leverage leaked credentials, phishing, or SIM-swap attacks to gain access. A successful compromise exposes financial data, estate documents, personal schedules, and sensitive communications.
- **Assets Affected:** Email accounts, cloud storage, identity records  
- **Threat Actors:** Cybercriminals, stalkers, extortionists  
- **Likelihood:** 4  
- **Impact:** 5  
- **Inherent Risk:** Critical  
- **Existing Controls:** MFA enabled for most accounts, password manager  
- **Gaps:** Two family members lack enrolled MFA  
- **Residual Likelihood:** 3  
- **Residual Impact:** 5  
- **Residual Rating:** High  
- **Mitigation Plan:** Enroll remaining users in MFA; review logins monthly  
- **Owner:** Family Office Tech Lead  
- **Review Date:** 30 days  
- **Status:** In Progress  

---

## **Risk 2 — Exposure of Home Address via Data Brokers**

- **Risk ID:** FO-RISK-002  
- **Category:** Privacy  
- **Subcategory:** Digital Footprint  
- **Risk Title:** Exposure of home address via public data brokers  
- **Description:**  
  Data brokers often publish home addresses tied to family member names. This increases stalking, harassment, burglary, and kidnapping risks.
- **Assets Affected:** Home address, family members  
- **Threat Actors:** Criminals, stalkers, paparazzi  
- **Likelihood:** 5  
- **Impact:** 4  
- **Inherent:** Critical  
- **Controls:** Broker removal in progress  
- **Gaps:** 7 data brokers still have listings  
- **Residual:** High  
- **Mitigation:** Complete removals + monthly monitoring  
- **Owner:** Privacy Officer  
- **Status:** In Progress  

---

## **Risk 3 — Smart Home Device Compromise**

- **Risk ID:** FO-RISK-003  
- **Category:** Cybersecurity  
- **Subcategory:** IoT  
- **Risk Title:** Smart home devices exploited due to insecure configuration  
- **Description:**  
  Smart TVs, thermostats, and cameras may expose the household to eavesdropping or surveillance.
- **Likelihood:** 3  
- **Impact:** 5  
- **Inherent:** High  
- **Controls:** Router firewall, basic segmentation  
- **Gaps:** IoT VLAN not fully implemented  
- **Residual:** Medium  
- **Mitigation:** Implement IoT VLAN + firmware audits  
- **Owner:** IT MSP  
- **Status:** Planned  

---

## **Risk 4 — Travel Theft of Devices**

- **Risk ID:** FO-RISK-004  
- **Category:** Travel  
- **Title:** Loss or theft of devices during travel  
- **Description:**  
  Devices may be stolen from hotels, airports, or taxis, leading to identity theft or sensitive data exposure.
- **Likelihood:** 4  
- **Impact:** 4  
- **Controls:** Travel phone used, Find My enabled  
- **Gaps:** Travel laptop not encrypted  
- **Residual:** High  
- **Mitigation:** Enable full disk encryption  
- **Owner:** Security Team  

---

## **Risk 5 — Vendor Breach of Sensitive Documents**

- **Risk ID:** FO-RISK-005  
- **Category:** Vendor  
- **Title:** Document storage vendor breach  
- **Likelihood:** 3  
- **Impact:** 5  
- **Controls:** SOC 2 review  
- **Gaps:** No breach notification SLA  
- **Residual:** High  

---

## **Risk 6 — SIM-Swap Attack**

- **Risk ID:** FO-RISK-006  
- **Category:** Cybersecurity  
- **Subcategory:** Identity  
- **Likelihood:** 4  
- **Impact:** 5  
- **Controls:** Carrier PIN  
- **Gaps:** Carrier does not support advanced SIM protection  
- **Residual:** High  

---

## **Risk 7 — Insider Threat from Household Staff**

- **Risk ID:** FO-RISK-007  
- **Category:** Operational  
- **Title:** Insider access to sensitive information  
- **Likelihood:** 2  
- **Impact:** 5  
- **Residual:** Medium  
- **Mitigation:** Staff background checks + asset restrictions  

---

## **Risk 8 — Investment Fraud Targeting a Family Member**

- **Risk ID:** FO-RISK-008  
- **Category:** Financial  
- **Likelihood:** 3  
- **Impact:** 5  
- **Controls:** Advisor oversight  
- **Gaps:** No scam-awareness training  
- **Residual:** High  

---

## **Risk 9 — Weak Home Wi-Fi Password**

- **Risk ID:** FO-RISK-009  
- **Category:** Cybersecurity  
- **Likelihood:** 3  
- **Impact:** 4  
- **Controls:** WPA3 router  
- **Gaps:** Weak PSK  
- **Residual:** Medium  

---

## **Risk 10 — Confidential Documents in Email**

- **Risk ID:** FO-RISK-010  
- **Category:** Privacy  
- **Likelihood:** 4  
- **Impact:** 4  
- **Controls:** Encrypted email optional  
- **Gaps:** No standard for document sharing  
- **Residual:** High  

---

## **Risk 11 — Gift Card Scam Targeting Elder Family Member**

- **Risk ID:** FO-RISK-011  
- **Category:** Social Engineering  
- **Likelihood:** 5  
- **Impact:** 3  
- **Residual:** Medium  

---

## **Risk 12 — Public Social Media Oversharing**

- **Risk ID:** FO-RISK-012  
- **Category:** Reputational  
- **Likelihood:** 4  
- **Impact:** 3  
- **Residual:** Medium  
- **Mitigation:** Social media audit + education  

---

# End of Document
