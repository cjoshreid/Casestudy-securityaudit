# Case study: Security Audit

## This scenario was provided in the Google Cybersecurity Professional Certification as an example to gain experence in performing a cybersecurity audit and writeup. 

### This scenario is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Scope and goals of the audit:

Scope: The scope is defined as the entire security program at Botium Toys. This means
all assets need to be assessed alongside internal processes and procedures related to
the implementation of controls and compliance best practices.
Goals: Assess existing assets and complete the controls and compliance checklist to
determine which controls and compliance best practices need to be implemented to
improve Botium Toys’ security posture.

Current assets
Assets managed by the IT Department include:
● On-premises equipment for in-office business needs
● Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.
● Storefront products available for retail sale on site and online; stored in the
company’s adjoining warehouse
● Management of systems, software, and services: accounting,
telecommunication, database, security, ecommerce, and inventory
management
● Internet access
● Internal network
● Data retention and storage
● Legacy system maintenance: end-of-life systems that require human
monitoring

Risk assessment
Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does
not have all of the proper controls in place and may not be fully compliant with U.S. and
international regulations and standards.
Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to
dedicate resources to identify assets so they can appropriately manage them.
Additionally, they will need to classify existing assets and determine the impact of the
loss of existing assets, including systems, on business continuity.
Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of
controls and adherence to compliance best practices.
Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT
department does not know which assets would be at risk. The risk to assets or fines
from governing bodies is high because Botium Toys does not have all of the necessary
controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure. Review the following bullet points for
specific details:
● Currently, all Botium Toys employees have access to internally stored data and
may be able to access cardholder data and customers’ PII/SPII.
● Encryption is not currently used to ensure confidentiality of customers’ credit
card information that is accepted, processed, transmitted, and stored locally in
the company’s internal database.
● Access controls pertaining to least privilege and separation of duties have not
been implemented.
● The IT department has ensured availability and integrated controls to ensure
data integrity.
● The IT department has a firewall that blocks traffic based on an appropriately
defined set of security rules.
● Antivirus software is installed and monitored regularly by the IT department.

● The IT department has not installed an intrusion detection system (IDS).
● There are no disaster recovery plans currently in place, and the company does
not have backups of critical data.
● The IT department has established a plan to notify E.U. customers within 72
hours if there is a security breach. Additionally, privacy policies, procedures, and
processes have been developed and are enforced among IT department
members/other employees, to properly document and maintain data.
● Although a password policy exists, its requirements are nominal and not in line
with current minimum password complexity requirements (e.g., at least eight
characters, a combination of letters and at least one number; special
characters).
● There is no centralized password management system that enforces the
password policy’s minimum requirements, which sometimes affects
productivity when employees/vendors submit a ticket to the IT department to
recover or reset a password.
● While legacy systems are monitored and maintained, there is no regular
schedule in place for these tasks and intervention methods are unclear.
● The store’s physical location, which includes Botium Toys’ main offices, store
front, and warehouse of products, has sufficient locks, up-to-date
closed-circuit television (CCTV) surveillance, as well as functioning fire
detection and prevention systems.


            Control categories

Controls within cybersecurity are grouped into three main categories:
● Administrative/Managerial controls
● Technical controls
● Physical/Operational controls
Administrative/Managerial controls address the human component of
cybersecurity. These controls include policies and procedures that define how an
organization manages data and clearly defines employee responsibilities, including
their role in protecting the organization. While administrative controls are typically
policy based, the enforcement of those policies may require the use of technical or
physical controls.
Technical controls consist of solutions such as firewalls, intrusion detection systems
(IDS), intrusion prevention systems (IPS), antivirus (AV) products, encryption, etc.
Technical controls can be used in a number of ways to meet organizational goals and
objectives.
Physical/Operational controls include door locks, cabinet locks, surveillance
cameras, badge readers, etc. They are used to limit physical access to physical assets
by unauthorized personnel.
Control types
Control types include, but are not limited to:
1. Preventative
2. Corrective
3. Detective
4. Deterrent

These controls work together to provide defense in depth and protect assets.
Preventative controls are designed to prevent an incident from occurring in the first
place. Corrective controls are used to restore an asset after an incident. Detective
controls are implemented to determine whether an incident has occurred or is in
progress. Deterrent controls are designed to discourage attacks.
Review the following charts for specific details about each type of control and its
purpose.

Administrative/Managerial Controls

Control Name Control Type Control Purpose
Least Privilege Preventative Reduce risk and overall
impact of malicious insider
or compromised accounts

Disaster recovery plans Corrective Provide business
continuity

Password policies Preventative Reduce likelihood of
account compromise
through brute force or
dictionary attack
techniques

Access control policies Preventative Bolster confidentiality and
integrity by defining which
groups can access or
modify data

Account management
policies

Preventative Managing account
lifecycle, reducing attack
surface, and limiting
overall impact from
disgruntled former
employees and default
account usage
Separation of duties Preventative Reduce risk and overall
impact of malicious insider
or compromised accounts

Technical Controls

Control Name Control Type Control Purpose
Firewall Preventative To filter unwanted or
malicious traffic from
entering the network
IDS/IPS Detective To detect and prevent
anomalous traffic that
matches a signature or
rule

Encryption Deterrent Provide confidentiality to
sensitive information
Backups Corrective Restore/recover from an

event

Password management Preventative Reduce password fatigue
Antivirus (AV) software Corrective Detect and quarantine
known threats

Manual monitoring,
maintenance, and
intervention

Preventative Necessary to identify and
manage threats, risks, or
vulnerabilities to
out-of-date systems

Physical/Operational Controls

Control Name Control Type Control Purpose
Time-controlled safe Deterrent Reduce attack surface and
overall impact from
physical threats

Adequate lighting Deterrent Deter threats by limiting

“hiding” places

Closed-circuit television
(CCTV)

Preventative/Detective Closed circuit television is
both a preventative and
detective control because
it’s presence can reduce
risk of certain types of
events from occurring,
and can be used after an
event to inform on event
conditions

Locking cabinets (for
network gear)

Preventative Bolster integrity by
preventing unauthorized
personnel and other
individuals from physically
accessing or modifying
network infrastructure
gear

Signage indicating alarm
service provider

Deterrent Deter certain types of
threats by making the
likelihood of a successful
attack seem low
Locks Deterrent/Preventative Bolster integrity by
deterring and preventing
unauthorized personnel,
individuals from physically
accessing assets

Fire detection and
prevention (fire alarm,
sprinkler system, etc.)

Detective/Preventative Detect fire in physical
location and prevent
damage to physical assets
such as inventory, servers,
etc.





# Cybersecurity Audit Report

## Executive Summary

This cybersecurity audit report provides an overview of the current state of Botium Toys' security posture, focusing on assets, controls, and compliance. The audit aimed to assess existing assets, identify potential risks, and recommend controls and compliance measures to improve the overall security posture. The scope encompassed the entire security program at Botium Toys, including on-premises equipment, employee devices, storefront products, management systems, internet access, network infrastructure, data retention, and storage.

## Findings

### 1. Risk Assessment

#### Risk Description
Botium Toys currently faces a high risk (score of 8) due to inadequate asset management, lacking controls, and potential non-compliance with U.S. and international regulations.

#### Control Best Practices
- The NIST CSF's first function, Identify, is crucial. Resources should be allocated to identify and classify assets to manage them effectively.
- Business continuity planning and impact assessment of potential asset loss are essential.

#### Additional Comments
- Employees have unrestricted access to internally stored data, including cardholder data and PII/SPII.
- Lack of encryption for credit card information stored locally poses a confidentiality risk.
- Access controls (least privilege and separation of duties) are absent.
- No intrusion detection system (IDS) is in place.
- No disaster recovery plans or backups for critical data.
- Password policy requirements are nominal, and no centralized password management system is implemented.
- Legacy systems lack a regular maintenance schedule.

### 2. Control Categories

#### Administrative/Managerial Controls

1. **Least Privilege**
   - **Control Type:** Preventative
   - **Purpose:** Reduce the risk and overall impact of malicious insider or compromised accounts.

2. **Disaster Recovery Plans**
   - **Control Type:** Corrective
   - **Purpose:** Provide business continuity.

3. **Password Policies**
   - **Control Type:** Preventative
   - **Purpose:** Reduce the likelihood of account compromise through brute force or dictionary attack techniques.

4. **Access Control Policies**
   - **Control Type:** Preventative
   - **Purpose:** Bolster confidentiality and integrity by defining access or modification rights.

5. **Account Management Policies**
   - **Control Type:** Preventative
   - **Purpose:** Manage account lifecycle, reducing the attack surface and limiting overall impact from disgruntled former employees and default account usage.

6. **Separation of Duties**
   - **Control Type:** Preventative
   - **Purpose:** Reduce the risk and overall impact of malicious insider or compromised accounts.

#### Technical Controls

1. **Firewall**
   - **Control Type:** Preventative
   - **Purpose:** Filter unwanted or malicious traffic from entering the network.

2. **IDS/IPS**
   - **Control Type:** Detective
   - **Purpose:** Detect and prevent anomalous traffic that matches a signature or rule.

3. **Encryption**
   - **Control Type:** Deterrent
   - **Purpose:** Provide confidentiality to sensitive information.

4. **Backups**
   - **Control Type:** Corrective
   - **Purpose:** Restore/recover from an event.

5. **Password Management**
   - **Control Type:** Preventative
   - **Purpose:** Reduce password fatigue.

6. **Antivirus (AV) Software**
   - **Control Type:** Corrective
   - **Purpose:** Detect and quarantine known threats.

7. **Manual Monitoring, Maintenance, and Intervention**
   - **Control Type:** Preventative
   - **Purpose:** Necessary to identify and manage threats, risks, or vulnerabilities to out-of-date systems.

#### Physical/Operational Controls

1. **Time-Controlled Safe**
   - **Control Type:** Deterrent
   - **Purpose:** Reduce attack surface and overall impact from physical threats.

2. **Adequate Lighting**
   - **Control Type:** Deterrent
   - **Purpose:** Deter threats by limiting "hiding" places.

3. **Closed-Circuit Television (CCTV)**
   - **Control Type:** Preventative/Detective
   - **Purpose:** Reduce risk of events and inform on event conditions after they occur.

4. **Locking Cabinets (for Network Gear)**
   - **Control Type:** Preventative
   - **Purpose:** Bolster integrity by preventing unauthorized access to network infrastructure gear.

5. **Signage Indicating Alarm Service Provider**
   - **Control Type:** Deterrent
   - **Purpose:** Deter certain types of threats by making the likelihood of a successful attack seem low.

6. **Locks**
   - **Control Type:** Deterrent/Preventative
   - **Purpose:** Bolster integrity by deterring and preventing unauthorized access.

7. **Fire Detection and Prevention (Fire Alarm, Sprinkler System, etc.)**
   - **Control Type:** Detective/Preventative
   - **Purpose:** Detect fire in the physical location and prevent damage to physical assets.

## Recommendations

1. **Asset Management:**
   - Implement a robust asset management system to identify, classify, and manage all assets.

2. **Access Controls:**
   - Enforce access controls, including least privilege and separation of duties, to limit unauthorized access.

3. **Encryption:**
   - Implement encryption for the confidentiality of customers' credit card information.

4. **Intrusion Detection System (IDS):**
   - Deploy an IDS to detect and prevent anomalous network traffic.

5. **Disaster Recovery and Backup:**
   - Develop and test disaster recovery plans, including regular backups of critical data.

6. **Password Policy:**
   - Update the password policy to meet current minimum complexity requirements.

7. **Centralized Password Management:**
   - Implement a centralized password management system for efficiency and security.

8. **Legacy Systems Maintenance:**
   - Establish a regular schedule for monitoring and maintaining legacy systems.

9. **Compliance with E.U. Regulations:**
   - Ensure full compliance with E.U. regulations, including timely breach notification and adherence to privacy policies.

10. **Continuous Monitoring:**
    - Establish continuous monitoring mechanisms to promptly identify and respond to security incidents.

## Conclusion

Botium Toys faces significant cybersecurity risks due to inadequate controls and non-compliance. The recommended measures aim to enhance the security posture, ensure compliance, and mitigate potential risks. It is crucial for Botium Toys to prioritize these recommendations to safeguard their information assets and maintain the trust of customers and regulatory bodies.
```
