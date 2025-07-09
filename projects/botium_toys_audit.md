
# 🧸 Botium Toys - Internal Audit Report

## Controls and Compliance Checklist

### Controls Assessment

| Control                                                                 | In Place | Explanation |
|-------------------------------------------------------------------------|----------|-------------|
| Least Privilege                                                         | ❌       | All employees have access to customer data; need to limit access to reduce breach risk. |
| Disaster Recovery Plans                                                 | ❌       | No disaster recovery plans are in place. Needed to ensure business continuity. |
| Password Policies                                                       | ❌       | Current password requirements are minimal, increasing vulnerability. |
| Separation of Duties                                                    | ❌       | One person manages payroll and daily operations; separation needed to prevent fraud. |
| Firewall                                                                | ✅       | Firewall in place with well-defined security rules. |
| Intrusion Detection System (IDS)                                        | ❌       | Not in place; needed to detect intrusions by threat actors. |
| Backups                                                                 | ❌       | No backup process in place for critical data. |
| Antivirus Software                                                      | ✅       | Regularly installed and monitored by the IT department. |
| Manual Monitoring of Legacy Systems                                     | ❌       | Monitored, but no regular schedule or clear policies. |
| Encryption                                                              | ❌       | Not implemented; would improve data confidentiality. |
| Password Management System                                              | ❌       | Not implemented; causes delays and increases risk. |
| Locks (offices, storefront, warehouse)                                  | ✅       | Sufficient physical locks in place. |
| Closed-Circuit Television (CCTV) Surveillance                           | ✅       | CCTV system is functioning at physical location. |
| Fire Detection/Prevention (alarm, sprinkler system)                     | ✅       | Fire systems are in place and functioning. |

---

### Compliance Checklist

#### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                                                 | In Place | Explanation |
|------------------------------------------------------------------------------|----------|-------------|
| Only authorized users have access to customers’ credit card information.     | ❌       | All employees have access to internal customer data. |
| Data stored, accepted, processed, transmitted in a secure environment.       | ❌       | Internal credit card data is accessible without encryption. |
| Implement data encryption procedures.                                        | ❌       | Encryption not currently in use for transactions. |
| Adopt secure password management policies.                                   | ❌       | Password management is weak and not enforced. |

#### General Data Protection Regulation (GDPR)

| Best Practice                                                                 | In Place | Explanation |
|------------------------------------------------------------------------------|----------|-------------|
| E.U. customers’ data is kept private/secured.                                | ❌       | Encryption not used; data is not fully protected. |
| Breach notification plan within 72 hours for E.U. customers.                 | ✅       | Plan exists to notify customers within 72 hours. |
| Ensure data is properly classified and inventoried.                          | ❌       | Assets listed but not properly classified. |
| Enforce privacy policies and procedures.                                     | ✅       | Privacy policies developed and enforced internally. |

#### System and Organizations Controls (SOC 1, SOC 2)

| Best Practice                                                                 | In Place | Explanation |
|------------------------------------------------------------------------------|----------|-------------|
| User access policies are established.                                        | ❌       | Least Privilege and Separation of Duties are not in place. |
| Sensitive data (PII/SPII) is confidential/private.                           | ❌       | No encryption, all employees have access to customer data. |
| Data integrity ensures consistent, complete, accurate, validated data.       | ✅       | Data integrity is maintained. |
| Data is available to authorized individuals only.                            | ❌       | All employees currently have full access. |

---

### 🔧 Recommendations

To improve Botium Toys’ security posture and align with regulatory compliance:

- Implement **Least Privilege**, **Separation of Duties**, and **Encryption**.
- Create and maintain **Disaster Recovery Plans** and **Data Backups**.
- Introduce a **Password Management System** with secure, enforced policies.
- Deploy an **Intrusion Detection System (IDS)**.
- Classify all assets properly and limit access to sensitive data.
- Strengthen compliance with **PCI DSS**, **GDPR**, and **SOC** frameworks by ensuring only authorized personnel have access to credit card and personal data, and by adopting secure encryption and password handling procedures.
