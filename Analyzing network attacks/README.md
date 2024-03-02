# Analyzing Network Attacks

This folder contains documentation related to the analysis of a specific network attack. The analysis focuses on a SYN flood attack, which targeted the web server of a travel agency's website. The provided content includes a Wireshark TCP-HTTP log, the scenario, and a cybersecurity incident report.

## Wireshark TCP-HTTP Log

The Wireshark log captures the network traffic during the SYN flood attack. The log is organized with color-coded entries, highlighting interactions between the server and the attacker's IP address (203.0.113.0). The attack progression and its impact on legitimate visitor traffic are detailed in the log.

### Log Analysis

The analysis includes:

- Identification of SYN requests from the attacker and legitimate visitors.
- The server's initial responses to both legitimate and malicious SYN requests.
- Escalation of the attack leading to failed communications and eventual server unresponsiveness.
- Error messages, such as "504 Gateway Timeout" and [RST, ACK] packets, indicating the disruption caused by the SYN flood attack.

## Cybersecurity Incident Report

The incident report provides a comprehensive overview of the SYN flood attack. It covers:

- Identification of the attack type based on the continuous stream of SYN requests.
- Explanation of how the attack disrupts the normal three-way handshake process.
- Analysis of the logs, detailing the impact on the server's ability to handle legitimate traffic.
- Suggestions for security measures to prevent future attacks, including Intrusion Prevention Systems (IPS), rate limiting, Web Application Firewalls (WAF), and an Incident Response Plan.

## Prevention Measures

To prevent similar attacks in the future, consider implementing the following security measures:

- **Intrusion Prevention System (IPS):** Deploy IPS solutions like Cisco Secure IPS to identify and block malicious traffic.
- **Rate Limiting:** Implement measures to control the volume of incoming SYN requests from a single source.
- **Web Application Firewalls (WAF):** Deploy WAFs to filter and monitor HTTP traffic, blocking malicious attempts, including SYN flood attacks.
- **Incident Response Plan:** Develop and maintain a plan outlining steps to be taken in the event of a cyber attack.

Feel free to explore the provided materials and use the insights gained to enhance network security.

---
