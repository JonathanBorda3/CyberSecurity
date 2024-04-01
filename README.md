# Cybersecurity Work

This branch is dedicated to my CyberSecurity profile on GitHub. Here, I'll be documenting my progress, security audits, and practice work related to cybersecurity.

## Updates 

### [3/21/2024] Incident Investigation Report - SSH Login Failure Analysis

## Purpose
This project involves investigating failed SSH logins for the root account on the mail server at Buttercup Games. The goal is to analyze log data using Splunk Cloud, identify security issues, and assess the severity of the incident.

## Contents
1. Description: Brief overview of the incident investigation.
2. Tools Used: Splunk Cloud for log analysis.
3. The 5 W's: Capturing essential details of the incident.
4. Additional Notes: Including any findings or observations.

## Description
This report documents the investigation into failed SSH logins for the root account on the mail server at Buttercup Games. Splunk Cloud was used to analyze log data and identify potential security issues.

## Tools Used
- Splunk Cloud: Used for log analysis and search queries.

## The 5 W's
- **Who caused the incident?** Unknown at this stage; investigation ongoing.
- **What happened?** Failed SSH logins for the root account on the mail server.
- **When did the incident occur?** Date and time details captured in the investigation.
- **Where did the incident happen?** On the mail server at Buttercup Games.
- **Why did the incident happen?** Investigating potential vulnerabilities or unauthorized access attempts.

## Additional Notes
The investigation is ongoing, with a focus on identifying the root cause of the failed SSH logins and adding security measures to prevent future incidents.

## Conclusion
The incident investigation into failed SSH logins on the mail server at Buttercup Games using Splunk Cloud has provided valuable insights. Further analysis and actions will be taken to enhance the security posture and prevent similar incidents in the future.

### [3/19/2024] Incident Report Review

### Purpose
This project involves a review of a major security incident at a mid-sized retail company, focusing on a data breach that occurred before the analyst joined the security team. The goal is to understand the incident's life cycle, including what happened, when it happened, the response actions taken, and future recommendations to prevent similar incidents.

### Contents
1. Goals and Answers: Summarizes the identified goals and their corresponding answers regarding the incident.
2. Incident Summary: Provides an overview of the incident, including unauthorized access to customer data and its financial impact.
3. Conclusion: Concludes the project with insights into proactive security measures and the importance of continuous monitoring.

### Goals and Answers
- **Goal 1:** Identify exactly what happened.
  - The organization experienced a data breach affecting approximately 50,000 customer records.
- **Goal 2:** Identify when it happened.
  - The security incident occurred on December 28, 2022, with initial signs noted on December 22, 2022.
- **Goal 3:** Identify the response actions that the company took.
  - The company responded by investigating the breach, disclosing it to affected customers, and implementing security measures.
- **Goal 4:** Identify future recommendations.
  - Recommendations include routine vulnerability scans, penetration testing, and access control mechanisms.

### Incident Summary
The incident involved an unauthorized access to customer personal identifiable information (PII) and financial data, resulting in a financial impact of $100,000. The root cause was a vulnerability in the e-commerce web application.

### Conclusion
This review emphasizes the significance of proactive security measures like routine scans and access control to prevent similar incidents. Continuous monitoring and response strategies are crucial in safeguarding customer data and mitigating financial losses.

For detailed information, refer to the incident report review within the project folder.


### [3/18/2024] Use a playbook to respond to a phishing incident

### Purpose
This project focuses on using a playbook to respond to a phishing incident in a level-one Security Operations Center (SOC) at a financial services company. The scenario involves investigating a phishing alert about a suspicious file being downloaded on an employee's computer. The project aims to demonstrate the structured approach and procedures followed in responding to such incidents according to the organization's security policies.

### Contents
1. Scenario and Steps: Details the scenario, steps to follow, and key actions during the investigation.
2. Phishing Incident Response Playbook: Provides the playbook version, purpose, and steps for responding to phishing incidents.
3. Alert Ticket: Includes the alert message, severity, details, and ticket status.
4. Incident Handler's Journal: Captures the details, tools used, 5 W's analysis, and additional notes about the incident.

### Conclusion
After reviewing the playbook, evaluating the alert, and analyzing the incident details, the decision was made to escalate the alert due to the presence of a known malicious file hash, inconsistencies in the sender information, grammatical errors in the email, and the successful download of a password-protected attachment. This project showcases the importance of a structured incident response process and the need for continuous vigilance against phishing attacks in organizational cybersecurity strategies.

For detailed information and step-by-step instructions, refer to the specific documents within the folder "Use a playbook to respond to a phishing incident".


### [3/16/2024] Investigate a suspicious file hash

## Purpose
This section details an investigation into a suspicious file download incident at a financial services company. It provides a structured guide for analyzing the incident, utilizing tools like SHA256 hashing and VirusTotal for IoC discovery, and assessing associated risks using the Pyramid of Pain framework.

## Key Points

### Scenario
The scenario involves a level one security operations center (SOC) analyst investigating a suspicious file download on an employee's computer. The file, received via email, contains a malicious payload executed after the employee entered a provided password.

### Steps for Investigation
1. Review the alert details and timeline.
2. Enter the file hash into VirusTotal for IoC discovery.
3. Analyze the VirusTotal report for detections, behaviors, and IoCs.
4. Determine if the file is malicious based on report findings.
5. Enter identified IoCs into the Pyramid of Pain template.

### Incident Handler's Journal
The incident handler's journal captures details of the incident, including who, what, when, where, and why, along with additional notes about the file's malicious nature and associated threat actors.

### Conclusion
Through this project, we demonstrate a structured approach to cybersecurity incident investigation and analysis. By leveraging tools like SHA256 hashing and VirusTotal, along with frameworks like the Pyramid of Pain, we can effectively identify, analyze, and respond to cybersecurity threats in a systematic manner.

For detailed instructions and documentation, refer to the full documents related to this scenario in the "Investigate a suspicious file hash" folder. 

### [3/13/2024] Incident Handler's Journal

**Purpose:**  
This section provides guidelines for recording incident details in the Incident Handler's Journal, along with a scenario of a security incident at a healthcare clinic.

**Contents:**
- Steps for recording a journal entry in the Incident Handler's Journal.
- Description of the security incident scenario at a healthcare clinic.
- Guidelines for filling out the journal entry with the 5 W's (Who, What, When, Where, Why).
- Additional notes section for questions and thoughts related to the incident scenario.

**Conclusion:**  
By following the documents provided, you can effectively document incident details and analyze security incidents using the Incident Handler's Journal framework.

### [3/13/2024] Sneaker Company Security Threat Model

## Purpose
This section outlines the security threat model analysis for a mobile app developed by a sneaker company. The purpose of this is to identify and address potential risks and vulnerabilities in the app to ensure data security and user privacy.

## Overview
- **Step 1: Identify Objectives**: Understand the app's purpose and functionalities.
- **Step 2: Evaluate Components**: Assess the technologies used for potential security risks.
- **Step 3: Review Data Flow**: Analyze how information flows within the app to protect data.
- **Step 4: Analyze Threats**: Identify possible attacks and threat scenarios.
- **Step 5: Assess Vulnerabilities**: List weaknesses that attackers could exploit.
- **Step 6: Map Attack Scenarios**: Create an attack tree to visualize potential attacks.
- **Step 7: Implement Security Controls**: Add measures to mitigate risks and enhance security.

**Conclusion**
This threat model analysis aims to strengthen the security posture of the sneaker company's app, ensuring a safe and secure experience for users and protecting sensitive data.

### [3/08/2024] Parking Lot USB Exercise

- **Purpose**
  - This README.md outlines a security scenario involving a USB drive found in the parking lot of Rhetorical Hospital. It provides a structured approach for inspecting the device, analyzing it from an attacker's perspective, and assessing associated risks.

- **Contents**
  - The USB drive contains a mix of personal and work-related files belonging to Jorge Bailey, including family photos, a new hire letter, and an employee shift schedule.

- **Attacker Mindset**
  - The information on the USB drive could be used by an attacker to craft phishing emails, gain insights into hospital operations, and potentially establish unauthorized access to systems.

- **Risk Analysis**
  - Implementing controls such as employee awareness training, routine antivirus scans, and technical measures like endpoint security software can mitigate the risks associated with USB-baiting attacks.
    
For detailed insights and step-by-step instructions, refer to the full documents related to this scenario.

### [3/03/2024] Vulnerability Assessment Report

- **System Description**
  - Server hardware: Powerful CPU, 128GB memory, Linux OS, MySQL DBMS, IPv4 network, SSL/TLS encryption.

- **Scope**
  - Assess current access controls from June 20XX to August 20XX using NIST SP 800-30 Rev. 1.

- **Purpose**
  - Protect crucial customer data, ensure business continuity, and avoid significant operational impacts.

- **Risk Assessment**
  - Identified threats: Unauthorized access by employees, outsider hacking attempts, and malware attacks.
  - Likelihood and severity scores used to calculate overall risk scores (6-9).

- **Approach**
  - Assessed risks based on data storage procedures and system access permissions.
  - Identified threats considering likelihood and impact on daily operations.

- **Remediation Strategy**
  - Recommendations: Principle of Least Privilege, Defense in Depth, Multi-Factor Authentication, AAA framework.
  - Specific measures proposed to address identified risks.

For detailed information, refer to the full Vulnerability Assessment Report.

### [2/28/2024] Investigation - Payroll Incident Analysis

- Conducted an investigation into a payroll incident at a business.
- Reviewed the event log to identify the cause of the incident: the Legal/Administrator initiated the payroll event at 8:29:57 AM on 10/03/2023 using the account of a former employee (Robert Taylor Jr.).
- Identified an authorization issue where an inactive account was used to access sensitive systems.
- Recommended implementing role-based access control (RBAC) to restrict access to authorized personnel, enabling Multi-Factor Authentication (MFA), and setting user account expiration policies to prevent unauthorized access.
- Refer to the Access controls worksheet for detailed incident analysis, authorization issues, and recommendations.
- ...

### [2/23/2024] Data Leak Incident Analysis - Educational Tech Company
- Conducted an analysis of a data leak incident at a tech company.
- Reviewed the factors that led to the incident, including inadequate access controls and unintentional data sharing.
- Identified control enhancements based on NIST SP 800-53: AC-6 to improve data security.
- Recommended implementing stricter access controls based on user roles and automating access reviews.
- Justified the recommendations to reduce the likelihood of future data leaks and improve information privacy.
- Refer to the Data Leak Worksheet for detailed incident analysis, control enhancements, and justifications.
- ...

### [2/18/2024] Risk Assessment - Commercial Bank
- Conducted a risk assessment for a commercial bank in a coastal area with low crime rates.
- Analyzed potential risks to the bank's funds, including business email compromise, compromised user database, financial records leak, theft, and supply chain disruption.
- Considered the bank's operational environment, including the number of employees, customer base, and marketing channels.
- Prioritized risks based on likelihood and severity scores, using a risk matrix for assessment.
- Developed a risk register to centralize potential risks and prioritize security measures.
- Refer to the risk register for detailed risk descriptions, likelihood, severity, and priority scores.
- ....
  
### [2/13/2024] Home Network Device Inventory
- Created an Excel sheet to inventory network devices in a small home business environment.
- Identified devices like desktops, smartphones, smart home devices, and game consoles.
- Documented important characteristics such as network access, owner, and location for each device.
- Evaluated device access based on stored information and owner's security practices.
- Classified sensitivity levels (e.g., Restricted, Internal-only, Confidential) to prioritize security measures.
- Refer to the Excel sheet for detailed device information and security classifications.
- ...


### [2/08/2024] SQL Security Investigation Project
- Investigated potential security threats in login attempts and employee data using SQL filters.
- Analyzed after-hours failed login attempts, specific dates' login activities, and activities outside Mexico.
- Targeted Marketing, Finance, and Sales departments' employees for security updates.
- Identified security needs for departments not in IT, ensuring a comprehensive security posture.
- Utilized SQL queries to retrieve critical data and insights for enhancing security measures.
- Refer to the SQL queries for detailed investigation steps and insights.
- ...
  
### [2/01/2024] File Permissions Management in Linux
This folder contains three important documents related to managing file permissions in Linux within the `/home/researcher2/projects` directory:

1. **Current & Updated File Permissions**:
   - **Current file permissions**: Displays the file structure and permissions of files/subdirectories in `/home/researcher2/projects`.
   - **Updated file permissions**: Reflects changes made to file permissions based on organizational policies.

2. **File Permissions in Linux**:
   - **Project description**: Outlines the tasks involved in examining and modifying file permissions within the projects directory.
   - **Instructions**: Provides step-by-step instructions for checking permissions, understanding permission strings, and modifying permissions using Linux commands.

3. **Scenario & Instructions for Linux Commands**:
   - **Scenario**: Describes the role of a security professional in managing permissions for the research team, ensuring appropriate access control.
   - **Instructions**: Details the steps for checking, describing, and changing file permissions, along with screenshots and explanations.

Explore these documents for insights into managing file permissions effectively, adhering to security policies, and maintaining access control within Linux environments.

### [1/25/2024] Linux Software Installation Lab
#### Introduction
This lab guides participants through the process of managing software installations and removals in a Linux distribution, specifically Ubuntu, using command-line tools. By leveraging the APT package manager and sudo privileges, users install Suricata and tcpdump, essential for network security analysis.

#### Activity Overview
In this lab activity, participants will use the Advanced Package Tool (APT) and sudo to install and uninstall applications in Ubuntu. The lab emphasizes the importance of efficient software management in a Linux environment, particularly for security analysts requiring network monitoring tools like Suricata and tcpdump.

#### Scenario
Your role as a security analyst requires that you have the Suricata and tcpdump network security applications installed on your system. In this scenario, you have to install, uninstall, and reinstall these applications on your Linux Bash shell. You also need to confirm that you’ve installed them correctly.

#### Tasks
1. **Ensure APT Installation**: Confirm the presence of the APT package manager in your Linux environment.
2. **Install and Uninstall Suricata**:
   - Install Suricata using the APT package manager (`sudo apt install suricata`).
   - Verify the installation by running the `suricata` command.
   - Uninstall Suricata using `sudo apt remove suricata`.
3. **Install the tcpdump Application**: Install tcpdump, a network traffic capturing tool, using the APT package manager (`sudo apt install tcpdump`).
4. **List Installed Applications**: Confirm the installation of required applications by listing all installed applications using the APT package manager (`apt list --installed`).

### [1/18/2024] NIST Cybersecurity Framework Incident Report
This folder contains documents related to network security practices and incident response strategies, focusing on the NIST Cybersecurity Framework (CSF).

- Explored security hardening tasks, configurations, and risk assessment in network environments.
- Addressed vulnerabilities through Multifactor Authentication, Firewall Rule Configuration, and Password Policy Enforcement.
- Included a scenario document highlighting major vulnerabilities and the necessity for security measures.

The documents available are:

- **Incident Report Analysis:** Provides a template and instructions for incident report analysis, covering sections for Identify, Protect, Detect, Respond, and Recover.
- **Applying the NIST CSF Framework:** Offers an overview of the NIST Cybersecurity Framework's five core functions: Identify, Protect, Detect, Respond, and Recover. It includes detailed questions and considerations for each function, aiding in managing cybersecurity risks effectively.
- **Completed Example of an Incident Report Analysis:** Includes an example incident report detailing unauthorized access and data manipulation, along with the actions taken to Identify, Protect, Detect, Respond, and Recover from the security incident.
- **Scenario for NIST Cybersecurity Framework:** Presents a scenario involving a DDoS attack and the subsequent investigation and mitigation measures. It assigns tasks to a cybersecurity analyst to create a plan following the NIST CSF framework.

These documents offer valuable insights into network security practices, incident response strategies, and the application of frameworks like the NIST CSF for effectively managing cybersecurity risks.


### [1/10/2024] Network Hardening Tools and Security Risk Assessment
- Explored security hardening tasks, configurations, and risk assessment in network environments.
- Addressed vulnerabilities through Multifactor Authentication, Firewall Rule Configuration, and Password Policy Enforcement.
- Referenced a scenario document highlighting major vulnerabilities and the need for security measures.
- ...
  
### [1/1/2024] Applying OS Hardening Techniques
- This folder contains documents and logs related to networking, security incidents, and OS hardening techniques.
- Explore the materials for insights into network analysis, security incident reporting, and operating system security.
- Added tcpdump log with explanation: Reading the tcpdump traffic log.
  - Detailed analysis of DNS and HTTP traffic, identifying malicious activities.
  - Explanation of TCP flag codes and HTTP requests.
  - Resources for more information on tcpdump usage.
- ...
  
### [12/24/2024] Analyzing Network Attacks
- Conducted detailed analysis of a SYN flood attack.
- Examined Wireshark TCP-HTTP logs to understand attack patterns.
- Created a comprehensive Cybersecurity Incident Report outlining the attack's impact.
- Implemented mitigation strategies to prevent future occurrences.
- ...

### [12/12/2023] Network Traffic Analysis
- Conducted a detailed analysis of DNS port 53 unreachable incidents using tcpdump.
- Identified and documented potential vulnerabilities in DNS configurations.
- Proposed recommendations for enhancing DNS availability and security.
- ...

### [12/5/2023] 
- Implemented folder structure for better organization.
- Added summaries and descriptions for commits based on the audit checklist.
- Continued working on the Controls compliance checklist.
- Explored additional resources on cybersecurity best practices.
- ...

### [12/4/2023] Botium Security Audit
- Added a checklist based on a mock security audit for Botium Toys.
- Completed the Controls compliance checklist.
- Provided 10 recommendations to improve security controls and compliance.
- ...

## To-Do
- [ ] Explore more cybersecurity frameworks.
- [ ] Practice ethical hacking techniques.
- [ ] Security information and event management (SIEM) dashboards.

Feel free to check back for updates on my cybersecurity journey!
