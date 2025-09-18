# Bug Reports — The Internet Herokuapp

## Bug 1
**ID:** BUG-001  
**Title:** Error message does not disappear after successful login  
**Steps to Reproduce:**  
1. Go to the login page.  
2. Enter incorrect username or password.  
3. Click "Login".  
4. The error message appears.  
5. Enter correct credentials and click "Login".  
**Expected Result:** The error message disappears.  
**Actual Result:** The error message sometimes remains or briefly appears on the main page.  
**Priority/Severity:** Medium

## Bug 2
**ID:** BUG-002  
**Title:** No password length validation  
**Steps to Reproduce:**  
1. Enter username: `tomsmith`  
2. Leave password empty.  
3. Click "Login".  
**Expected Result:** The form should warn about minimum password length.  
**Actual Result:** The form submits and shows standard error message.  
**Priority/Severity:** Medium

## Bug 3
**ID:** BUG-003  
**Title:** Login button active with empty fields  
**Steps to Reproduce:**  
1. Leave username and password fields empty.  
2. Click "Login".  
**Expected Result:** The button should be disabled or show a warning.  
**Actual Result:** The form submits and shows an error message.  
**Priority/Severity:** Medium

## Bug 4
**ID:** BUG-004  
**Title:** Error messages not differentiated by error type  
**Steps to Reproduce:**  
1. Enter wrong username, correct password → message: "Your username is invalid!"  
2. Enter correct username, wrong password → message: "Your password is invalid!"  
**Expected Result:** Messages should be clearly distinguishable.  
**Actual Result:** Sometimes messages overlap and are not visually clear.  
**Priority/Severity:** Low

## Bug 5
**ID:** BUG-005  
**Title:** Error message disappears too quickly  
**Steps to Reproduce:**  
1. Enter invalid data and click "Login".  
2. Message appears but disappears in 1–2 seconds.  
**Expected Result:** Message should remain until next attempt.  
**Actual Result:** Disappears immediately.  
**Priority/Severity:** Low
