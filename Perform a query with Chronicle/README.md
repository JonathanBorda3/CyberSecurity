# Phishing Domain Investigation - Incident Report Review

## Purpose
This project involves investigating a phishing domain discovered in a suspicious email received by an employee at a financial services company. The goal is to determine the extent of the phishing attempt, identify affected assets, assess the threat level, and take appropriate action to mitigate potential risks.

## Incident Journal Entry 6 - 3/23/2024

### Description
This journal entry documents the investigation process of a phishing domain (signin.office365x24.com) identified in a suspicious email received by an employee.

### Tools Used
- Chronicle
- VirusTotal (VT)
- ET Intelligence Rep List

### The 5 W's
- **Who caused the incident?**
  The incident was caused by an external threat actor who initiated the phishing attempt by sending a malicious email.
  
- **What happened?**
  An employee received a phishing email containing the domain signin.office365x24.com, indicating a potential phishing attempt.
  
- **When did the incident occur?**
  The incident was detected and investigated on 3/23/2024.

- **Where did the incident happen?**
  The incident occurred within the company's email system, affecting the employee who received the phishing email.

- **Why did the incident happen?**
  The incident happened due to a phishing attack targeting company employees to gain unauthorized access or extract sensitive information.

### Additional Notes
- The investigation revealed that the domain signin.office365x24.com was flagged as a drop site for logs or stolen credentials by the ET Intelligence Rep List.
- Assets accessed the phishing domain, including roger-spence-pc, coral-alvarez-pc, and emil-palmer-pc.
- The domain resolved to the IP address 40.100.174.34, and three POST requests were made to this IP address.
- The target URL of the web page for the POST requests was http://signin.office365x24.com/login.php.
- The IP address 40.100.174.34 resolved to signin.accounts-gooqle.com and signin.office365x24.com.

## Conclusion
The investigation into the phishing domain signin.office365x24.com revealed significant threats, including the potential for stolen credentials and unauthorized access. It highlights the importance of employee awareness, robust email security measures, and continuous monitoring to detect and respond to phishing attempts promptly.

For detailed information and logs, refer to the incident journal within the project folder.
