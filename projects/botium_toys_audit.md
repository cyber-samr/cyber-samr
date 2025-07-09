# 🧸 Botium Toys - Internal Audit Report

## 🔍 Scope and Goals of the Audit

**Scope:**  
This audit covers the entire security program at Botium Toys, including:

- Employee equipment and devices  
- Internal network and internet access  
- All systems and software used for accounting, ecommerce, inventory, and more  
- Data retention and storage practices  
- Legacy systems still in operation

**Goals:**  
- Review existing assets  
- Complete the controls and compliance checklist  
- Identify missing controls and compliance gaps  
- Recommend improvements to strengthen the overall security posture

---

## 💻 Current Assets Managed by IT

- On-premises business equipment
- End-user devices (laptops, desktops, phones, etc.)
- Remote workstations and peripherals
- Surveillance equipment
- Storefront and warehouse inventory systems
- Software/services (accounting, telecom, database, ecommerce, etc.)
- Internal network and internet access
- Data retention systems
- Legacy systems requiring manual oversight

---

## ⚠️ Risk Assessment

### 🔐 Risk Description:
- Asset management is poorly defined  
- Controls are missing or incomplete  
- Possible non-compliance with U.S. and E.U. regulations (especially regarding payment processing and data protection)

### 🧰 Control Best Practices:
- **NIST CSF: Identify** – Assets must be properly inventoried and classified  
- Assess the business impact of asset loss

### 📊 Risk Score:
**8 out of 10** – High risk due to lack of controls and weak compliance practices

### 📝 Additional Notes:

- All employees currently have access to internal customer data (including PII/SPII and payment info)
- No encryption is used for credit card data
- No access controls based on least privilege or separation of duties
- Firewall and antivirus software are functioning properly
- No Intrusion Detection System (IDS) is in place
- No disaster recovery or backup plan
- GDPR compliance: breach notification plans and privacy policies are in place
- Password policies are outdated and not enforced through a central management system
- Legacy system maintenance lacks a schedule or response plan
- Physical location is secured with locks, updated CCTV, and fire systems

---

> 📌 Next Step: Proceed to the [Controls and Compliance Checklist] to assess and recommend improvements.

# Botium Toys: Controls and Compliance Checklist

## Controls Assessment Checklist

| Control                                                                 | Implemented? |
|------------------------------------------------------------------------|--------------|
| Least Privilege                                                        | ❌ No         |
| Disaster Recovery Plans                                                | ❌ No         |
| Password Policies                                                      | ✅ Yes        |
| Separation of Duties                                                   | ❌ No         |
| Firewall                                                               | ✅ Yes        |
| Intrusion Detection System (IDS)                                       | ❌ No         |
| Backups                                                                | ❌ No         |
| Antivirus Software                                                     | ✅ Yes        |
| Manual Monitoring for Legacy Systems                                   | ✅ Yes        |
| Encryption                                                             | ❌ No         |
| Password Management System                                             | ❌ No         |
| Locks (offices, storefront, warehouse)                                 | ✅ Yes        |
| Closed-Circuit Television (CCTV) Surveillance                          | ✅ Yes        |
| Fire Detection/Prevention (fire alarms, sprinklers, etc.)              | ✅ Yes        |

---

## Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                                                 | Adhered? |
|------------------------------------------------------------------------------|----------|
| Only authorized users have access to customers’ credit card information.     | ❌ No     |
| Credit card info is stored, accepted, processed, transmitted securely.       | ❌ No     |
| Data encryption procedures are in place for credit card data.                | ❌ No     |
| Secure password management policies are adopted.                             | ❌ No     |

---

### General Data Protection Regulation (GDPR)

| Best Practice                                                                 | Adhered? |
|------------------------------------------------------------------------------|----------|
| E.U. customers’ data is kept private/secured.                                | ✅ Yes    |
| Breach notification plan within 72 hours is in place.                        | ✅ Yes    |
| Data is properly classified and inventoried.                                 | ❌ No     |
| Privacy policies and procedures are enforced to document/maintain data.      | ✅ Yes    |

---

### System and Organization Controls (SOC 1 / SOC 2)

| Best Practice                                                                 | Adhered? |
|------------------------------------------------------------------------------|----------|
| User access policies are established.                                        | ❌ No     |
| Sensitive data (PII/SPII) is kept confidential/private.                      | ❌ No     |
| Data integrity is maintained (accurate, complete, validated).                | ✅ Yes    |
| Data is available to authorized users.                                       | ✅ Yes    |

---

## Recommendations

To improve Botium Toys’ security posture, the following controls and best practices should be implemented immediately:

- Enforce **least privilege** access policies and **separation of duties** to reduce insider threat risks.
- Develop and test a **disaster recovery plan** and establish **regular backups** of critical systems.
- Implement **encryption** for customer payment data and deploy a **centralized password management system**.
- Adopt secure password policies aligned with industry standards and update the current policy.
- Install an **intrusion detection system (IDS)** for better threat visibility.
- Classify and inventory all sensitive data, especially data subject to GDPR regulations.
- Create detailed **user access policies** and limit access to only what is needed per role.
- Ensure full PCI DSS compliance, especially regarding **credit card data security**.

