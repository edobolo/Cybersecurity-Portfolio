# Security Audit & Risk Assessment (Internal) - Botium Toys

> *Note: The following security audit was done as a practical exercise for the Google Cybersecurity Professional Certificate.*

## 1. Context
Botium Toys is a hypothetical company that is growing rapidly. In an internal review, I performed a security audit of their IT systems, asset management practices, and existing security processes to find out where there are any weaknesses or gaps in terms of compliance.

## 2. Objectives
The main goal of this audit was to test the effectiveness of the current physical, technical, and administrative controls used by the company. Furthermore, the company's compliance with international compliance frameworks (GDPR & PCI DSS) was tested.
[Clicca qui per visualizzare il Risk Assessment Report originale](Botium-Toys-Scope-goals-risk-assessment-report.pdf)
[Clicca qui per visualizzare il Botium Toys Report](Controls-and-compliance-checklist.pdf)

## 3. Methodology
In order to achieve these goals, I used the Identify and Protect core functions from the NIST Cybersecurity Framework (CSF). I reviewed the given Risk Assessment Report and classified controls used by the company.

## 4. Controls Assessment Checklist
| Current Status | Control | Type |
| :---: | :--- | :--- |
| ❌ No | Least Privilege | Administrative/Preventative |
| ❌ No | Disaster recovery plans | Administrative/Corrective |
| ✅ Yes | Password policies | Administrative/Preventative |
| ❌ No | Separation of duties | Administrative/Preventative |
| ✅ Yes | Firewall | Technical/Preventative |
| ❌ No | Intrusion detection system (IDS) | Technical/Detective |
| ❌ No | Backups | Technical/Corrective |
| ✅ Yes | Antivirus software | Technical/Corrective |
| ❌ No | Manual monitoring, maintenance for legacy systems | Technical/Preventative |
| ❌ No | Encryption | Technical/Deterrent |
| ❌ No | Password management system | Technical/Preventative |
| ✅ Yes | Locks (offices, storefront, warehouse) | Physical/Deterrent |
| ✅ Yes | CCTV surveillance | Physical/Preventative |
| ✅ Yes | Fire detection/prevention | Physical/Detective |

### General Data Protection Regulation (GDPR)
| Current Status | Best practice |
| :---: | :--- |
| ❌ No | E.U. customers’ data is kept private/secured. |
| ✅ Yes | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
| ❌ No | Ensure data is properly classified and inventoried. |
| ✅ Yes | Enforce privacy policies, procedures, and processes to properly document and maintain data. |

### System and Organizations Controls (SOC type 1, SOC type 2) 
| Current Status | Best practice |
| :---: | :--- |
| ❌ No | User access policies are established. |
| ❌ No | Sensitive data (PII/SPII) is confidential/private. |
| ✅ Yes | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
| ❌ No | Data is available to individuals authorized to access it. |  

## 5. Recommendations for IT Management
Based on the Risk Assessment, Botium Toys presents a high risk (score 8/10) due to the lack of adequate controls and non-compliance with PCI DSS and GDPR. I strongly recommend prioritizing the following implementations:
* **Administrative & Technical Access Controls:** Immediate implementation of the Principle of Least Privilege and Separation of Duties. Currently, all employees have access to sensitive data (PII/SPII) and credit card data, exposing the company to severe compliance violations.
* **Encryption:** The absence of encryption for locally stored data must be rectified to comply with PCI DSS requirements and protect the confidentiality of customers' financial information.
* **Business Continuity & Backups:** Establish disaster recovery plans and implement regular backups of critical data (Corrective Controls) to mitigate the impact of potential data loss.
* **Password Management & IDS:** Upgrade the password policy to enforce stricter requirements and adopt a centralized password management system. Furthermore, deploying an Intrusion Detection System (IDS) is highly advised to monitor and detect anomalous network activity.
