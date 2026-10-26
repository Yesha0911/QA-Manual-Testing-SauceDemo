# Manual Testing – SauceDemo Checkout Test Cases

**Project:** SauceDemo Manual Testing  
**Module:** Checkout  
**Website:** https://www.saucedemo.com/  
**Testing Type:** Functional Testing

## Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC_CHECKOUT_001 | Open checkout | Open cart and click Checkout | Checkout Information page should open | Checkout Information page opened | Pass |
| TC_CHECKOUT_002 | Submit empty form | Leave all fields empty and click Continue | First Name required error should appear | Error: First Name is required | Pass |
| TC_CHECKOUT_003 | Missing Last Name | Enter First Name; leave Last Name and Postal Code blank | Last Name required error should appear | Error: Last Name is required | Pass |
| TC_CHECKOUT_004 | Missing Postal Code | Enter First Name and Last Name; leave Postal Code blank | Postal Code required error should appear | Error: Postal Code is required | Pass |
| TC_CHECKOUT_005 | Valid checkout information | Enter valid details and click Continue | Checkout Overview page should open | Checkout Overview page opened | Pass |
| TC_CHECKOUT_006 | Finish order | Click Finish on the Overview page | Order confirmation should appear | “Thank you for your order!” displayed | Pass |
| TC_CHECKOUT_007 | Back Home navigation | Click Back Home on the confirmation page | Products page should open | Products page opened | Pass |

## Test Execution Summary

- Total Test Cases: 7
- Passed: 7
- Failed: 0
- Blocked: 0
- Not Run: 0

**Overall Result:** All 7 checkout test cases passed.

**Note:** Results are based on manual execution on the SauceDemo demo website.