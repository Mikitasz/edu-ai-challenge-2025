# Title
Logout Button Unresponsive on Safari Browser

## Description
The logout button does not respond when clicked in the Safari browser. Users are unable to log out of their accounts, resulting in potential security and usability issues.

## Steps to Reproduce
1. Open the application in Safari (version specified below).
2. Log in with valid user credentials.
3. Navigate to the user profile or any page where the logout button is visible.
4. Click the "Logout" button.

## Expected vs Actual Behavior
**Expected Behavior:**  
Clicking the "Logout" button should log the user out and redirect them to the login page or homepage.

**Actual Behavior:**  
Clicking the "Logout" button does nothing. The user remains logged in, and there is no visible feedback or error message.

## Environment
- Browser: Safari 17.4 (also tested on Safari 17.3)
- OS: macOS Sonoma 14.4
- Application Version: v2.5.1 (staging)
- User Role: Regular user (not admin)

## Severity or Impacts
**Severity:** High  
**Impacts:**  
- Users cannot log out, which is a security risk.
- May affect compliance with privacy and session management requirements.
- Impacts all users accessing the application via Safari.
