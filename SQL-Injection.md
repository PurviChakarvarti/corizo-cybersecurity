# SQL Injection

## Description
SQL injection occurs when untrusted input is included in an SQL query without proper validation, allowing attackers to manipulate the database.

## Impact
An attacker can execute arbitrary SQL commands, potentially accessing sensitive data or manipulating the database.

## Mitigation
Use parameterized queries or prepared statements to sanitize user input and prevent SQL injection.
