# Web Application Penetration Testing

**Done by:** Abhishek Nair
**Internship:** NETWORKWALKS, Week 4 Project

A hands-on security assessment carried out in an authorized lab environment. The project covers SQL Injection against a login form, access control testing, network reconnaissance, and password recovery on protected PDF files.

## Overview

The goal of this project was to practise how security professionals find and evaluate weaknesses in a web application. Working only on systems I was permitted to test, I looked at how poor input handling, weak authorization, and weak passwords can expose an application and its data.

## Objectives

- Understand common web application vulnerabilities and their impact
- Test whether a login mechanism is vulnerable to SQL Injection
- Check authentication and authorization controls
- Review access to restricted patient-related and administrative pages
- Use network reconnaissance and analysis techniques
- Assess the strength of password-protected PDF documents
- Record findings and the risks they pose

## Tools and Techniques

| Area | Details |
|---|---|
| SQL Injection | Tested an authentication bypass with the `admin'--` payload |
| Network analysis | Used security tools to gather and examine network information |
| PDF password recovery | Used dedicated recovery tools to test password strength |
| Browser developer tools | Inspected application responses and page behaviour |
| Command line | Ran testing and analysis commands |

## What I Did

### 1. SQL Injection: Authentication Bypass
I tested the payload `admin'--` on the login form. It showed how a query built directly from user input can let an attacker skip the password check entirely.

### 2. Access Control Testing
I examined which pages could be reached without proper permission, including patient-related records and administrative functions, to spot authorization gaps.

### 3. Network Reconnaissance and Analysis
I used network analysis tools to understand what information can be collected about a target and why reconnaissance is the first stage of a penetration test.

### 4. PDF Password Recovery
I ran password recovery against a protected PDF to see how quickly weak passwords can be cracked and what makes a password resistant.

## Concepts Covered

- SQL Injection
- Authentication and authorization
- Access control vulnerabilities
- Network reconnaissance
- Password security
- PDF document protection
- Web application security testing
- Ethical hacking methodology

## Key Takeaways

Small oversights can have serious consequences. Parameterized queries, strong authentication, properly enforced access controls, and strong passwords are basic requirements for protecting an application and its users.

## Disclaimer

This project was done for educational purposes in an authorized testing environment. All testing and password recovery was performed only on systems and files that I had permission to test.

## Acknowledgements

Thanks to NETWORKWALKS and Waqas Karim (CCIE) for their guidance and support.
