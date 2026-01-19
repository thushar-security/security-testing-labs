# SQL Injection – OWASP Juice Shop

## Description
SQL Injection in Juice Shop allows attackers to manipulate backend queries.

## Lab Environment
- Application: OWASP Juice Shop
- Tool Used: Burp Suite

## Steps to Reproduce
1. Identified injectable input fields
2. Intercepted requests using Burp Suite
3. Injected SQL payloads
4. Observed application behavior

## Impact
- Unauthorized data access
- Data leakage

## Remediation
- Parameterized queries
- Input validation
- Secure ORM usage
