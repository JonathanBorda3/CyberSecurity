# Data Leak Incident Analysis and Recommendations

## Overview
This folder contains the analysis and recommendations following a data leak incident at a tech company. The incident involved the unintentional sharing of internal documents with an external party because of inadequate access controls.

## Analysis
The incident analysis revealed that the principle of least privilege was not used, leading to unauthorized access and data sharing. The incident occurred when a sales representative shared a link to internal documents instead of promotional materials during a video call with a business partner.

### Factors Leading to the Incident
The incident happened due to inadequate access control measures, specifically not implementing the principle of least privilege. Access to sensitive internal documents was not restricted only to the sales team, which led to unintentional data sharing with business partners.

## Recommendations
Based on the analysis, the following control enhancements are recommended to improve data security and prevent similar incidents:

1. Implement stricter access controls based on user roles to make sure that only necessary access is granted to sensitive internal documents.
2. Automatically revoke access to sensitive data after a specific period of time to lower the risk of unintended data sharing.
3. Implement automated access reviews: Set up regular automated reviews of user access permissions to make sure that users have only the necessary access required for their roles. This will help with the principle of least privilege over time and reduce the risk of accidental data leaks.

### Justification
These control enhancements are important in improving data security by reducing the likelihood of accidental data leaks. By enforcing least privilege and automatically revoking access when necessary, the company can better protect sensitive information from unauthorized users and sharing incidents.

Feel free to review the analysis findings and recommendations in the Data Leak Worksheet for more detailed insights.
