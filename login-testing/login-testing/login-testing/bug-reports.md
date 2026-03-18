# Bug Reports — Login

## Bug 01 — Login accepts empty password
**Steps to Reproduce:**
1. Enter a valid email
2. Leave password field empty
3. Click on the login button

**Expected Result:**
The system should display an error message asking for the password.

**Actual Result:**
The system allows login attempt without password validation.

**Severity:** High  
**Priority:** High

---

## Bug 02 — Invalid email format is accepted
**Steps to Reproduce:**
1. Enter an invalid email format (example: usergmail.com)
2. Enter any password
3. Click on the login button

**Expected Result:**
The system should validate the email format and display an error message.

**Actual Result:**
The system accepts the invalid email format.

**Severity:** Medium  
**Priority:** Medium

---

## Bug 03 — Error message is not clear
**Steps to Reproduce:**
1. Enter wrong credentials
2. Click on the login button

**Expected Result:**
A clear error message should explain that the credentials are invalid.

**Actual Result:**
A generic or unclear message is displayed.

**Severity:** Low  
**Priority:** Medium
