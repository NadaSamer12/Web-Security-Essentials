# 🛡️ Web Security Controls

This document summarizes the main security controls covered during the **Web Security Essentials** training room on TryHackMe.

## 1. Application Security

### Secure Coding

Use secure development practices, handle errors safely, and avoid exposing sensitive information.

### Input Validation & Sanitization

Validate and sanitize user-supplied input to reduce the risk of injection attacks and unexpected application behavior.

### Access Control

Restrict access to resources and functionality based on user roles and permissions.

---

## 2. Web Server Security

### Logging

Web access logs record information such as:

* Client IP address
* Timestamp
* Requested resource
* HTTP method
* Status code
* User Agent

These logs provide visibility into web activity and can support security investigations.

### Web Application Firewall (WAF)

A WAF inspects HTTP traffic and can block or log potentially harmful requests.

Common detection approaches include:

* Signature-based detection
* Heuristic-based detection
* Anomaly and behavioral analysis
* IP reputation filtering

### Content Delivery Network (CDN)

A CDN can improve both performance and security by:

* Masking the origin server IP
* Providing DDoS protection
* Enforcing HTTPS
* Integrating WAF capabilities

---

## 3. Host Machine Security

### Least Privilege

Run services using accounts with only the permissions they require.

### System Hardening

Disable unnecessary services and close unused ports to reduce the attack surface.

### Antivirus

Endpoint protection can detect and block known malicious files and programs.

---

## 4. General Security Practices

### Strong Authentication

Use strong authentication mechanisms to prevent unauthorized access.

### Patch Management

Keep applications, dependencies, web servers, and operating systems up to date.

### Defense in Depth

Use multiple security controls together rather than relying on a single defensive mechanism.

---

## Key Takeaway

Web security requires protection across the **application, web server, and host machine**. Combining preventive, detective, and mitigating controls helps reduce exposure and improve the overall security posture of a web application.
