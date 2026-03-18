# Bug Reports — E-commerce

## Bug 01 — Product is added twice after double click
**Steps to Reproduce:**
1. Open the product listing page
2. Select a product
3. Double click on "Add to Cart"

**Expected Result:**
The product should be added only once.

**Actual Result:**
The product is added twice to the cart.

**Severity:** Medium  
**Priority:** High

---

## Bug 02 — Cart total is not updated after removing product
**Steps to Reproduce:**
1. Add two products to the cart
2. Open the cart
3. Remove one product

**Expected Result:**
The cart total should update correctly.

**Actual Result:**
The removed product disappears, but the total price remains the same.

**Severity:** High  
**Priority:** High

---

## Bug 03 — Checkout allows empty required fields
**Steps to Reproduce:**
1. Add a product to the cart
2. Proceed to checkout
3. Leave required fields empty
4. Confirm purchase

**Expected Result:**
The system should block checkout and display validation messages.

**Actual Result:**
The checkout continues without validating required fields.

**Severity:** High  
**Priority:** High

---

## Bug 04 — Quantity update does not refresh total price
**Steps to Reproduce:**
1. Add a product to the cart
2. Open the cart
3. Increase the quantity

**Expected Result:**
The total price should update based on the new quantity.

**Actual Result:**
The quantity changes, but the total price remains unchanged.

**Severity:** Medium  
**Priority:** Medium
