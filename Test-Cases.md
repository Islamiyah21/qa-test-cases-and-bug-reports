# Test Cases — Sample Banking Application

## 1. Project Overview

**Project:** Sample Banking Application  
**Testing Type:** Manual Functional Testing  
**Application Type:** Web/Mobile Banking  
**Status:** Test cases designed; execution pending.

### Objective

To validate the login, account balance, and fund transfer functionalities of a fictional banking application.

These test cases are designed for demonstration purposes and have not been executed against a live application.

## 2. Login Test Cases

| Test Case ID | Test Scenario | Preconditions | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | A registered test user exists | 1. Open the login page. 2. Enter valid credentials. 3. Click Login. | The user should log in successfully. | Not executed | Not Run |
| TC_LOGIN_002 | Login with an incorrect password | A registered test user exists | 1. Open the login page. 2. Enter a valid username and incorrect password. 3. Click Login. | An appropriate error message should appear. | Not executed | Not Run |
| TC_LOGIN_003 | Login with an empty username | Login page is accessible | 1. Leave the username empty. 2. Enter a password. 3. Click Login. | The application should validate the required username field. | Not executed | Not Run |
| TC_LOGIN_004 | Login with an empty password | Login page is accessible | 1. Enter a username. 2. Leave the password empty. 3. Click Login. | The application should validate the required password field. | Not executed | Not Run |
| TC_LOGIN_005 | Login with both fields empty | Login page is accessible | 1. Leave both fields empty. 2. Click Login. | Required-field validation should appear. | Not executed | Not Run |

## 3. Account Balance Test Cases

| Test Case ID | Test Scenario | Preconditions | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC_BAL_001 | View account balance | User is authenticated | 1. Navigate to the account dashboard. 2. Locate the balance section. | The correct account balance should be displayed. | Not executed | Not Run |
| TC_BAL_002 | Refresh account balance | User is authenticated | 1. Record the displayed balance. 2. Refresh the page. | The displayed balance should remain consistent with the latest account data. | Not executed | Not Run |
| TC_BAL_003 | Access account information without authentication | User is logged out | 1. Attempt to open a protected account page directly. | The application should prevent unauthorized access. | Not executed | Not Run |

## 4. Fund Transfer Test Cases

| Test Case ID | Test Scenario | Preconditions | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC_TRF_001 | Transfer funds to a valid beneficiary | Authenticated user has sufficient test funds | 1. Open Fund Transfer. 2. Enter valid beneficiary details. 3. Enter an allowed amount. 4. Review and submit. | The transfer should complete successfully and a confirmation should be displayed. | Not executed | Not Run |
| TC_TRF_002 | Transfer with insufficient funds | Authenticated user has insufficient test funds | 1. Open Fund Transfer. 2. Enter valid beneficiary details. 3. Enter an amount exceeding the available balance. 4. Submit. | The transfer should be rejected with an appropriate message. | Not executed | Not Run |
| TC_TRF_003 | Submit an empty transfer amount | User is authenticated | 1. Open Fund Transfer. 2. Enter beneficiary details. 3. Leave the amount empty. 4. Submit. | The application should validate the required amount field. | Not executed | Not Run |
| TC_TRF_004 | Enter a negative transfer amount | User is authenticated | 1. Open Fund Transfer. 2. Enter beneficiary details. 3. Enter a negative amount. 4. Submit. | The application should reject the invalid amount. | Not executed | Not Run |
| TC_TRF_005 | Attempt to submit a transfer repeatedly | User is authenticated and on the transfer confirmation screen | 1. Submit a transfer. 2. Attempt to submit the same transaction again. | The application should prevent unintended duplicate transactions. | Not executed | Not Run |
| TC_TRF_006 | Verify account balance after a successful transfer | User has sufficient test funds | 1. Record the opening balance. 2. Complete an approved test transfer. 3. Retrieve the closing balance. | The balance should reflect the completed transaction and applicable fees. | Not executed | Not Run |

## 5. Test Execution Notes

- All scenarios are proposed test cases for a fictional banking application.
- Actual results should be recorded only after the relevant tests have been executed.
- Test execution should use authorized test environments and approved test data.
- Financial transactions should never be tested against production accounts without explicit authorization.
- Expected results should be refined using approved business requirements.

## 6. Conclusion

This document demonstrates test case design for common banking workflows, including authentication, account balance enquiries, and fund transfers.

The test cases can be expanded to cover additional business rules, boundary values, security controls, transaction limits, and integration failures.
