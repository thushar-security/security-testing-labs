# SQL Injection – DVWA

## Description
SQL Injection is a vulnerability that allows attackers to manipulate backend database queries.

## Lab Environment
- Application: DVWA
- Security Level: Low
- Tool Used: Burp Suite

## Steps to Reproduce
1. Logged into DVWA
2. Navigated to SQL Injection module
3. Intercepted request using Burp Suite
4. Injected payload: ' OR '1'='1 --

## Impact
- Authentication bypass
- Unauthorized data access

## Remediation
- Use prepared statements
- Validate user input
- Apply least privilege to database users

