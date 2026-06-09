# Registration & Onboarding Test Cases

## Overview

This folder contains manual test cases for customer onboarding and registration workflows in a fintech/mobile banking application.

The scenarios validate onboarding reliability, KYC verification, OTP authentication, account creation, onboarding recovery, and business rule validations for both **Individual** and **Business** account types.

---

## Test Coverage

### Individual Account Onboarding

Coverage includes:

* Sign-up screen validation
* Mandatory field validation
* Phone number validation
* Email validation
* Means of identification validation
* OTP verification
* OTP expiration handling
* Incorrect OTP validation
* QoreID facial verification
* Identity mismatch handling
* Read-only prefilled customer data
* Address validation
* Terms & Conditions handling
* Tier 1 account creation
* Session persistence
* Drop-off recovery

---

### Business Account Onboarding

Coverage includes:

* Business sign-up flow
* Business name validation
* Address validation
* OTP verification
* QoreID verification
* KYC restrictions
* Tier limitations
* Post-KYC upgrade flow
* Restricted outward transfer validation
* API and backend failure handling
* Accessibility testing

---

### Validation Testing

Coverage includes:

* Required field validation
* Invalid email format
* Invalid phone number format
* Empty field validation
* Business name validation
* Character restrictions
* Consecutive special character validation
* Emoji and unsupported character validation
* Terms & Conditions validation

---

### Negative Testing

Coverage includes:

* Invalid OTP
* Expired OTP
* Failed QoreID verification
* Existing BVN/NIN prevention
* No internet handling
* Backend/API failures
* Invalid onboarding data
* Restricted access before KYC

---

### Edge Case Testing

Coverage includes:

* App crash recovery
* Session persistence
* Onboarding resume after drop-off
* Resume after OTP stage
* Resume after facial verification
* Resume after account number generation
* Resume during PIN setup
* Multi-session onboarding synchronization
* Duplicate account prevention

---

### Accessibility Testing

Coverage includes:

* Screen reader compatibility
* VoiceOver/TalkBack support
* Keyboard navigation
* Accessible labels and validation messages

---

## Total Coverage

**100+ Manual Test Scenarios**

Coverage includes:

✅ Functional Testing

✅ Validation Testing

✅ Negative Testing

✅ Edge Case Testing

✅ Accessibility Testing

✅ Security & KYC Validation

✅ Session Recovery Testing

---

## Test Artifacts

```text
Registration_Onboarding_Test_Cases.xlsx
```

---

## Status

**Execution Result:** Passed

All executed onboarding scenarios behaved as expected.

---

## Author

**Mercy Abednego**
QA Engineer | Manual & Automation Testing | Fintech Testing
