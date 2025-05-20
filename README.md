# OTP-VERIFICATION-SYSTEM
A Secure One-Time Password Authentication Solution

OTP Verification is a method of authentication that generates a unique password for one-time use.
Objective of the Project is building a Python-based OTP verification system.
Generate a random 6-digit OTP.
Send OTP to the user’s email address.
Verify the OTP entered by the user.
Provide error handling and retry mechanism.

# Project Architecture
Generate OTP: Create a 6-digit random OTP.
Send OTP: Email the OTP to the user using Python’s smtplib
User Input: Prompt the user to enter the received OTP.
Verify OTP: Validate user input and grant/deny access.
Retry OTP: Allowing user to retry the OTP if incorrect.

# Demo Workflow
Step-by-Step Execution: 
User enters their email address.
OTP is generated and emailed to the user.
User inputs the OTP received in their email.
System verifies OTP:
If correct: Access granted.
If incorrect: Retry prompts up to 3 attempts.

# Testing & Scenarios
Valid OTP entered: Access granted.
Invalid OTP entered: Access Denied.
         1. Incorrect OTP:
         2. Incorrect digits entered
Maximum retry limit reached: Access denied.

![image](https://github.com/user-attachments/assets/bda65606-c5d5-4378-bb2b-4029adb1b1d1)

