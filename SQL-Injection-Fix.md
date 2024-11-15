# Fixing SQL Injection Vulnerability

### Problem
```sql
SELECT * FROM users WHERE username = '$_POST['username']' AND password = '$_POST['password']';
