---
layout: default
title: Continuous Security
nav_order: 3
has_children: false
parent: DevSecOps
permalink: /devsecops/coninuous-security/
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Overview

Continuous security is a threat intelligence approach that automates the monitoring of information security controls, vulnerabilities, and other cyber threats to support organizational risk management decisions. To implement continuous security following steps needs to be considered 

1. Implement Threat Modeling during the solution and design phase of the project. A threat model is a structured representation of all the information that affects the security of an application. In essence, it is a view of the application and its environment through the lens of security.

2. Implement automated security tests using tools as part of delivwery pipeline to understand the security posture and risks with the software release candidate and address gaps as early as possible.

3. Implement automated scanning of application and infrastructure at runtime to identify security vulnerabilities and threats and respond with immediate actions in case of any issues.

Following are the common tests that could be considered to be built as part of delivery pipeline to find issues like out-of-date libraries, OWASP top 10 vulnerabilities such as XSS, SQL Injection, CSRF, etc. that can be easily addressed during development

- Dependency Checking & Tracking 
- Static Application Security Testing  (SonarQube, PyLint, Visual Studio, etc.)
- Dynamic Application Security Testing  (OWASP ZAP)
- Container Vulnerability (trivy)

## Participants
1. Solution/Security Architects
2. Developers
2. Security Engineers
3. DevOps Engineers

## Outcomes
- Delivery Pipeline with automated security testing.
- Faster feedback to the developers regarding out of date libraries, vulnerabilities.
- Real time reporting of risks by executing automated security testing & scaning. 
- Accelerated remedial and Patching of issues detected.
- Minimizes the risks associated with security.


## Quick References
- [Secure Coding Practices Quick Reference](https://owasp.org/www-pdf-archive/OWASP_SCP_Quick_Reference_Guide_v2.pdf)
- [Web Application Security Quick Reference](https://owasp.org/www-pdf-archive//OWASP_Web_Application_Security_Quick_Reference_Guide_0.3.pdf)
- [Security Mindset/Creating a Security Program Quick Start](https://github.com/OWASP/Quick-Start-Guide/blob/master/OWASP%20Quick%20Start%20Guide.pdf?raw=true)

## OWASP Cheat Sheets
 Note: OWASP is considered to be the gold-standard in computer security information. OWASP maintains an extensive series of cheat sheets which cover all the OWASP Top 10 and more. Below, many of the more relevant cheat sheets have been summarized. To view all the cheat sheets, check out their [Cheat Sheet Index](https://github.com/OWASP/CheatSheetSeries/blob/master/Index.md).

- [Access Control Basics](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Access_Control_Cheat_Sheet.md)
- [Attack Surface Analysis](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Attack_Surface_Analysis_Cheat_Sheet.md)
- [Content Security Policy (CSP)](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Content_Security_Policy_Cheat_Sheet.md)
- [Cross-Site Request Forgery (CSRF) Prevention](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.md)
- [Cross-Site Scripting (XSS) Prevention](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.md)
- [Cryptographic Storage](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Cryptographic_Storage_Cheat_Sheet.md)
- [Deserialization](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Deserialization_Cheat_Sheet.md)
- [Docker/Kubernetes (k8s) Security](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Docker_Security_Cheat_Sheet.md)
- [Input Validation](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Input_Validation_Cheat_Sheet.md)
- [Key Management](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Key_Management_Cheat_Sheet.md)
- [OS Command Injection Defense](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/OS_Command_Injection_Defense_Cheat_Sheet.md)
- [Query Parameterization Examples](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Query_Parameterization_Cheat_Sheet.md)
- [Server-Side Request Forgery Prevention](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Server_Side_Request_Forgery_Prevention_Cheat_Sheet.md)
- [SQL Injection Prevention](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.md)
- [Unvalidated Redirects and Forwards](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Unvalidated_Redirects_and_Forwards_Cheat_Sheet.md)
- [Web Service Security](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Web_Service_Security_Cheat_Sheet.md)
- [XML Security](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/XML_Security_Cheat_Sheet.md)
 