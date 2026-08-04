# Towel on the Sunbed – TryHackMe Walkthrough

## Overview

This repository contains a professional walkthrough of the **"Towel on the Sunbed"** room on TryHackMe. The objective of this challenge is to analyze a vulnerable web application, identify the underlying security weakness, and successfully exploit it to retrieve the final flag.

The walkthrough documents the complete assessment process, including web application analysis, browser developer tools, Burp Suite request manipulation, and exploitation of a **Race Condition** vulnerability.

> **Platform:** TryHackMe  
> **Category:** Web Application Security  
> **Difficulty:** Easy–Medium  
> **Primary Vulnerability:** Race Condition

---

## Skills Demonstrated

- Web Application Enumeration
- Browser Developer Tools
- JavaScript Analysis
- Client-Side vs Server-Side Validation
- HTTP Request Interception
- Burp Suite Repeater
- Parallel Request Execution (Last Byte Sync)
- Race Condition Exploitation
- Web Application Security Testing

---

## Tools Used

- Burp Suite Community/Professional
- FoxyProxy
- Browser Developer Tools
- Chromium / Google Chrome
- Nano Editor (Script Override)

---

## Walkthrough Contents

The walkthrough covers:

- Obtaining room access credentials
- Registering a user account
- Analyzing the web application
- Inspecting `dashboard.js`
- Testing client-side validation using Script Override
- Understanding why client-side modification fails
- Intercepting HTTP requests with Burp Suite
- Exploiting the Race Condition vulnerability
- Unlocking the vault
- Retrieving the final flag

---

## Learning Objectives

After completing this walkthrough, you will understand how to:

- Analyze client-side JavaScript
- Differentiate client-side and server-side validation
- Intercept and modify HTTP requests
- Identify Race Condition vulnerabilities
- Execute synchronized requests using Burp Suite
- Exploit application logic flaws safely in a lab environment

---

## Disclaimer

This walkthrough is intended **solely for educational purposes** within the TryHackMe platform.

Do **not** attempt these techniques against systems that you do not own or have explicit permission to test.

---

## Author

**Debmalya Thakur**

Junior System Administrator | Aspiring Penetration Tester | VAPT Enthusiast

GitHub: https://github.com/<your-username>

LinkedIn: https://linkedin.com/in/<your-profile>

---

## License

This project is provided for educational and learning purposes.
