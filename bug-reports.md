This document contains simple bug reports during testing and self-studying


## BR-OO1
---
# Summary: 

# Description: 

# Steps to Reproduce:
1.
2.
3. 
4.
5.
6. 

# Expected Result:

# Actual Result:

# Severity:

# Priority:

# Environment:

# Attachment:

# Fix Version/s:

# Reporter:

---

## BUG-001: Second product card height differs from other product cards

**Type:** UI  
**Severity:** Minor  
**Priority:** Medium  
**Environment:** Windows 10 Pro / Chrome 140.0.7339.128  

### Steps to Reproduce
1. Open https://academybugs.com/find-bugs/  
2. Observe the second product card "Dark Grey Jeans"

### Expected Result
All product cards have the same size and alignment

### Actual Result
The second product card has a smaller height than the others

---

## BUG-002: Grand Total is calculated incorrectly in cart

**Type:** Functional  
**Severity:** Critical  
**Priority:** High  
**Environment:** Windows 10 Pro / Chrome 140.0.7339.128  

### Steps to Reproduce
1. Open https://academybugs.com/find-bugs/  
2. Add any product to cart  
3. Click "Update" under the Quantity field  
4. Check the "Grand Total"

### Expected Result
Grand Total should equal Cart Subtotal plus Shipping

### Actual Result
Grand Total is calculated incorrectly

### Screenshot

![Grand Total Bug](./images/bug-002-total.png)

### Notes
This issue affects the final order amount
