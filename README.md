# botium-toys-internal-security-audit


# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Internal Security Audit Workflow](#workflow)
4. [Controls Assessment](#control-assessment)
5. [Compliance Checklist](#compliance-checklist)
6. [Stakeholder Memorandum](#stakeholder-memo)


-------

# Introduction <a name="introduction">

This is an internal security audit for a company botium toys, a fictitious company. The scope of the audit defined as 
the entire security program at Botium toys including things like employee equipments and devices.

The goal is to assess existing assets and complete the controls and compliance checklis to determine which controls and compliance best practices needs to be 
implemented to improve Botium Toy's security posture.

# Scenario  <a name="scenario">
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

The task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

------------------------


The goals for Botium Toys’ internal IT audit are:
- Assess current security posture of Botium Toys
- To adhere to the National Institute of Standards and Technology Cybersecurity
Framework (NIST CSF)
- Ensure compliance with regulations such as PCI DSS, GDPR and others needed as the company's online presence grows
- Create policies and procedures to identify risk, including their security playbook
- Evaluate IT operations efficiency and identify areas for improvement, including recommending strategies to optimize IT process
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential
management



   
## Internal Security Audit Workflow  <a name="workflow">
The internal audit can be broken down into two main steps.

### step 1: Initial Assessment and planning
1. Analyze the Audit scope, goals, and risk assessment
   - clearly define the audit's objective and scope
   - identify the key areas of the scope based on the risk assessment

2. Conduct the Audit
   - Controls assessment 
     - Evalaute existing structure against industry best practices and regulatory requirements.
     - Identify gaps and weakness
     - prioritize control improvements based on risks and impacts.
   - Compliance checklist
     - Asess adherence to relevant regulations and standards(e.g PCI DSS, GDPR).
     - Identify potential gaps and potential risk.
     - Develop a plan to address found issues.
### step 2: Reporting and Recommendations
1. Audits finding and Deliverable.
   - Make note of key findings and recommendations
   - Analyze the results of the controls assessment and compliance checklist. 
2. Prepare the Audit report.
   - Summarize the audit findings in a clear and concise format.
   - Provide specific recommendations for improvement, including timeline and responsible parties.
4. communicate findings to stakeholders
   - Present audits to the relevant stackholders
   - Address issues and concerns raised by stakeholders
   - Monitor implementation and track the progress.


Controls Assessment  <a name="control-assessment">
===================


Current Assets 
--------------

Assets managed by the IT Department include:

- In office IT equipments. 

- Employee workstations, mobile devices, and remote workstations

- Business applications and software

- Network connectivity

- Data storage and backup

- Physical access control

- Data center hosting services 

- Legacy system maintenance: end-of-life systems that require human monitoring

### Administrative Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative: Limits access to data and systems to only what's necessary for job roles. | X | High |
| Disaster recovery plans | Corrective: Protects critical systems and data from disruptions like system failures, natural disasters, and minimizes downtime. | X | High |
| Password policies | Preventative: Strengthen account security by establishing robust password policies to deter brute-force and dictionary attacks. | X | High |
| Access control policies | Preventative: Bolster data security by prioritizing confidentiality and integrity. | X | High |
| Account management policies | Preventative: Ensures secure user accounts through strong passwords, limited access, and regular reviews. | X | High |
| Separation of duties | Preventative: Ensures that no single person has complete control over a critical process, reducing the risk of fraud, errors, and security breaches. | X | High |

### Technical Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall | Preventative: firewalls ***already implemented*** helps  filter unwanted/malicious traffic from entering internal network | NA | NA |
| Intrusion Detection System (IDS) | Detective: Detects and alerts the IT team on possible network intruison or breach | X | High |
| Encryption | Deterrent: Encrypts data to prevent unauthorised use, especially data in transmission | X | High |
| Backups | Corrective; Very useful in a disaster recovery scenario | X | High |
| Password management system | Preventive: Strong password policies, recovery methods, and account lockout after multiple failed login attempts.   | X | High |
| Antivirus (AV) software | Correctiv: detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective: This is essential for securing legacy systems by addressing vulnerabilities and threats. | X | High |


### Physical Controls
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Time-controlled safe | Deterrent: limits access to a safe and reduces attack surface/impact of physical threats | X | Medium/Low |
| Adequate lighting | Deterrent: provides more visibility hence deterring threat actors | X | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective: Helps monitors and records activities to enhance security and support incident investigation in an IT environment. | X | High/Medium |
| Locking cabinets (for network gear) | Preventative: Enhance integrity by preventing unauthorized access to or tampering with network infrastructure. | X | High/Medium |
| Signage indicating alarm service provider | Deterrent: Helps alerts individuals to the presence of a monitored alarm system, deterring potential security breaches. | X | Low |
| Locks | Preventative: Helps restrict unauthorized access to buildings, rooms, or equipment, keeping physical and digital assets more secure | X | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative: mitigate fire risks, protecting assets and ensuring safety, e.g servers, inventory, devices, etc. | X | High |

Compliance checklist
====================
   
Given the fact that Botium toys would like to expand it's operation to the international market and with it's use of digital payment system, these are some compliance regulations they need to follow:   

-   Payment Card Industry Data Security Standard (PCI DSS)

    - The PCI DSS is an information security standard designed to reduce payment card fraud by increasing security controls around cardholder data. 

       - Botium Toys must strictly adhere to PCI DSS standards due to its plan to expand their global online and in-person payment processing. Inability to comply can lead to severe consequences, including hefty fines, costly forensic audits, payment brand restrictions, reputational damage, and potential legal liabilities.

-   General Data Protection Regulation (GDPR)
      - GDPR is a European law that protects the privacy of EU citizens. It's helps protect personal information, no matter irrespective of a company's base of operation. If a company mishandles your data, they have to let you know within 72 hours.
         - As Botium Toys expands its global operations, GDPR compliance becomes very crucial to protect the personal data of EU customers. This includes safeguarding financial and personal information.


-   System and Organizations Controls (SOC type 1, SOC type 2)
   - SOC 1 and SOC 2 are types of reports that assess an organization's security practices. They evaluate controls related to financial reporting and information security, respectively. 

      -Botium Toys must implement strong access controls to protect sensitive information. This includes limiting access to authorized personnel and monitoring third-party access to minimize security risks.
      - These  frameworks are used to assess an organization's internal controls. While SOC 1 specifically evaluates financial reporting controls, SOC 2 focuses on a broader range of information security controls, including those related to customer data protection.
----------------
   

# Stakeholder memorandum <a name="stakeholder-memo">

To: IT Manager, Stakeholders\
From: Samuel U.\
Date: 20/11/2024 \
Subject: Internal Audit Findings and Recommendations

**Introduction:**

This memorandum presents the findings from the recent internal cybersecurity audit conducted for Botium Toys. As the company continues to expand it's physical presence and online operations, the audit was designed to evaluate existing security measures, compliance with critical regulations such as PCI DSS and GDPR, and alignment with industry best practices. The audit’s scope covered core IT systems, user access controls, and data security procedures.

Based on the findings, several critical vulnerabilities that need immediate attention, as well as longer-term recommendations for enhancing the overall cybersecurity posture of Botium Toys has been outlined.

**Scope and Goals:**

The audit focused on evaluating the following key systems and processes:

- Main/core Systems Evaluated: Accounting systems, endpoint detection solutions, firewalls, intrusion detection system (IDS), and security information and event management (SIEM) tools.
  
- Objectives: 

  - Ensure that user permissions, implemented controls, and security protocols align with regulatory requirements, including PCI DSS and GDPR.

  - Ensure all security assets both digital and physical are secure and accounted for.

  - Establish a comprehensive process and policy to align systems with NIST Cybersecurity Framework(CSF),including the implementation of strong security controls, access management protocols, and clear incident response procedures.

The goal is to fortify Botium toy's security framework, ensuring that both the company and customers data and private information are protected adequately against cyber threats it might face in the nearest future.

**Critical Findings and Immediate Actions**

The audit uncovered several high-risk areas requiring immediate corrective actions to mitigate security threats:

- Access Control Weaknesses: The principle of least privilege and separation of duties are not fully implemented, increasing the risk of unauthorized access. Should be addressed immediately.

- Lack of Disaster Recovery Plans: There is no proper disaster recovery plan in place. A comprehensive strategy must be created and implemented to ensure business continuity.

- Weak Password and Account Management Policies: There is no proper password management system, and account access controls are insufficient. Stronger policies are needed.

- Absence of Intrusion Detection Systems (IDS): The lack of an IDS increases vulnerability to unauthorized access. Implementing an IDS is crucial for threat detection.

- Data Encryption: Sensitive data is not adequately encrypted during transmission or storage. Encryption must be implemented to protect critical assets/information both on the business/customer side.

- Insufficient Backup Procedures: Backups are lacking, and there’s no strategy for securing critical data. Data needs to be backuped onsite and through a cloud platform.

- Physical Security Gaps: Existing physical security measures need reinforcement, especially in fire detection and prevention, CCTV installation to better protect assets.


**Additional Findings** (No immediate action needed):

The following physical controls should be considered in the future once the critical findings have been resolved:

- Time-controlled safe

- Adequate lighting

- Signage indicating alarm service provider for restricted areas

**Recommendations:**

Based on the findings I would like to strongly recommend the following steps to address the identified security gaps to further enhance Botium Toy's security posture.

- PCI DSS and GDPR Compliance: There should be a focus on ensuring full compliance with PCI DSS to ensure proper handling of payment card data. On a similar note, there should also be full compliance with GDPR for the protection of customers data especially those in the  EU.

- Implement Strong Access Controls: Apply the principle of least priviledge for user access management, and introduce seperation to prevent unauthorized access and data manipulation.

- Disaster Recovery and Backup Procedures:
Develop and implement a proper disaster recovery plan. Ensure that regular backups are performed and stored securely, including backing up data on site and on cloud platforms.

- Deploy an Intrusion Detection System (IDS):
Ensure to install an IDS to detect and respond to potential security threats in real time. This will improve the company’s ability to prevent or minimize the impact of cyber-attacks.

- Enhance Data Protection:
Sensitive data should always be encrypted when at rest or in transit, ensuring that customer payment information and PII are adequately protected.

- Implement a Password Management System:
There should be a strong password management system to enforce strong password policies and reduce the risk of password-related vulnerabilities.

- Physical Security Enhancements:
There should be upgrades with the physical security infrastructure with time-controlled safes, enhanced fire detection, and prevention systems, as well as improved lighting and alarm service indicators.

**Conclusion:**

In conclusion, given Botium Toys' expansion into international markets and online payment processing, prioritizing PCI DSS and GDPR compliance is crucial. To ensure data security, implementing strong access controls based on the principle of least privilege, as outlined in SOC 1 and SOC 2 guidelines, is essential.

To bolster business continuity and data resilience, implementing robust disaster recovery plans and regular backups is essential. Additionally, incorporating fire detection and prevention systems can mitigate physical threats.

To enhance security, deploying intrusion detection systems (IDS) and antivirus (AV) software can help identify and mitigate potential threats, particularly for legacy systems that require manual monitoring.

Physical security measures, such as locks, CCTV surveillance, time-controlled safes, adequate lighting, and alarm systems, can significantly enhance the security of Botium Toys' physical assets.
   
