---
description: Security best practices for code and architecture.
---

# Security Best Practices

## Input Validation
- Validate all user inputs on both client and server sides.
- Sanitize data to prevent XSS (Cross-Site Scripting).

## Authentication & Authorization
- Use established libraries for auth (avoid rolling your own crypto).
- Implement proper role-based access control (RBAC).

## Data Protection
- Use HTTPS for all communications.
- Store sensitive data (like tokens) securely (e.g., HttpOnly cookies).
- Avoid exposing API keys or secrets in client-side code.

## Dependencies
- Regularly check for vulnerable dependencies (`npm audit`).
- Pin dependency versions to avoid surprise breakages or supply chain attacks.
