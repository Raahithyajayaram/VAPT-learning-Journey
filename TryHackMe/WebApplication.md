# 🛡️ Web Application Security - TryHackMe Notes

**Module**: Basics of Web Application Security  
**Platform**: TryHackMe  
**Status**: In Progress  
**Topics Covered**: Web architecture, HTTP requests, authentication, identity, cryptography, and security headers.

---

## ✅ Completed Tasks

### 1. Introduction
- Overview of web application security fundamentals.
- Introduction to attack surfaces, client-server architecture.

### 2. Web Application Overview
- What makes a web app vulnerable?
- Role of user input, sessions, and form handling.

### 3. Uniform Resource Locator (URL)
- Anatomy of a URL.
- How attackers abuse query strings and paths.

### 5. HTTP Request: Request Line and Methods
- GET, POST, PUT, DELETE methods.
- Idempotent vs non-idempotent methods.

### 6. HTTP Request: Headers and Body
- Request headers like `Host`, `User-Agent`, `Cookie`, etc.
- Understanding request body formats (`form-data`, `JSON`, etc.).

---

## 🔜 Incomplete Tasks (To Do)

- [ ] **Task 4**: HTTP Messages (structure of request/response)
- [ ] **Task 7**: HTTP Response: Status Line and Status Codes  
- [ ] **Task 8**: HTTP Response: Headers and Body  
- [ ] **Task 9**: Security Headers (e.g., CSP, X-Frame-Options, etc.)  
- [ ] **Task 10**: Practical Task – Making HTTP Requests  

---

## 🔐 Security Concepts Covered

- **Authentication & Identity**
  - Differentiating between authentication and authorization.
  - Tokens, session IDs, and login flows.

- **Cryptography**
  - HTTPS and TLS overview.
  - Hashing, salting, and encryption in data security.

- **HTTP Request Patterns**
  - Structure and behavior of client-server communication.
  - How attackers can manipulate HTTP methods and parameters.

---

## 📌 Tools Mentioned

- `curl` for HTTP requests
- Proxy tools like Burp Suite (implied for future use)
- Browser DevTools for request inspection

---

## 🗂️ Notes

- This module lays the foundation for web app pentesting.
- Focus is on understanding request flow and security headers before diving into attack vectors.
- Real-world scenarios are used to explain why misconfigured HTTP headers or poor authentication can lead to breaches.

---

> 📌 _Work in Progress: As I complete the rest of the tasks, I’ll update this doc with more detailed insights, practical examples, and tool usage._

