## Incident Report: Yummy Recipes Website

### Overview

This repository documents a cybersecurity incident analysis conducted on the client company website www.yummyrecipesforme.com. The investigation aimed to identify and resolve issues related to the "destination port unreachable" error reported by several customers.

### Incident Scenario

- **Description:** Customers reported being unable to access the website, encountering a "destination port unreachable" error.
- **Investigation Method:** Utilized TCPDump to analyze network traffic and diagnose the problem.
- **Key Findings:** Identified issues in the DNS protocol, specifically related to UDP packets and ICMP error responses.

### Incident Report

#### Part 1: Summary of TCPDump Log Analysis

As part of the DNS protocol, the UDP protocol was used to contact the DNS server to retrieve the IP address for the domain name. The ICMP protocol responded with an error message, indicating issues with the DNS server.

- **Protocols:** UDP and ICMP
- **Error Message:** "udp port 53 unreachable"
- **Port:** 53 (DNS service)
- **Analysis:** The DNS server on port 53 is unreachable, hindering successful resolution of the domain.

#### Part 2: Incident Analysis and Next Steps

- **Incident Time:** 1:24 p.m.
- **Awareness:** Customers reported the issue when encountering the "destination port unreachable" error.
- **Actions Taken:** Utilized TCPDump for packet sniffing, identified DNS port 53 as unreachable.
- **Next Steps:**
  - Verify firewall settings.
  - Check DNS server for issues.
  - Investigate network connectivity problems.
  - Examine the possibility of DNS spoofing/hijacking attempts.
- **Suspected Cause:** Failure in communication between the client's computer and the DNS server on port 53.

