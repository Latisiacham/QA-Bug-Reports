# Checkout Test Cases

**Website:** https://demo.nopcommerce.com/
**Feature:** Shopping Cart and Checkout

## CHECKOUT-001: Add a product to the shopping cart

### Test Steps

1. Search for “laptop”.
2. Open the ASUS laptop product.
3. Click **Add to cart**.
4. Open the shopping cart.

**Expected Result:**
The product should be added to the cart with the correct name, quantity and subtotal.

**Actual Result:**
The message “The product has been added to your shopping cart” was displayed. The correct product appeared with a quantity of 1 and a subtotal.

**Status:** PASS

## CHECKOUT-002: Continue without accepting the terms of service

**Precondition:** The shopping cart contains a product.

### Test Steps

1. Open the shopping cart.
2. Leave the terms-of-service checkbox unchecked.
3. Click **Checkout**.

**Expected Result:**
Checkout should be blocked, and a message should ask the user to accept the terms of service.

**Actual Result:**
Checkout was blocked. The message “Please accept the terms of service before the next step.” was displayed.

**Status:** PASS

## CHECKOUT-003: Complete checkout with valid information

**Precondition:** A registered user has a product in the shopping cart.

### Test Steps

1. Accept the terms of service.
2. Click **Checkout**.
3. Log in with a valid registered account.
4. Enter a valid billing address.
5. Select Ground shipping.
6. Select Check / Money Order as the payment method.
7. Review the order details.
8. Click **Confirm**.

**Expected Result:**
The order should be processed successfully, and an order number should be displayed.

**Actual Result:**
The message “Your order has been successfully processed!” was displayed. Order number 34 was generated.

**Status:** PASS