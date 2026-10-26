# Manual Testing – SauceDemo Login Test Cases

**Project:** SauceDemo Manual Testing  
**Module:** Login  
**Website:** https://www.saucedemo.com/  
**Testing Type:** Functional Testing

## Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | Enter username and password, then click Login | standard_user / secret_sauce | Products page should open | Products page opened successfully | Pass |
| TC_LOGIN_002 | Login with invalid password | Enter valid username and incorrect password | standard_user / wrong123 | Error message should appear | "Epic sadface: Username and password do not match any user in this service" | Pass |
| TC_LOGIN_003 | Login with invalid username | Enter invalid username and valid password | wrong_user / secret_sauce | Error message should appear | "Epic sadface: Username and password do not match any user in this service" | Pass |
| TC_LOGIN_004 | Login with both fields empty | Leave both fields empty and click Login | Blank fields | Validation error should appear | "Epic sadface: Username is required" | Pass |
| TC_LOGIN_005 | Login with empty password | Enter username and leave password blank | standard_user / Blank | Password validation error should appear | Validation error appeared | Pass |
| TC_LOGIN_006 | Verify password masking | Type password in the password field | secret_sauce | Password should be masked | Password displayed as dots | Pass |

## Test Execution Summary

- Total Test Cases: 6
- Passed: 6
- Failed: 0
- Blocked: 0
- Not Run: 0

**Overall Result:** All 6 login test cases passed.

**Note:** Results are based on manual execution on the SauceDemo demo website.