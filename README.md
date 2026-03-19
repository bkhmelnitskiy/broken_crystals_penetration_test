# 🔐 Web Application Penetration Testing – Broken Crystals

## 📌 Overview

This project presents a full **penetration testing engagement** conducted on the *Broken Crystals* web application as part of a cybersecurity assessment.

The goal was to identify security vulnerabilities, assess their impact, and provide remediation recommendations to improve the overall security posture of the application.

---

## 🎯 Scope

The assessment covered:

* Web application (frontend & backend)
* REST API & GraphQL endpoints
* Authentication & authorization mechanisms
* User and admin functionalities
* File upload and messaging features

---

## 🧪 Methodology

Testing was performed using a **gray-box approach**, combining:

* Manual testing
* Automated vulnerability scanning
* Threat modeling (STRIDE)
* OWASP Top 10 & OWASP WSTG methodologies

Key phases:

* Application mapping
* Functionality & business logic analysis
* Vulnerability identification & exploitation
* Reporting

---

## 🚨 Key Findings

The assessment identified multiple vulnerabilities, including:

### 🔴 Critical

* Remote Code Execution (RCE)
* Broken Access Control
* JWT Authentication Bypass (alg=none)
* Weak default admin credentials

### 🟠 High

* Stored XSS
* Path Traversal
* Sensitive data exposure
* Missing rate limiting (DoS risk)

### 🟡 Medium

* SSRF
* Open Redirect
* IDOR (Insecure Direct Object References)
* Lack of logging & monitoring

---

## 🛠️ Tools & Techniques

* Burp Suite
* OWASP ZAP
* Manual exploitation
* Custom payloads
* API testing tools

---

## 📊 Results

* 8 Critical vulnerabilities
* 7 High vulnerabilities
* 9 Medium vulnerabilities

Each issue includes:

* Description
* Impact analysis
* Proof of Concept (PoC)
* Remediation recommendations

---

## 📈 Outcome

The project demonstrated how real-world web applications can be compromised through:

* Misconfigured authentication
* Poor input validation
* Lack of access control

Recommendations were provided to significantly improve system security.

---

## ⚠️ Disclaimer

This project was conducted in a controlled **test environment** for educational purposes only.
