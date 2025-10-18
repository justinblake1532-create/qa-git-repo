# Login Feature Test Cases

## Test Case 1: Successful Login
- **Description:** Verify that a user can log in with valid credentials.
- **Steps:**
    1. Navigate to the login page.
    2. Enter a valid username.
    3. Enter a valid password.
    4. Click the "Login" button.
- **Expected Result:** User is successfully logged in and redirected to the dashboard.

## Test Case 2: Invalid Password
- **Description:** Verify an error message is shown for an invalid password.
- **Steps:**
    1. Navigate to the login page.
    2. Enter a valid username.
    3. Enter an invalid password.
    4. Click the "Login" button.
- **Expected Result:** An error message "Invalid password" is displayed.

## Found Bug: "Invalid password" message is incorrect
The system shows "Authentication failed" instead of "Invalid password". The test case needs to be updated.
- **Expected Result:** An error message "Authentication failed" is displayed.

