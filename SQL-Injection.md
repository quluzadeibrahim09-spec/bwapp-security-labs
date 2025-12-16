# SQL Injection - bWAPP Lab

## Vulnerability Description
SQL Injection is a web vulnerability that allows an attacker to interfere with database queries by injecting malicious SQL code.

## Test Environment
- Application: bWAPP
- OS: Ubuntu
- Method: Manual testing via web browser

## Testing Process
- Identified user input fields vulnerable to SQL Injection
- Tested basic payloads to confirm vulnerabilty
- Observed abnormal application behavior

## Impact
- Unauthorized access to sensitive data
- Potential authentication bypass
- Risk of data manipulation

## Mitigation 
- Use prepared statements (parameterized queries)
- Input validation and sanitization
- Proper error handling
