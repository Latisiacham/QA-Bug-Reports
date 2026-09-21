# Registration Test Cases

**Website:** https://demo.nopcommerce.com/
**Feature:** User Registration

## REG-001: Register with valid details

**Precondition:** The email address has not been registered before.

### Test Steps

1. Open the nopCommerce Demo Store.
2. Click **Register**.
3. Enter a valid first name.
4. Enter a valid last name.
5. Enter a unique email address.
6. Enter a valid password.
7. Enter the same password in the Confirm password field.
8. Click **Register**.

**Expected Result:**
The account should be created successfully.

**Actual Result:**
The message “Your registration completed” was displayed.

**Status:** PASS

## REG-002: Register with an existing email address

**Precondition:** An account already exists with the test email address.

### Test Steps

1. Open the registration page.
2. Enter a valid first name and last name.
3. Enter an email address that is already registered.
4. Enter a valid matching password and confirmation password.
5. Click **Register**.

**Expected Result:**
The account should not be created, and an appropriate error message should be displayed.

**Actual Result:**
The message “The specified email already exists” was displayed.

**Status:** PASS

## REG-003: Register with empty required fields

### Test Steps

1. Open the registration page.
2. Leave all required fields empty.
3. Click **Register**.

**Expected Result:**
The account should not be created, and validation messages should appear for all required fields.

**Actual Result:**

- “First name is required”
- “Last name is required”
- “Email is required.”
- “Password required.”

The account was not created.

**Status:** PASS