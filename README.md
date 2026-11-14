# SQL Injection | Blue team and Red Team Security Analysis
This project investigates SQL Injection (SQLi) vulnerabilities through practical penetration testing and defensive security analysis using the Hack The Box 'Appointment' machine.
## Team Members
## 0. Executive Summary
This report delves into the concept of SQL injection (SQLi) vulnerabilities and how
unvalidated user input is exploited to generate malicious SQL requests using a backend
database on a web application service such as a webpage. The ‘Appointment’ machine
contained a login webpage service which had limited defences against SQLi and as a
result, Authentication Bypass, UNION-based and automated blind SQLi were practically
demonstrated to bypass authentication and extract sensitive user data entirely by
manipulating SQL logic. These findings effectively outlined the vulnerability of the
machine due to its severe lack of input validation and sanitation. The proposed
defensive techniques to harden the ‘Appointment’ were parameterised queries, input
validation and sanitation and a Web Application Firewall (WAF). These defences would
significantly mitigate the machine’s vulnerability to SQLi as malicious requests would
be blocked and repeated suspicious automated requests would be blocked by the WAF.
Ultimately, this report demonstrates how SQLi must be considered as a critical risk to
web applications and must have layered defences and protocols implemented to
secure systems.

## 1. Introduction
## 2. Attacking
### 2.1 HTB Machine ‘Appointment’ - Enumeration
### 2.2 In-Band SQLi
#### 2.2.1 Authentication Bypass SQLi
#### 2.2.2 Union-based SQLi
### 2.3 Automated Blind SQLi (SQLMAP)
## 3. Defending 
### 3.1 Parameterised Queries / Prepared Statements
### 3.2 Input Validation and Sanitisation
### 3.3 Web Application Firewalls and Error Handling
## 4. Discussion
## 5. Lessons Learned
## 6. References
