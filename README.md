
# Pentesting Report: juice shop Web Application

## Overview
This document provides a detailed security assessment of the **juice shop** legacy web application, specifically targeting vulnerabilities identified through a Blackbox Web Application Penetration Test. The engagement was conducted between **October 1, 2024** (testing date) and **October 20, 2024** (report delivery date).

The report covers high, medium, and low-risk vulnerabilities, along with recommended remediation measures to enhance the security posture of the juice shop web application. The assessment was carried out using a combination of manual testing and automated tools to ensure thorough evaluation.

## Key Sections
1. **Security Engagement Summary**  
   A high-level overview of the scope, goals, and methodology of the pentesting engagement.
   
2. **Risk Analysis**  
   A detailed breakdown of the overall risk level associated with the application, prioritizing high-risk vulnerabilities such as Broken Authentication and Sensitive Data Exposure.

3. **Vulnerability Summary**  
   Identifies and categorizes vulnerabilities based on their severity:
   - **High Risk:** Broken Authentication, Unrestricted File Upload, Broken Access Control, Sensitive Data Exposure, SQL Injection, and more.
   - **Medium Risk:** XSS vulnerabilities, HTTP header injection, Database schema exposure.
   - **Low Risk:** Issues like weak CORS configurations and Client-Side XSS protection.
   
4. **Vulnerability Details**  
   Explains the significant vulnerabilities with validation steps, exploit evidence, and their potential impact on the application. It also includes recommendations for fixing the issues.

5. **Methodology**  
   Describes the penetration testing process used, including information gathering, vulnerability scanning, and exploitation techniques. The tools used in the assessment include:
   - Burp Suite
   - Nmap
   - SQLMap
   - Hydra
   - FFUF, and more.

## Authors
The penetration test was conducted by:
- **Youssef Fathy Abdul Moez**
- **Mohammed Khaled Abdelraziq**
- **Hadeer Amr Fawzy**
- **Toqa Ayman Gomaa**

## How to Use This Report
This report is intended for developers, security professionals, and system administrators responsible for maintaining and securing the Dojuicer web application. It provides actionable insights into improving the application's security and protecting it from potential threats.

