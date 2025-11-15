# IT Provider Oversight Playbook  
*For HNWI, SFO, and MFO Operational Excellence*  
**Version 1.0 — Complete Document**

---

## 1. Purpose

This playbook ensures effective oversight of Managed Service Providers (MSPs), Managed Security Service Providers (MSSPs), IT contractors, and embedded technology teams serving Family Offices.  
Families and SFO/MFOs require a stronger governance model than typical SMBs because:

- The sensitivity of personal and financial data is far greater  
- Targeted attacks are more common  
- The “cost of failure” is orders of magnitude higher  
- IT providers often operate with implicit trust and little verification  

This playbook creates structure, transparency, accountability, and measurable performance.

---

## 2. Roles & Responsibilities

### **Family Office / Principal Responsibilities**
- Set security and privacy expectations  
- Maintain a list of approved systems  
- Review quarterly performance reports  
- Approve administrative access requests  
- Maintain an IT governance calendar  

### **IT Provider Responsibilities**
- Implement and maintain secure infrastructure  
- Enforce MFA and privileged access controls  
- Provide proactive patching and monitoring  
- Provide incident response support  
- Maintain asset inventory and documentation  
- Report incidents immediately  

### **Shared Responsibilities**
- Business continuity  
- Identity lifecycle management  
- Endpoint hardening  
- Vendor oversight  

---

## 3. Core Oversight Framework

Oversight is structured in five layers:

1. **Contractual & SLA Governance**  
2. **Identity & Access Oversight**  
3. **Infrastructure & Endpoint Oversight**  
4. **Security Monitoring & Incident Handling**  
5. **Quarterly Review Cadence**  

Each is detailed below.

---

## 4. Contract & SLA Governance

### 4.1 Required Contractual Items
The provider must contractually commit to:

- 24/7 critical incident support  
- 1-hour response on security incidents  
- MFA enforcement  
- Asset tracking and reporting  
- Backup and recovery SLAs with testing  
- No subcontractors without disclosure  
- SOC 2 or equivalent security reporting  
- Annual security test results  

### 4.2 SLA Targets
- **Critical incidents:** 1 hour response, 4 hour mitigation, 24 hour resolution  
- **High incidents:** 4 hour response, 8 hour mitigation  
- **Support requests:** 1 business day  
- **Patching:**  
  - Critical vulnerabilities: 72 hours  
  - High: 7 days  
  - Medium: 30 days  
  - Low: 90 days  

---

## 5. Identity & Access Oversight

The IT provider must enforce:

### 5.1 Privileged Access Controls
- No shared admin accounts  
- Separate admin and standard accounts  
- Just-in-time (JIT) elevation if possible  
- MFA enforced for all admin actions  

### 5.2 Identity Lifecycle
- Onboard within 24 hours  
- Offboard within 2 hours of request  
- Quarterly access audits  

### 5.3 Monitoring
- Admin activity logs exported to SIEM  
- Alerts for privilege escalation events  
- Alerts for access outside normal hours  

---

## 6. Infrastructure & Endpoint Oversight

### 6.1 Device Baselines
All devices must have:

- Full disk encryption  
- EDR/XDR agent  
- Screen lock ≤ 5 minutes  
- Prevent local admin by default  
- Software allowlisting if feasible  
- Automatic patching  

### 6.2 Network Oversight
- Separate guest network  
- Separate IoT network  
- VPN or Zero Trust network access  
- Firewall rules documented  
- Regular review of open ports/services  

### 6.3 Backup & Recovery
- Daily backups  
- Cloud-stored, immutable copies  
- Quarterly restoration tests  
- RTO ≤ 24 hours for critical systems  

---

## 7. Security Monitoring & Incident Handling

### 7.1 Monitoring Requirements
- Endpoint telemetry  
- DNS filtering  
- Threat intelligence correlation  
- Cloud tenant monitoring (O365/GWS)  
- Identity-based anomaly detection  

### 7.2 Required Incident Notifications
Provider must notify the family office within:

- **15 minutes** of suspected compromise  
- **1 hour** of confirmed incident  
- **24 hours** with full preliminary report  
- **72 hours** with root cause analysis  

### 7.3 Incident Review
After any incident:

- Update timelines  
- Validate lessons learned  
- Implement required remediations  
- Review provider performance  

---

## 8. Quarterly Review Structure

Every quarter the provider must deliver:

### 8.1 Required Quarterly Deliverables
- Ticket analysis (volume, type, resolution times)  
- Incident summaries and metrics  
- Patch compliance report  
- Asset inventory delta report  
- MFA enforcement report  
- Backup test results  
- Uptime & reliability metrics  
- Security control gaps  

### 8.2 Review Meeting Agenda
1. Strategic updates  
2. Incidents & near misses  
3. Patch compliance  
4. Open vulnerabilities  
5. Backup and restore performance  
6. Identity & access audit  
7. Hardware/software lifecycle  
8. Roadmap review  

---

## 9. Annual Review Structure

### 9.1 Required Annual Deliverables
- Full infrastructure review  
- Privilege access audit  
- Network architecture review  
- Security roadmap  
- DR test results  
- Vendor risk assessment  

### 9.2 Renewal Decision Criteria
- SLA achievement  
- Responsiveness  
- Incident handling quality  
- Technical maturity  
- Financial stability  

---

## 10. Offboarding Procedure

If the provider is replaced:

1. Export all configurations  
2. Remove all provider accounts  
3. Rotate all credentials  
4. Validate backups and system integrity  
5. Update documentation  
6. Migrate logs  
7. Revoke access tokens  
8. Conduct exit interview  

---

# End of Document
