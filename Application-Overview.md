# JusRide – Application Overview

## 1. Project Introduction

JusRide is a bicycle community and service application that allows users to plan rides, connect with other cyclists, create groups, share ride activities, and book bicycle maintenance services.

The application also provides AMC and Warranty management features for eligible bicycles.

## 2. Application Modules

| Module | Description |
|---|---|
| Signup & Login | Users register and log in using mobile number and OTP. Profile details include name, nickname and email ID. |
| Home Page | Provides access to Feed, Nearby, Create, Explore and More sections. |
| Plan a Ride | Allows users to create rides using free-text details, maps, GPX files or Strava routes. |
| Groups | Allows users to create groups, invite members, join public groups and request access to private groups. |
| JusCards | Allows users to create and share ride cards with photos and ride statistics. |
| Explore | Helps users discover public JusCards, riders, groups and trending rides. |
| Profile & Settings | Supports profile updates, mobile/email changes, Strava synchronization and ride/follow requests. |
| Service Booking | Allows users to book bicycle services through Home Service, JBC Pickup and I'll Drop options. |
| AMC Management | Users upload their purchase invoice. Invoice details are fetched, and OTP verification is performed using the invoice mobile number when it differs from the registered number. |
| Warranty Management | Users upload their purchase invoice. Invoice details are fetched, and OTP verification is performed using the invoice mobile number when it differs from the registered number. |
| Help & Support | Allows users to raise queries through the Help & Support section. |

## 3. Service Booking – Main User Flow

1. Select city and enter pincode.
2. Select service type.
3. Add a new bicycle or select a saved bicycle.
4. Choose Basic or Advanced service.
5. Review bicycle details and payment summary.
6. Select address or service store, depending on service type.
7. Select available date and time slot.
8. Review booking details and complete payment.
9. Receive booking confirmation and OTP.
10. Track service progress through My Bookings.

### Available Service Types

- Service @ Home – Technician visits the customer's home.
- Service @ Store (JBC Pickup) – Bicycle is collected and returned by pickup staff.
- Service @ Store (I'll Drop) – Customer drops off and collects the bicycle at the selected store.

## 4. AMC & Warranty – High-Level Flow

1. User uploads the purchase invoice.
2. Invoice details are automatically fetched.
3. If the invoice mobile number differs from the registered mobile number, OTP is sent to the invoice mobile number.
4. After successful OTP verification, the respective AMC or Warranty activation process proceeds.

## 5. QA Testing Scope

The following testing areas are relevant to the application:

- Functional Testing
- UI Testing
- Positive and Negative Testing
- End-to-End Testing
- Regression Testing
- API Testing
- Database Validation
- OTP and Verification Testing
- Payment and Booking Flow Testing
- Notification and Status Validation

## 6. Project Objective

The objective of QA testing is to verify that the application's features work as expected, validate end-to-end user journeys, identify defects, and ensure a reliable user experience across the available modules.
