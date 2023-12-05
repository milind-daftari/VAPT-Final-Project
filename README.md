# Vulnerability Assessment and Penetration Testing (VAPT) Final Project

## Overview
This repository contains the documentation and findings of a comprehensive penetration testing project conducted on Near-Earth Broadcast Network (NBN). The project's aim was to identify and exploit vulnerabilities in NBN's developing web server and employee client machine, which are crucial for customer account access and employee customer service.

## Problem Statement
The penetration test was necessitated by a recent security breach at NBN Corp, raising concerns about residual risks in their web server and internal client machine. The goal was to simulate a realistic external threat, identify potential vulnerabilities, and propose remediation strategies.

## Methodology
The testing followed the Penetration Testing Execution Standard (PTES) using a black-box approach. This involved stages of reconnaissance, threat modeling, vulnerability analysis, exploitation, and post-exploitation activities. The primary tools used included Kali Linux, NMAP, LinPEAS, Nikto, OWASP ZAP, John, Hydra, and several custom scripts.

## Key Findings
Several critical vulnerabilities were identified, including:
- Privilege Escalation due to Misconfigurations and Vulnerabilities in PKexec.
- Critical Data Exposure through various directories and paths.
- Weak Credentials and Hard-coded Credentials in the system.
- Cross-Site Scripting and Directory Traversal vulnerabilities in the web application.
- Usage of vulnerable Apache versions.

## Solution
The Solution Report details the specific steps taken to exploit these vulnerabilities, the methodology for gaining access and escalating privileges, and recommendations for remediation. These include upgrading system components, tightening access controls, disabling anonymous FTP login, and improving user authentication methods.

## Conclusion
The test successfully highlighted a range of security issues that pose significant risks to NBN Corp's data and operations. Implementing the recommended fixes and continuously monitoring the systems are crucial steps in mitigating these vulnerabilities and enhancing the overall security posture.

---

For detailed insights and methodologies, refer to the [Solution Report](Solution_Report.pdf) and [Final Project](https://github.com/milind-daftari/VAPT-Final-Project/blob/main/Final%20Project.pdf) documents.
