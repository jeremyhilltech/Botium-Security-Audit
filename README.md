# Botium Security Audit
A security audit of fictional company Botium Toys from the Google Cybersecurity Professional Certificate course. 

---

## **This scenario is based on a fictional company:**

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

---

## **The following report was obtained from Botium Toys:**

### Botium Toys: Scope, Goals, and Risk Assessment Report

Scope: The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

Goals: Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture.

### Current Assets
Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring 

### Risk Assessment
Risk description: 
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

### Control Best Practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk Score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

### Additional Comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

  - Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
  - Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
  - Access controls pertaining to least privilege and separation of duties have not been implemented.
  - The IT department has ensured availability and integrated controls to ensure data integrity.
  - The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
  - Antivirus software is installed and monitored regularly by the IT department. 
  - The IT department has not installed an intrusion detection system (IDS).
  - There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
  - The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
  - Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters). 
  - There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
  - While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
  - The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

---

## **Report Given In Response To Assessment Review**

### Botium Toys Controls & Compliance Report

After careful review of the information gathered in the initial assessment, this report has been generated to give a high-level view of current practices within the company as well as recommendations for hardening security posture and streamlining security practices within the company. The first portion outlines the current state of controls and compliance, with recommendations given last. This document serves to function as an aid for the IT Manager or others in supporting positions to communicate to stakeholders the current security and compliance needs of the organization in order to avoid illegal practices, fines, data breaches, and irreparable damage to Botium Toys' reputation. 

**Controls Assessment Checklist**

|   Yes |     No | Control |
| ----- | ----- | :---- |
|  | x | Least Privilege |
|  | x | Disaster recovery plans |
| x |  | Password policies |
|  | x | Separation of duties |
| x |  | Firewall |
|  | x | Intrusion detection system (IDS) |
|  | x | Backups |
| x |  | Antivirus software |
| x |  | Manual monitoring, maintenance, and intervention for legacy systems |
|  | x | Encryption |
|  | x | Password management system |
| x |  | Locks (offices, storefront, warehouse) |
| x |  | Closed-circuit television (CCTV) surveillance |
| x |  | Fire detection/prevention (fire alarm, sprinkler system, etc.) |

---

**Compliance Checklist**

Payment Card Industry Data Security Standard (PCI DSS)

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|  | x | Only authorized users have access to customers’ credit card information.  |
|  | x | Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
|  | x | Implement data encryption procedures to better secure credit card transaction touchpoints and data.  |
|  | x | Adopt secure password management policies. |

General Data Protection Regulation (GDPR)

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|  | x | E.U. customers’ data is kept private/secured. |
| x |  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
|  | x | Ensure data is properly classified and inventoried. |
|  | x | Enforce privacy policies, procedures, and processes to properly document and maintain data. |

System and Organizations Controls (SOC type 1, SOC type 2\) 

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|  | x | User access policies are established. |
|  | x | Sensitive data (PII/SPII) is confidential/private. |
| x |  | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
| x |  | Data is available to individuals authorized to access it. |

---

**Recommendations to IT Manager for Communication to Stakeholders**

Controls: 

* Implement use of the principle of Least Privilege across company.   
* Develop and implement Disaster Recovery Plan.   
* Implement Separation of Duties where able to reduce risk of compromise.  
* Install IDS on host equipment to actively monitor for security events.   
* Create encrypted data backups, kept in two separate locations, that are updated on a regular schedule. Consider idea of cold, warm, hot sites if financially feasible (See recommendation for DRP.)  
* Encrypt all payment systems, data, and databases.   
* Implement Password Policy and any other supporting software to enforce said policies. 

Compliance: 

* Ensure that PCI DSS compliance is followed.
  -  [https://docs-prv.pcisecuritystandards.org/PCI%20DSS/Standard/PCI-DSS-v4\_0\_1.pdf](https://docs-prv.pcisecuritystandards.org/PCI%20DSS/Standard/PCI-DSS-v4_0_1.pdf)  
* Ensure that GDPR compliance is followed.
  -  [https://gdpr-info.eu/](https://gdpr-info.eu/)   
* Use NIST CSF to gain additional insight into needed implementations and security posture improvements.
  -  [https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf)

SOC (Systems and Organizations Controls) Considerations:

* Establish organization-wide user policies and procedures.   
* Ensure that all PII/SPII is confidential, authentic, available to proper parties, and protected. 

Closing Comments: 

If you have additional questions, please do not hesitate to reach out for clarification and help with additional resources. Thank you for your time and attention to these matters, I look forward to working with the team to secure Botium Toys and continue to build a brand that our customers will trust for many successful years to come. 

Very Respectfully, 

> Jeremy Hill  
> Governance, Risk, and Compliance Analyst  
> Botium Toys

