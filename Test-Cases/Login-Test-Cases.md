# Login Test Cases

**Website:** https://demo.nopcommerce.com/
**Feature:** User Login

## LOGIN-001: Log in with valid details

**Precondition:** A registered user account exists.

### Test Steps

1. Open the nopCommerce Demo Store.
2. Click **Log in**.
3. Enter a registered email address.
4. Enter the correct password.
5. Click **Log in**.

**Expected Result:**
The user should be logged in and redirected to the homepage. The Log out option should be displayed.

**Actual Result:**
The homepage opened, and the Log out option was displayed.

**Status:** PASS

## LOGIN-002: Log in with an incorrect password

**Precondition:** A registered user account exists.

### Test Steps

1. Open the login page.
2. Enter a registered email address.
3. Enter an incorrect password.
4. Click **Log in**.

**Expected Result:**
The user should not be logged in, and an appropriate error message should be displayed.

**Actual Result:**
The following messages were displayed:

- “Login was unsuccessful. Please correct the errors and try again.”
- “The credentials provided are incorrect”

The user was not logged in.

**Status:** PASS

## LOGIN-003: Log in with empty fields

### Test Steps

1. Open the login page.
2. Leave the email and password fields empty.
3. Click **Log in**.

**Expected Result:**
The user should not be logged in, and a validation message should be displayed.

**Actual Result:**
The message “Please enter your email” was displayed, and the user was not logged in.

**Status:** PASS