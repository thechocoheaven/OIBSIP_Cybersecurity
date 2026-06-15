# Task 3: SQL Injection on DVWA

## AICTE OIB-SIP Cybersecurity Internship

## Objective

The objective of this task is to demonstrate and understand an SQL Injection vulnerability using **DVWA (Damn Vulnerable Web Application)** with a low security configuration.

## Tools Used

* DVWA
* Docker Desktop
* Web Browser

## Environment Setup

DVWA was deployed locally using Docker Desktop and tested in a controlled environment.

Application:

* DVWA (Damn Vulnerable Web Application)

Security Level:

* Low

## Vulnerability Description

SQL Injection is a web application vulnerability where attackers can manipulate SQL queries by injecting malicious input into user-controlled fields.

If an application does not properly validate user input, attackers may access unauthorized database information or bypass application security.

## SQL Injection Payload Tested

Payload used:

```
1' OR '1'='1
```

This payload was used to demonstrate how improper input handling can modify SQL query logic and return unintended results.

## Testing Process

1. Installed and launched DVWA using Docker Desktop.
2. Logged into the DVWA application.
3. Changed the security level to Low.
4. Navigated to the SQL Injection module.
5. Entered the SQL Injection payload.
6. Observed the database response.

## Impact

SQL Injection vulnerabilities may allow attackers to:

* Access unauthorized database records
* Bypass authentication mechanisms
* Extract sensitive information
* Modify or delete database data

## Prevention Measures

To prevent SQL Injection attacks:

* Use prepared statements
* Use parameterized SQL queries
* Validate and sanitize user input
* Apply proper database permissions
* Follow secure coding practices

## Screenshots

Included screenshots:

* DVWA security level configuration
* SQL Injection payload testing
* SQL Injection output/result

## Conclusion

This task demonstrated how SQL Injection vulnerabilities occur due to insecure input handling and highlighted the importance of secure development practices for protecting web applications.
