# Bug Reports — Sample Banking Application

## 1. Project Overview

**Project:** Sample Banking Application  
**Document Type:** Sample Defect Reports  
**Application Type:** Fictional Web/Mobile Banking Application

### Purpose

This document demonstrates how software defects can be documented using clear reproduction steps, expected and actual results, severity, and supporting evidence.

**Important:** The reports below are hypothetical examples. They are not verified defects from an actual application.

## 2. Sample Bug Report BR-001

**Title:** Transfer confirmation is not displayed after a successful fund transfer

**Module:** Fund Transfer

**Severity:** Major — proposed pending impact assessment

**Priority:** High — proposed

**Environment:** Fictional banking test environment

**Precondition:** The user is authenticated and has sufficient test funds.

### Steps to Reproduce

1. Log in with an authorized test account.
2. Navigate to Fund Transfer.
3. Enter valid beneficiary details.
4. Enter an allowed transfer amount.
5. Complete the confirmation process.
6. Observe the result displayed by the application.

### Expected Result

The application should display a clear confirmation when the transfer has completed successfully.

### Actual Result

Hypothetical example: The transfer is completed, but no confirmation is displayed to the user.

### Impact

The user may be uncertain whether the transaction succeeded and may attempt to submit it again.

### Evidence

Not available. Screenshots and transaction references should be attached only after reproducing the issue in an authorized test environment.

### Status

Not Verified — Illustrative Example

---

## 3. Sample Bug Report BR-002

**Title:** Login form accepts an empty password field without required-field validation

**Module:** Authentication

**Severity:** Minor — proposed pending impact assessment

**Priority:** Medium — proposed

**Environment:** Fictional web application

**Precondition:** The login page is accessible.

### Steps to Reproduce

1. Open the login page.
2. Enter a registered username.
3. Leave the password field empty.
4. Click Login.
5. Observe the validation response.

### Expected Result

The application should indicate that the password field is required and should not submit the form.

### Actual Result

Hypothetical example: The application submits the form without displaying the expected required-field validation.

### Impact

The user receives an unclear response and may have difficulty understanding what is required to proceed.

### Evidence

Not available. Capture the relevant screen only after reproducing the issue.

### Status

Not Verified — Illustrative Example

---

## 4. Sample Bug Report BR-003

**Title:** Account balance does not refresh after a completed transaction

**Module:** Account Dashboard

**Severity:** Major — proposed pending impact assessment

**Priority:** High — proposed

**Environment:** Fictional banking test environment

**Precondition:** An authorized test user has completed a successful transaction.

### Steps to Reproduce

1. Log in with an authorized test account.
2. Record the displayed account balance.
3. Complete an approved test transaction.
4. Return to the account dashboard.
5. Refresh the balance or revisit the dashboard.
6. Compare the displayed balance with the expected balance.

### Expected Result

The application should display the latest correct account balance according to the transaction processing and balance-update rules.

### Actual Result

Hypothetical example: The displayed balance remains unchanged even though the transaction has completed successfully.

### Impact

An incorrect or stale balance may mislead the user and affect subsequent financial decisions.

### Evidence

Not available. Record the transaction reference and relevant screenshots after reproducing the issue in an authorized test environment.

### Status

Not Verified — Illustrative Example

---

## 5. Defect Reporting Guidelines

A useful defect report should include:

- A clear, concise title.
- The affected module or feature.
- Environment and relevant test data.
- Preconditions.
- Numbered reproduction steps.
- Expected and actual results.
- Severity and priority, assigned using the team's guidelines.
- Supporting evidence where available.
- Current status and links to related test cases, where applicable.

## 6. Conclusion

These examples demonstrate a structured approach to defect documentation.

In a real testing engagement, every reported defect should be supported by reproducible observations and appropriate evidence before being presented as a confirmed finding.
