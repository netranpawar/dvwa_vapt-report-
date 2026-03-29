# DVWA Vulnerability Assessment Report

## Target
Damn Vulnerable Web Application (DVWA)

## Objective
To identify and analyze common web vulnerabilities using penetration testing techniques.

## Tools Used
- Kali Linux
- Nmap
- Burp Suite

---

## Vulnerabilities Identified

### 1. SQL Injection

**Description:**  
SQL Injection allows attackers to manipulate database queries.

**Impact:**  
- Unauthorized data access  
- Database compromise  

**Proof:**  
Payload used:
' OR '1'='1

**Remediation:**  
- Use prepared statements  
- Input validation  

---

### 2. Cross-Site Scripting (XSS)

**Description:**  
XSS allows injection of malicious scripts into web pages.

**Impact:**  
- Session hijacking  
- Data theft  

**Proof:**  
Payload used:
<script>alert(1)</script>

**Remediation:**  
- Output encoding  
- Input sanitization  

---

## Conclusion
This assessment identified critical vulnerabilities that can compromise application security. Proper input validation and secure coding practices are recommended.
