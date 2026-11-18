# JusRide – Login Test Scenarios

## Module: Login

**Testing Type:** Functional Testing

**Objective:** To verify that existing users can log in to the JusRide application using their registered mobile number and OTP.

### Test Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| LG_001 | Verify that the user can open the JusRide application. | Application should launch successfully. |
| LG_002 | Verify that the login screen is displayed. | Login screen should be displayed correctly. |
| LG_003 | Verify login using a valid registered mobile number. | OTP should be sent to the registered mobile number. |
| LG_004 | Verify login using an invalid mobile number. | Appropriate validation message should be displayed. |
| LG_005 | Verify login using an unregistered mobile number. | User should be guided through the new-user signup flow. |
| LG_006 | Verify OTP entry using a valid OTP. | User should be authenticated successfully. |
| LG_007 | Verify OTP entry using an invalid OTP. | Appropriate error message should be displayed. |
| LG_008 | Verify OTP entry using an expired OTP. | System should reject the expired OTP. |
| LG_009 | Verify the Resend OTP functionality. | A new OTP should be sent to the registered mobile number. |
| LG_010 | Verify login after successful OTP verification. | User should be redirected to the Home Page. |
| LG_011 | Verify login with an empty mobile number. | Appropriate validation message should be displayed. |
| LG_012 | Verify login with an incomplete mobile number. | Appropriate validation message should be displayed. |

### Testing Notes

- Login is performed using a registered mobile number and OTP.
- Email ID is not used as a login method.
- Existing users should be redirected to the Home Page after successful OTP verification.
- Unregistered users should be guided through the signup flow.
- Use test mobile numbers and test OTPs in the testing environment.
