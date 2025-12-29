# DVWA Web Application Security Scan – OWASP ZAP

## Overview

This project documents a full web application vulnerability assessment conducted on **Damn Vulnerable Web Application (DVWA)** using **OWASP ZAP** as part of a ParoCyber practical assignment.

## Objectives

* Perform passive and active scanning using OWASP ZAP
* Identify common OWASP Top 10 vulnerabilities
* Document findings and remediation strategies

## Tools Used

* DVWA (Localhost)
* OWASP ZAP
* Web Browser
* GitHub

## Methodology

1. Proxy DVWA traffic through OWASP ZAP
2. Crawl application using Spider
3. Perform Active Scan
4. Analyze alerts and risks
5. Document vulnerabilities and remediation

## Key Findings

* Remote Code Execution - CVE-2012-1823
* Source Code Disclosure - CVE-2012-1823
* Absence of Anti-CSRF Tokens
* Content Security Policy (CSP) Header Not Set
* Directory Browsing

## Remediation Summary

* Input validation and output encoding
* Prepared SQL statements
* CSRF tokens
* Secure HTTP headers
* Principle of least privilege

## Disclaimer

This assessment was conducted on an intentionally vulnerable application in a controlled lab environment for educational purposes only.
