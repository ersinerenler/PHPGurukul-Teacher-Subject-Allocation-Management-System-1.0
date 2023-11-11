# PHPGurukul Teacher Subject Allocation Management System 1.0

Welcome to the PHPGurukul Teacher Subject Allocation Management System 1.0 repository. This project aims to provide a robust system for managing teacher subject allocations.

## Security Vulnerabilities

### CVE-2023-46024

- **Description:** Vulnerable to SQL Injection via `index.php`, 'searchdata' parameter.
- **Affected Version:** 1.0
- **Impact:** Attackers can manipulate the 'searchdata' parameter, potentially gaining unauthorized access.
- **Solution:** Implement proper input validation and utilize parameterized queries in `index.php`.

### CVE-2023-46025

- **Description:** Vulnerable to SQL Injection via `teacher-info.php`, 'id' parameter.
- **Affected Version:** 1.0
- **Impact:** SQL injection may lead to unauthorized access or data manipulation.
- **Solution:** Ensure input validation and utilize parameterized queries in `teacher-info.php`.

### CVE-2023-46026

- **Description:** Vulnerable to Stored Cross-Site Scripting (XSS) via `profile.php`, 'adminname' parameter.
- **Affected Version:** 1.0
- **Impact:** Attackers can inject malicious scripts into the 'adminname' parameter.
- **Solution:** Implement proper input validation and output encoding in `profile.php`.

---
