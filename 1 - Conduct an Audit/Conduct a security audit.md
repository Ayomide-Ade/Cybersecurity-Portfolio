# Controls and Compliance Assessment 

## Scenario

This is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

## Scope

The scope of this audit is defined as the entire security program at Botium Toys.
This includes their assets like employee equipment and devices, their internal network,
and their systems. You will need to review the assets Botium Toys has and the controls
and compliance practices they have in place.

## Goals 

Assess existing assets and complete the controls and compliance checklist to
determine which controls and compliance best practices that need to be implemented
to improve Botium Toys’ security posture.

## Current Assets

Assets managed by the IT Department include: 
* On-premises equipment for in-office business needs
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Data retention and storage
* Legacy system maintenance: end-of-life systems that require human monitoring 

## Risk Assessment 

### Risk Description

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

### Control Best Practices

The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk Score

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

### Additional Comments

The potential impact from the loss of an asset is rated as medium, because the IT
department does not know which assets would be at risk. The risk to assets or
fines from governing bodies is high because Botium Toys does not have all of the necessary
controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure.

## Control Categories

In Cybersecurity, control types can be classified in three ways: 

1. Administrative/Managerial controls
2. Technical controls
3. Physical/Operational controls

### Control Types 

Control types include, but are not limited to:
1. Preventative
2. Corrective
3. Detective
4. Deterrent

## Control Assessment Checklist

| Control                | ✅ Yes | ❌ No | Explanation |
|------------------------|:------:|:-----:|-------------|
| Least Privilege        |        | ✅    | All employees have access to customer data; access should be restricted. |
| Disaster Recovery Plan |        | ✅    | No disaster recovery plan in place to ensure business continuity. |
| Firewall               | ✅     |       | A firewall exists to block traffic based on defined security rules. |
| Password Policies      |        |  ❌   | Password policy exists but lacks complexity and enforcement. |
| Antivirus              | ✅     |       | Antivirus software is installed and monitored by IT. |
| Backups                |        | ✅    | No backups are in place; data is at risk in the event of breach. |
| Encryption             |        | ✅    | Encryption is not implemented for customer or credit card data. |
| IDS                    |        | ✅    | No intrusion detection system is currently installed. |
| Storefront             | ✅     |       | Storefront is physically secured with locks and monitored. |
| CCTV                   | ✅     |       | CCTV surveillance is active and functioning. |
| Fire Detection         | ✅     |       | Fire detection and prevention systems are in place. |

## Compliance Checklist

| Best Practice                                                               | Yes | No  | Explanation |
|-----------------------------------------------------------------------------|:---:|:---:|-------------|
| Only authorized users have access to customers’ credit card information     | ✅ |     | Access now limited to authorized personnel only. |
| Credit card data is stored/processed internally in a secure environment     | ✅ |     | Credit card data is handled in a secure internal setup. |
| Encryption procedures are implemented to secure credit card data            |     | ✅ | Encryption has not yet been implemented. |
| Secure password management policies are adopted                             |     | ✅ | Weak policies exist; no centralized password manager in place. |

## General Data Protection Regulation (GDPR)

| Best Practice                                              | Yes | No  | Explanation |
|------------------------------------------------------------|:---:|:---:|-------------|
| E.U. customers’ data is kept private/secured               | ✅ |     | IT enforces privacy procedures for data protection. |
| Breach notification plan (within 72 hours) is in place     | ✅ |     | IT has a plan to notify affected E.U. customers. |
| Data is properly classified and inventoried                |     | ✅ | No formal data classification/inventory system exists. |
| Privacy policies, procedures, and processes are enforced   | ✅ |     | IT staff follow defined privacy protocols. |

## System and Organization Controls (SOC)

| Best Practice                                                       | Yes | No  | Explanation |
|----------------------------------------------------------------------|:---:|:---:|-------------|
| User access policies are established                                 |     | ✅ | All employees can access all data; no proper access policy. |
| Sensitive data (PII/SPII) is confidential/private                    |     | ✅ | Data is not encrypted or access restricted. |
| Data integrity ensures data is consistent, complete, and accurate    | ✅ |     | Data integrity controls are in place and maintained. |
| Data is available (to authorized users only)                         |     | ✅ | Access is not restricted to authorized users only. |

## 🔐 Security & Compliance Recommendations for Botium Toys

In this section, we outline key recommendations related to controls and compliance that can be communicated to stakeholders to reduce risks to assets and improve Botium Toys’ overall security posture:

1. **Implement Role-Based Access Control (RBAC)**  
   Restrict data access to only authorized users based on job roles to reduce exposure of sensitive customer information.

2. **Enforce Strong Password Policies**  
   Adopt minimum password complexity standards (e.g., at least 8 characters, upper/lowercase, numbers, symbols) and enforce them using a centralized password management system.

3. **Enable Multi-Factor Authentication (MFA)**  
   Require MFA for all users, especially those accessing sensitive systems, to add an additional layer of protection.

4. **Encrypt Sensitive Data (PII, SPII, Credit Card Info)**  
   Use strong encryption (e.g., AES-256) for data at rest and in transit to protect confidentiality and meet compliance requirements (e.g., PCI-DSS, GDPR).

5. **Establish a Disaster Recovery & Backup Plan**  
   Develop and test a documented disaster recovery plan that includes regular data backups (full, incremental) and clearly defined RTO/RPO.
