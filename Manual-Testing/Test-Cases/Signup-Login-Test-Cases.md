# JusRide – Signup & Login Test Cases

## Module: Signup & Login

**Testing Type:** Functional Testing

**Objective:** To verify the Signup and Login functionality using mobile number and OTP.

## 1. Signup Test Cases

### TC_SU_001 – Signup with a Valid Mobile Number

**Precondition:** User should not be registered in the application.

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Open the JusRide application. | Application should launch successfully. |
| 2 | Enter a valid new mobile number. | Mobile number should be accepted. |
| 3 | Tap Get OTP. | OTP should be sent to the entered mobile number. |
| 4 | Enter the valid OTP. | User should be redirected to the profile creation screen. |

### TC_SU_002 – Signup with an Invalid Mobile Number

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Open the JusRide application. | Application should launch successfully. |
| 2 | Enter an invalid mobile number. | Invalid mobile number should be entered or rejected based on field validation. |
| 3 | Tap Get OTP. | Appropriate validation message should be displayed. |

### TC_SU_003 – Verify OTP with an Invalid OTP

**Precondition:** User has entered a valid new mobile number and requested OTP.

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Enter an incorrect OTP. | OTP field should accept the input or show validation. |
| 2 | Submit the OTP. | Appropriate error message should be displayed. |
| 3 | Check the application screen. | User should not be authenticated. |

### TC_SU_004 – Create Profile Without Nickname

**Precondition:** User has successfully verified OTP and reached the profile creation screen.

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Enter First Name. | First Name should be accepted. |
| 2 | Enter Last Name. | Last Name should be accepted. |
| 3 | Leave Nickname field blank. | Nickname should remain optional. |
| 4 | Enter a valid Email ID. | Email ID should be accepted. |
| 5 | Verify the mobile number field. | Verified mobile number should be automatically populated. |
| 6 | Tap Create. | Profile should be created successfully. |
| 7 | Check the application screen. | User should be redirected to the Home Page. |

### TC_SU_005 – Create Profile Without Mandatory Details

**Precondition:** User has successfully verified OTP and reached the profile creation screen.

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Leave First Name and Last Name blank. | Mandatory fields should remain empty. |
| 2 | Tap Create. | Appropriate validation messages should be displayed. |
| 3 | Check the application screen. | Profile should not be created. |

## 2. Login Test Cases

### TC_LG_001 – Login with a Valid Registered Mobile Number

**Precondition:** User should already have an account in JusRide.

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Open the JusRide application. | Application should launch successfully. |
| 2 | Enter a registered mobile number. | Mobile number should be accepted. |
| 3 | Tap Get OTP. | OTP should be sent to the registered mobile number. |
| 4 | Enter the valid OTP. | User should be authenticated successfully. |
| 5 | Check the application screen. | User should be redirected to the Home Page. |

### TC_LG_002 – Login with an Invalid OTP

**Precondition:** User has entered a registered mobile number and requested OTP.

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Enter an incorrect OTP. | OTP should be entered. |
| 2 | Submit the OTP. | Appropriate error message should be displayed. |
| 3 | Check the application screen. | User should not be logged in. |

### TC_LG_003 – Login with an Unregistered Mobile Number

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Open the JusRide application. | Application should launch successfully. |
| 2 | Enter an unregistered mobile number. | Mobile number should be accepted. |
| 3 | Tap Get OTP. | OTP should be sent if the application supports new-user registration through this flow. |
| 4 | Verify the next screen after OTP verification. | User should be guided to the profile creation screen. |

### TC_LG_004 – Login with an Empty Mobile Number

| Step | Test Steps | Expected Result |
|---|---|---|
| 1 | Open the JusRide application. | Application should launch successfully. |
| 2 | Leave the mobile number field blank. | Mobile number field should remain empty. |
| 3 | Tap Get OTP. | Appropriate validation message should be displayed. |
| 4 | Check the application screen. | OTP should not be requested. |

## 3. Test Execution Summary

| Test Case ID | Actual Result | Status |
|---|---|---|
| TC_SU_001 | Not Executed | Not Executed |
| TC_SU_002 | Not Executed | Not Executed |
| TC_SU_003 | Not Executed | Not Executed |
| TC_SU_004 | Not Executed | Not Executed |
| TC_SU_005 | Not Executed | Not Executed |
| TC_LG_001 | Not Executed | Not Executed |
| TC_LG_002 | Not Executed | Not Executed |
| TC_LG_003 | Not Executed | Not Executed |
| TC_LG_004 | Not Executed | Not Executed |


