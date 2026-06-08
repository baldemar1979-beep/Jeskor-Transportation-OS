# AFP Resource Center MFA Setup Guide

## Purpose

This document provides instructions for setting up Multi-Factor Authentication (MFA) for access to the Amazon Freight Partner (AFP) Resource Center.

The Resource Center uses Salesforce Experience Cloud and requires the Salesforce Authenticator mobile application for secure access.

---

## Overview

All AFP users must complete MFA enrollment before accessing the Resource Center.

The setup process includes:

1. Installing Salesforce Authenticator
2. Logging into the AFP Resource Center
3. Pairing a mobile device
4. Enabling notifications and permissions
5. Configuring backup and recovery options

---

## Required Application

### Salesforce Authenticator

Download from:

- Apple App Store
- Google Play Store

The application is required for identity verification during login.

---

## MFA Enrollment Process

### Step 1 – Install Salesforce Authenticator

- Download Salesforce Authenticator on your mobile device.
- Open the application.
- Keep the application available during setup.

### Step 2 – Reset Resource Center Password

- Open the AFP Resource Center password reset link.
- Create a new password.
- Log in successfully.
- Log out before beginning MFA enrollment.

### Step 3 – Start MFA Enrollment

- Log back into the Resource Center.
- Select:

```
Salesforce Authenticator Mobile App
```

- Click Continue.

### Step 4 – Pair Mobile Device

- Open Salesforce Authenticator.
- Select:

```
Add an Account
```

- Record the two-word phrase displayed.

### Step 5 – Connect Account

- Return to the Resource Center.
- Enter the two-word phrase exactly as shown.
- Select Connect.
- Approve the connection from the mobile device.

---

## Required Permissions

### Notifications

Enable:

- Allow Notifications
- Time Sensitive Notifications
- Lock Screen Notifications
- Notification Center
- Banners

### Location Services

Enable:

```
Allow While Using App
```

### Background Refresh

Enable:

```
Background App Refresh
```

This allows approval requests to be received even when the application is not open.

---

## Future Login Process

When logging into the Resource Center:

1. Enter username and password.
2. Receive notification from Salesforce Authenticator.
3. Approve login request.
4. Access Resource Center.

---

## Alternative Verification Method

If prompted for a verification code:

1. Open Salesforce Authenticator.
2. Retrieve the verification code.
3. Enter the code into the Resource Center login page.
4. Select Verify.

---

## Backup and Recovery

Users should enable account backup.

### iPhone

Use:

- iCloud Backup

### Android

Use:

- Google Account Backup

If backup is not enabled and the phone is lost or replaced, an MFA reset may be required.

---

## Troubleshooting

### Two-Word Phrase Not Working

- Refresh browser.
- Restart Salesforce Authenticator.
- Retry connection.

### No Notification Received

- Open Salesforce Authenticator manually.
- Verify notifications are enabled.

### Lost or Replaced Phone

- Contact AFP Support or Business Coach.
- Request MFA reset.

---

## Related Files

- AFP Partner Onboarding Checklist
- AFP Resource Center Access Guide
- AFP Training Requirements
- AFP Contact Directory

---

## Source

Based on Amazon AFP Resource Center MFA Setup Presentation using Salesforce Authenticator.
