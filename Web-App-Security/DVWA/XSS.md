# Cross-Site Scripting (XSS) – DVWA

## Description
XSS allows attackers to inject malicious scripts into web pages viewed by users.

## Lab Environment
- Application: DVWA
- Security Level: Low
- Tool Used: Burp Suite

## Steps to Reproduce
1. Opened XSS module in DVWA
2. Entered script payload in input field
3. Observed script execution in browser

## Impact
- Session hijacking
- Credential theft

## Remediation
- Proper input validation
- Output encoding
- Content Security Policy (CSP)
