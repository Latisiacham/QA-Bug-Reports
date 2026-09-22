# Profile Test Cases

**Website:** https://demo.nopcommerce.com/
**Feature:** Customer Profile

## PROFILE-001: View saved customer information

**Precondition:** The user is logged in.

### Test Steps

1. Open the nopCommerce Demo Store.
2. Click **My account**.
3. View the Customer info page.
4. Check the saved first name, last name and email address.

**Expected Result:**
The Customer info page should display the correct registered account details.

**Actual Result:**
The registered first name, last name and email address were displayed correctly.

**Status:** PASS

## PROFILE-002: Update customer information

**Precondition:** The user is logged in and viewing the Customer info page.

### Test Steps

1. Change the first name to “Bonita QA”.
2. Leave the remaining account details unchanged.
3. Click **Save**.

**Expected Result:**
The updated first name should be saved, and a success message should be displayed.

**Actual Result:**
The message “The customer info has been updated successfully.” was displayed. “Bonita QA” remained in the first-name field.

**Status:** PASS

## PROFILE-003: Save the profile with an empty first name

**Precondition:** The user is logged in and viewing the Customer info page.

### Test Steps

1. Clear the first-name field.
2. Click **Save**.

**Expected Result:**
The profile should not be updated, and a validation message should be displayed.

**Actual Result:**
The message “First name is required.” was displayed.

**Status:** PASS