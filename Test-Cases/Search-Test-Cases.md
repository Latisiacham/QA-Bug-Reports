# Search Test Cases

**Website:** https://demo.nopcommerce.com/
**Feature:** Product Search

## SEARCH-001: Search using a valid product keyword

### Test Steps

1. Open the nopCommerce Demo Store.
2. Enter “laptop” in the search field.
3. Click **Search**.

**Expected Result:**
The search-results page should open and display products related to laptops.

**Actual Result:**
The search-results page opened. ASUS and Lenovo laptop products were displayed.

**Status:** PASS

## SEARCH-002: Search using a keyword with no matching products

### Test Steps

1. Open the nopCommerce Demo Store.
2. Enter “xyznonexistentproduct123” in the search field.
3. Click **Search**.

**Expected Result:**
The search-results page should indicate that no matching products were found.

**Actual Result:**
The message “No products were found that matched your criteria.” was displayed.

**Status:** PASS

## SEARCH-003: Search with an empty field

### Test Steps

1. Open the nopCommerce Demo Store.
2. Leave the search field empty.
3. Click **Search**.

**Expected Result:**
The search should not continue, and a validation message should be displayed.

**Actual Result:**
A small browser pop-up displayed the message “Search term minimum length is 3 characters”.

**Status:** PASS