# Personal Device & Home Network Baseline Guide  
*For HNWI, Family Members, Staff, SFO, and MFO Environments*  
**Version 1.0 — Complete Document**

---

## 1. Purpose

This guide defines mandatory baseline security standards for:

- Phones  
- Tablets  
- Laptops  
- Home Wi-Fi  
- Smart home devices  
- Guest networks  
- IoT  
- Consoles  
- Cameras  

It establishes the minimum acceptable configuration for a Family Office–grade environment.

---

## 2. Device Security Baselines

### 2.1 Mobile Device Requirements (iOS / Android)
- OS up to date  
- Passcode required  
- Unlock time ≤ 30 seconds  
- FaceID/TouchID allowed except during high-risk travel  
- Full-disk encryption  
- Automatic updates enabled  
- AirDrop limited to Contacts Only (iOS)  
- Unknown App Sources disabled (Android)  
- VPN installed and configured  
- EDR mobile agent where appropriate  

### 2.2 Laptop/Desktop Requirements
- macOS or Windows 11 fully updated  
- Full disk encryption  
- Admin rights removed from daily account  
- EDR/XDR installed  
- Password-protected screen lock after 5 minutes  
- Automatic updates enabled  
- Browser extensions restricted  
- USB access restricted where possible  

---

## 3. Application Security

### 3.1 Mandatory Apps
- Password manager  
- Authenticator (not SMS)  
- Secure messenger (Signal)  
- VPN  
- Encrypted email (if needed)  

### 3.2 Prohibited Apps
- Unknown VPN apps  
- Smart-cleaner or booster apps  
- Unverified cryptocurrency wallets  
- Sideloaded applications  

### 3.3 Sensitive App Controls
- Banking apps require device encryption  
- Email apps require MFA  
- Cloud storage apps restricted to vetted providers  

---

## 4. Home Network Architecture

### 4.1 Required Network Segmentation
The home network must have:

1. **Primary Network** — family devices  
2. **Guest Network** — isolated, internet-only  
3. **IoT Network** — smart devices isolated  
4. **Work Network** (optional)  
5. **Security Network** — cameras, sensors, alarm  

### 4.2 Router Requirements
- WPA3 security  
- Disable WPS  
- Change admin password  
- Disable UPnP  
- Separate VLANs for IoT and guest  
- Firewall enabled  
- Remote admin disabled  

### 4.3 Wi-Fi Requirements
- Unique SSIDs per VLAN  
- Hidden SSIDs discouraged (security theater)  
- 5GHz or 6GHz preferred  
- Ethernet for stationary devices  

---

## 5. IoT & Smart Device Hardening

### 5.1 Required Controls
- Change default password  
- Update firmware regularly  
- Disable unused features  
- Isolate on IoT VLAN  
- Block internet access unless required  

### 5.2 High-Risk Devices
- Smart TVs  
- Voice assistants  
- Cloud-connected cameras  
- Smart locks  

### 5.3 Special Note: Smart TVs
- Disable tracking  
- Disable voice recognition  
- Remove unneeded apps  
- Use external streaming box (Apple TV) instead  

---

## 6. Family Office Systems at Home

### 6.1 Required Controls
- SSO/MFA for all work apps  
- Encrypted storage  
- Encrypted backups  
- Periodic device audits  
- No personal devices for work-critical apps  

### 6.2 Remote Workstations
- Company-managed devices strongly preferred  
- VDI alternative where appropriate  

---

## 7. Physical Security Controls

- Keep devices out of sight from windows  
- Enable device tracking (Find My / Find Device)  
- Lock home office when not in use  
- Use fireproof/waterproof safes for critical documents  

---

## 8. Monitoring & Maintenance

### 8.1 Weekly Tasks
- Check for OS updates  
- Review alerts from EDR/VPN/password manager  

### 8.2 Monthly Tasks
- Firmware updates (router, IoT devices)  
- Password manager audit  
- Backup verification  

### 8.3 Quarterly Tasks
- Device inventory review  
- Remove unused apps  
- Check access logs  
- Review network segmentation  

---

## 9. New Device Onboarding

Checklist:

1. Update system  
2. Enable encryption  
3. Remove bloatware  
4. Install EDR  
5. Install required applications  
6. Configure VPN  
7. Add to device registry  
8. Place on appropriate VLAN  
9. Confirm backups functioning  

---

## 10. Device Offboarding & Disposal

- Backup essential data  
- Factory reset  
- Wipe securely  
- Remove from MDM  
- Revoke tokens/access  
- Remove from network registry  

---

# End of Document
