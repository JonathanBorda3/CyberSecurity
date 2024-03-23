# Vulnerability Assessment Report

## Purpose
This README.md file provides an overview of the vulnerability assessment report for a database server, including system description, scope, risk assessment, approach, and remediation strategy.

### System Description
- **Hardware:** Powerful CPU processor, 128GB memory
- **Operating System:** Latest version of Linux
- **Database Management System:** MySQL
- **Network:** Stable IPv4 connection, SSL/TLS encryption
- **Scope:** Assess current access controls from June 20XX to August 20XX
- **Purpose:** Secure sensitive customer data and ensure business continuity

### Risk Assessment
| Threat Source         | Threat Event                                   | Likelihood | Severity | Risk |
|-----------------------|------------------------------------------------|------------|----------|------|
| Employee (Privileged User) | Unauthorized access to sensitive data      | 2          | 3        | 6    |
| Hacker (Outsider)         | Attempted unauthorized access to server     | 3          | 3        | 9    |
| Malicious Software (Malware) | Ransomware attack on server               | 2          | 3        | 6    |

### Approach
- Evaluated risks based on data storage and management procedures.
- Identified threats from open access permissions in the system.
- Compared incident severity against operational impact.

### Remediation Strategy
- **Principle of Least Privilege:** Limit user access to necessary functions.
- **Defense-in-Depth:** Add firewalls and antivirus software for layered security.
- **Multi-Factor Authentication (MFA):** Use additional verification methods.
- **AAA Framework:** Implement tools for user activity monitoring.
- **Encryption:** Use TLS, IP allow-listing for secure connections.

### NIST SP 800-30 Rev. 1
- Guide for risk assessments, aiding in identifying and analyzing risks.
- Helps in resource allocation and prioritizing security measures.

### Scenario & Steps
- Scenario: Vulnerable e-commerce database server.
- Steps: 
  1. Review system information and scope.
  2. Identify threat sources based on NIST guidelines.
  3. Identify potential threat events.
  4. Calculate risk scores.
  5. Propose security recommendations.

