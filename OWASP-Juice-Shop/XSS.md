# Cross-Site Scripting (XSS) – OWASP Juice Shop

## Description
XSS allows injection of malicious scripts into web pages.

## Lab Environment
- Application: OWASP Juice Shop
- Tool Used: Browser / Burp Suite

## Steps to Reproduce
1. Found vulnerable input field
2. Injected JavaScript payload
3. Observed script execution

## Impact
- Session hijacking
- User impersonation

## Remediation
- Output encoding
- Input sanitization
- Content Security Policy
