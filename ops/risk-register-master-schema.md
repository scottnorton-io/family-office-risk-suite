# Risk Register Master Schema  
*For HNWI, Family Offices, and Multi-Family Offices*  
**Version 1.0 — Complete Document**

---

## 1. Purpose

This schema defines the standardized structure, fields, definitions, and scoring methodology used to document and manage risks within HNWI, SFO, and MFO environments.  
It ensures:

- Consistent documentation  
- Clear prioritization  
- Traceable accountability  
- Alignment with governance frameworks (Interacture, ISO 27005, NIST RMF adapted for Family Offices)  
- Ability to export into Notion, FieldGuide, Vanta, or internal Excel templates  

---

## 2. Core Structure

A complete risk record includes the following sections:

1. **Risk ID**  
2. **Category**  
3. **Subcategory**  
4. **Risk Title**  
5. **Description**  
6. **Assets Affected**  
7. **Threat Actor(s)**  
8. **Likelihood Score**  
9. **Impact Score**  
10. **Inherent Risk Rating**  
11. **Existing Controls**  
12. **Gaps / Control Weaknesses**  
13. **Residual Likelihood**  
14. **Residual Impact**  
15. **Residual Risk Rating**  
16. **Mitigation Plan**  
17. **Owner**  
18. **Next Review Date**  
19. **Status**  

Each element is defined below.

---

## 3. Field Definitions

### **3.1 Risk ID**
- Format: `FO-RISK-###`  
- Auto-incrementing  
- Unique per environment  

### **3.2 Category**
High-level grouping:
- Cybersecurity  
- Privacy  
- Operational  
- Financial  
- Reputational  
- Physical Security  
- Travel  
- Vendor  
- Estate / Legal  
- Personal Exposure  

### **3.3 Subcategory Examples**
- Identity & Access Management  
- Data Protection  
- Social Engineering  
- Digital Footprint  
- Custodian / Bank  
- IT Provider  
- Smart Home Tech  
- Family Member Behaviors  
- Health / Medical Emergencies  

### **3.4 Risk Title**
Short, descriptive, action-oriented.

Examples:
- “Compromise of family email accounts due to weak MFA enrollment”  
- “Exposure of home address via public real estate data brokers”  

### **3.5 Description**
A full narrative including:

- What could happen  
- Why it matters  
- What assets are impacted  
- Real-world examples if applicable  

### **3.6 Assets Affected**
- Specific individuals  
- Devices  
- Property  
- Accounts  
- Entities  
- Reputation  

### **3.7 Threat Actors**
- Opportunistic cybercriminals  
- Data brokers  
- Nation-state groups  
- Insider threats  
- Stalkers  
- Kidnapping rings  
- Manipulative service providers  
- Tabloid/media  

---

## 4. Risk Scoring Framework

### **4.1 Likelihood Scale**
| Score | Definition |
|--------|------------|
| **1** | Rare – highly unlikely |
| **2** | Unlikely – possible but infrequent |
| **3** | Possible – reasonably expected |
| **4** | Likely – occurs regularly |
| **5** | Almost Certain – expected to occur |

### **4.2 Impact Scale**
Impact incorporates **financial, privacy, safety, operational, and reputational** dimensions.

| Score | Definition |
|--------|------------|
| **1** | Minimal impact |
| **2** | Limited impact |
| **3** | Moderate impact |
| **4** | High impact |
| **5** | Severe impact / catastrophic |

### **4.3 Risk Rating Matrix**

| Likelihood \ Impact | 1 | 2 | 3 | 4 | 5 |
|----------------------|---|---|---|---|---|
| **1** | L | L | L | M | M |
| **2** | L | L | M | M | H |
| **3** | L | M | M | H | H |
| **4** | M | M | H | H | C |
| **5** | M | H | H | C | C |

Legend:
- **L** = Low  
- **M** = Medium  
- **H** = High  
- **C** = Critical  

### **4.4 Inherent vs. Residual Risk**
- **Inherent Risk**: Likelihood × Impact before controls  
- **Residual Risk**: Likelihood × Impact after controls  

---

## 5. Required Fields for Controls

### **5.1 Existing Controls**
List all relevant controls:
- Technical  
- Administrative  
- Physical  
- Process-based  

Examples:
- MFA enforced  
- Vendor SOC 2  
- Device encryption  
- Travel risk briefings  

### **5.2 Control Gaps**
Specific weaknesses:
- “MFA not enrolled for 2 family members”  
- “IoT VLAN not implemented”  
- “Vendor lacks breach notification SLA”  

### **5.3 Mitigation Plan**
Must include:
- Action  
- Timeline  
- Owner  
- Desired outcome  

---

## 6. Status States

- **Open**  
- **In Progress**  
- **Mitigated**  
- **Accepted**  
- **Transferred** (typically via insurance or vendor)  
- **Archived**  

---

## 7. Review Requirements

### **Minimum Review Cadence**
- High/Critical risks: **Monthly**
- Medium risks: **Quarterly**
- Low risks: **Semi-annually**

---

# End of Document
