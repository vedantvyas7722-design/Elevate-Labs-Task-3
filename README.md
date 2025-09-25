# Elevate-Labs-Task-3

For a comprehensive breakdown, including detailed analysis and answers to all interview questions, please see the [task3-nessus.txt]

Scan Overview
Tool: Tenable Nessus Essentials

Target: Local Kali Linux VM (192.168.29.174)

Scan Type: Basic Network Scan

Key Findings
The scan identified a total of 63 vulnerabilities. The most significant findings were related to outdated software components.

Severity

CVSS

Vulnerability Name

High

7.5

Ruby RACK Denial of Service (DoS) Vulnerability

Medium

5.9

Ruby REXML Denial of Service (DoS) Vulnerability

Medium

--

Node.js Multiple Vulnerabilities

Conclusion & Remediation
The system's primary security risks are due to outdated versions of Node.js and Ruby. The recommended remediation is to update these software packages to their latest stable versions to patch the identified vulnerabilities.
