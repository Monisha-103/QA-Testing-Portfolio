# JusRide – Sample Bug Reports

## Bug Report 1: Application Accepts Invalid Mobile Number

| Field | Details |
|---|---|
| Bug ID | BUG_001 |
| Bug Title | Application accepts an invalid mobile number |
| Module | Signup / Login |
| Severity | High |
| Priority | High |
| Environment | Android – Test Environment |
| Status | New |

**Precondition:** User should be on the Signup/Login screen.

**Steps to Reproduce:**
1. Open the JusRide application.
2. Enter an invalid mobile number.
3. Tap Get OTP.

**Expected Result:**
Application should display an appropriate validation message and should not send OTP.

**Actual Result:**
Application accepts the invalid mobile number and proceeds with the OTP request.

---

## Bug Report 2: Application Accepts Incorrect OTP

| Field | Details |
|---|---|
| Bug ID | BUG_002 |
| Bug Title | Application accepts an incorrect OTP |
| Module | Signup / Login |
| Severity | Critical |
| Priority | High |
| Environment | Android – Test Environment |
| Status | New |

**Precondition:** User should have requested an OTP using a valid mobile number.

**Steps to Reproduce:**
1. Open the JusRide application.
2. Enter a valid mobile number.
3. Tap Get OTP.
4. Enter an incorrect OTP.
5. Tap Submit.

**Expected Result:**
Application should reject the incorrect OTP and display an appropriate error message.

**Actual Result:**
Application accepts the incorrect OTP and allows the user to proceed.

---

## Bug Report 3: Profile Created Without Mandatory Fields

| Field | Details |
|---|---|
| Bug ID | BUG_003 |
| Bug Title | Application allows profile creation without mandatory fields |
| Module | Signup |
| Severity | High |
| Priority | High |
| Environment | Android – Test Environment |
| Status | New |

**Precondition:** User should have successfully verified OTP and reached the profile creation screen.

**Steps to Reproduce:**
1. Open the profile creation screen.
2. Leave First Name and Last Name fields blank.
3. Enter a valid Email ID.
4. Tap Create.

**Expected Result:**
Application should display validation messages for the mandatory fields and should not create the profile.

**Actual Result:**
Application allows profile creation without entering mandatory fields.
