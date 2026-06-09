# Login Test Cases

## Overview

This folder contains manual test cases for authentication and login functionality within a fintech/mobile banking application.

The objective is to validate secure access, credential verification, session management, and authentication reliability across positive, negative, edge, and security scenarios.

---

## Test Coverage

### Positive Testing

* Valid login using username and password
* Valid login using phone number and password
* Successful login after account unlock
* Successful login with valid special characters in password
* Redirect to dashboard after successful login
* Biometric login validation

---

### Negative Testing

* Invalid username
* Invalid phone number
* Invalid password
* Invalid username and password combination
* Empty username/phone number field
* Empty password field
* Both fields empty
* Suspended/deactivated account login
* Backend/server failure handling
* Network interruption during login

---

### Validation Testing

* Password masking
* Show/Hide password toggle
* Login button disabled state
* Leading/trailing spaces handling
* Username trimming validation
* Phone number trimming validation
* Password special character support

---

### Security Testing

* SQL injection prevention
* Unauthorized access prevention
* Account lock after multiple failed attempts
* Locked account access restriction
* Session timeout validation

---

### Edge Cases

* Login drop-off recovery
* Session expiration after inactivity
* Recovery after account unlock
* Login state persistence

---

## Total Coverage

**27 Login Test Cases**

Coverage includes:

✅ Functional Testing
✅ Negative Testing
✅ Validation Testing
✅ Security Testing
✅ Edge Case Testing

---

## Test Artifacts

This folder includes:

```text
Login_Test_Cases.xlsx
```

---

## Status

**Execution Result:** Passed

All scenarios executed successfully and behaved as expected.

---

## Author

**Mercy Abednego**
QA Engineer | Manual & Automation Testing | Fintech Testing
