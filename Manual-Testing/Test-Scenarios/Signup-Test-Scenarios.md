

# JusRide – Signup Test Scenarios

## Module: Signup

**Testing Type:** Functional Testing

**Objective:** To verify that a new user can register in the JusRide application using a mobile number, OTP verification, and profile creation.

### Test Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| SU_001 | Verify that the user can open the JusRide application. | Application should launch successfully. |
| SU_002 | Verify that the signup/login screen is displayed. | Signup/login screen should be displayed correctly. |
| SU_003 | Verify signup using a valid new mobile number. | OTP should be sent to the entered mobile number. |
| SU_004 | Verify signup using an invalid mobile number. | Appropriate validation message should be displayed. |
| SU_005 | Verify OTP entry using a valid OTP. | User should be authenticated successfully and redirected to the profile creation screen. |
| SU_006 | Verify OTP entry using an invalid OTP. | Appropriate error message should be displayed. |
| SU_007 | Verify OTP entry using an expired OTP. | System should reject the expired OTP. |
| SU_008 | Verify the Resend OTP functionality. | A new OTP should be sent to the entered mobile number. |
| SU_009 | Verify that the profile creation screen is displayed after OTP verification. | Profile creation screen should be displayed. |
| SU_010 | Verify profile creation with valid First Name and Last Name. | User should be able to enter the mandatory profile details. |
| SU_011 | Verify profile creation without entering the optional Nickname. | User should be able to complete registration without entering a nickname. |
| SU_012 | Verify profile creation with a valid Email ID. | Email ID should be accepted. |
| SU_013 | Verify that the verified mobile number is automatically populated in the profile. | Verified mobile number should be displayed automatically. |
| SU_014 | Verify profile creation with mandatory fields left blank. | Appropriate validation messages should be displayed. |
| SU_015 | Verify profile creation with valid details. | User profile should be created successfully. |
| SU_016 | Verify redirection after successful profile creation. | User should be redirected to the Home Page. |

### Testing Notes

- Signup is performed using a mobile number and OTP.
- First Name and Last Name are mandatory.
- Nickname is optional.
- Email ID is collected during profile creation.
- Mobile number should be automatically populated after OTP verification.
- Use test mobile numbers and test OTPs in the testing environment.
