# Document Management & Vault Architecture Guide  
**Version 1.0 — Complete Document**

---

# 1. Goals  
This guide standardizes where documents live, who can access them, and how they are protected.

---

# 2. Storage Architecture

### **Primary Vault**
- 1Password  
- NetDocuments  
- Egnyte Secure  
- On-prem encrypted storage (optional)

### **Permitted Document Types**
- Legal docs  
- Personal identification  
- Medical records  
- Estate docs  
- Contracts  
- Investment docs  
- Incident reports  

---

# 3. Tagging Structure
| Tag | Definition |
|------|------------|
| FIN | Financial |
| LEG | Legal |
| MED | Medical |
| PRV | Privacy |
| OPS | Operations |
| CYB | Cybersecurity |

---

# 4. Document Lifecycle

### **Create**
- Must be encrypted-in-transit  
- Must be stored in vault  

### **Store**
- Correct tags  
- Correct access group  
- Version control maintained  

### **Share**
- Only encrypted channels  

### **Destroy**
- Crypto-erase  
- Document removal log  

---

# End of Document
