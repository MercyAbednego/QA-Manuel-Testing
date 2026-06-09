# Goal Savings Test Cases

## Overview

This folder contains manual test cases for a **Goal Savings / Digital Savings feature** within a fintech/mobile banking application.

The scenarios validate savings plan creation, auto-save scheduling, debit retries, maturity handling, interest accrual, notifications, withdrawals, early termination, admin actions, and failure recovery.

---

## Test Coverage

### Functional Testing

Coverage includes:

* Savings plan creation
* Manual savings
* Auto-save setup
* Plan maturity
* Goal completion
* Withdrawal flow
* Early termination
* Plan archiving
* Duplicate plan creation
* Savings top-up

---

### Validation Testing

Coverage includes:

* Plan name validation
* Minimum target amount validation
* Duration validation
* Required auto-save fields
* Save-now validation
* Date validation
* Frequency validation

---

### Auto-Save & Retry Logic

Coverage includes:

* Successful auto-save debit
* Failed debit handling
* Retry logic validation
* Resume on next frequency cycle
* Wallet balance validation
* Auto-save after target achievement

---

### Financial Validation

Coverage includes:

* Interest accrual validation
* Daily interest calculation
* Early termination deductions
* Withdrawal calculations
* Savings maturity validation
* Target completion validation

---

### Notification Testing

Coverage includes:

* Push notifications
* Email notifications
* Plan creation alerts
* Auto-save success/failure alerts
* Reminder notifications
* Completion notifications
* Withdrawal notifications
* Termination notifications

---

### Negative Testing

Coverage includes:

* Insufficient balance
* Failed debit retries
* Invalid plan setup
* Withdrawal restrictions
* Premature termination attempts

---

### Admin Testing

Coverage includes:

* Admin plan monitoring
* Admin debit logs
* Savings approval workflow
* Flagged account review
* Manual termination

---

### Edge Case Testing

Coverage includes:

* Saving above target
* Repeated debit failures
* Missed debit cycles
* Duplicate savings plans
* UI visibility conditions

---

## Total Coverage

**61 Manual Test Cases**

Coverage includes:

✅ Functional Testing

✅ Validation Testing

✅ Negative Testing

✅ Edge Case Testing

✅ Financial Calculation Testing

✅ Notification Testing

✅ Admin Testing

---

## Test Artifacts

```
The artifacts are provided in PDF format for readability and portfolio presentation.

```

---

## Status

**Execution Result:** Passed

All executed savings scenarios behaved as expected.

---

## Author

**Mercy Abednego**
QA Engineer | Manual & Automation Testing | Fintech Testing

