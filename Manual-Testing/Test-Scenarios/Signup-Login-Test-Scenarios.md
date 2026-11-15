# JusRide – Signup & Login Test Scenarios

## Module: Signup & Login

**Testing Type:** Functional Testing

**Objective:** To verify that users can register and log in to the JusRide application using their mobile number and OTP.

### Test Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| SL_001 | Verify that the user can open the JusRide application. | Application should launch successfully. |
| SL_002 | Verify that the login/signup screen is displayed. | Login/signup screen should be displayed correctly. |
| SL_003 | Verify login using a valid registered mobile number. | OTP should be sent to the entered mobile number. |
| SL_004 | Verify login using an invalid mobile number. | Appropriate validation message should be displayed. |
| SL_005 | Verify login with an unregistered mobile number. | User should be guided through the new-user registration flow. |
| SL_006 | Verify OTP entry using a valid OTP. | User should be authenticated successfully. |
| SL_007 | Verify OTP entry using an invalid OTP. | Appropriate error message should be displayed. |
| SL_008 | Verify OTP entry using an expired OTP. | System should reject the expired OTP. |
| SL_009 | Verify the Resend OTP functionality. | A new OTP should be sent to the registered mobile number. |
| SL_010 | Verify that a new user is redirected to the profile creation screen after OTP verification. | Profile creation screen should be displayed. |
| SL_011 | Verify profile creation with valid First Name and Last Name. | User profile should be created successfully. |
| SL_012 | Verify profile creation without entering the optional Nickname. | User should be able to complete registration without a nickname. |
| SL_013 | Verify profile creation with a valid Email ID. | Email ID should be accepted. |
| SL_014 | Verify that the mobile number is automatically populated in the profile. | Verified mobile number should be displayed. |
| SL_015 | Verify profile creation with mandatory fields left blank. | Appropriate validation messages should be displayed. |
| SL_016 | Verify that the user can complete profile creation. | User should be redirected to the Home Page. |
| SL_017 | Verify login for an existing user. | User should be redirected to the Home Page after successful OTP verification. |

### Testing Notes

- Login/signup is performed using a mobile number and OTP.
- Nickname is optional during profile creation.
- Email ID is collected as a profile detail and is not used as the login method.
- Use test mobile numbers and test OTPs in the testing environment.

