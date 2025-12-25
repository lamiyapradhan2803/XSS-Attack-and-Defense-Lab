# XSS-Attack-and-Defense-Lab
A hands-on cybersecurity lab demonstrating Stored, Reflected, and DOM-based XSS attacks using DVWA and Burp Suite, along with mitigation techniques such as input validation, output encoding, and ModSecurity WAF.

## XSS Attack & Defense Lab
This project is created to understand how Cross-Site Scripting (XSS) vulnerabilities work in web applications and how they can be prevented. All testing was done in a safe, local lab environment for learning purposes.

## 📌 What this project is about
In this lab, I explored three common types of XSS vulnerabilities using DVWA and analyzed web traffic with Burp Suite. After identifying the vulnerabilities, I applied different defense techniques to mitigate the attacks.

## 🎯 Objectives
- Learn the basics of Cross-Site Scripting (XSS)
- Identify Stored, Reflected, and DOM-based XSS
- Observe HTTP requests and responses using Burp Suite
- Understand how input validation and output encoding work
- Use ModSecurity WAF to block XSS attacks

## 🛠 Tools Used
- Kali Linux
- Metasploitable2
- DVWA (Damn Vulnerable Web Application)
- Burp Suite (Community Edition)
- Apache Web Server
- ModSecurity WAF
- OWASP Core Rule Set
- Firefox Browser

## 🔍 XSS Types Covered
- Stored XSS: Malicious input is stored in the database and executed when the page loads.
- Reflected XSS: Input is reflected in the response and executed immediately.
- DOM-based XSS: The vulnerability exists in client-side JavaScript and does not involve the server.

## 🧪 Traffic Analysis
Burp Suite was used to intercept and analyze HTTP requests and responses. This helped in understanding how user input travels through the application.

## 🛡 Defense & Mitigation
- Input validation was applied to restrict unsafe input
- Output encoding was used to display user input safely
- ModSecurity WAF with OWASP CRS was enabled to detect and block XSS attacks

## 📊 Results
After applying the defense mechanisms, XSS attacks were successfully blocked and logged by the WAF. The application became more secure compared to the initial vulnerable state.

## ⚠️ Disclaimer
This project was performed only for educational purposes in a controlled lab environment.

## 👤 Author
Lamiya Laboni Akter Mitu  
Cybersecurity Student
