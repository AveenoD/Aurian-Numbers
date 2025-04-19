# Aurian Numbers

**A Novel Digit-Based Numerical Identity**

---

### 📖 Overview

**Aurian Numbers** are a unique class of positive integers defined by a special relationship between the subtraction of their digits (from right to left) and the difference between the sum and the product of their digits.

This repository contains:
- A formal definition  
- C implementation to check Aurian Numbers  
- Examples and test cases  
- Links to the published paper on Figshare  

---

### 🔢 Definition

Let `N` be a k‑digit number with digits `d₁ d₂ … dₖ` (`d₁` = leftmost, `dₖ` = rightmost).

1. **Subtractive Reduction**  
S = dₖ – dₖ₋₁ – … – d₁

3. **Digit Sum & Product**
4. Sum = d₁ + d₂ + … + dₖ
Product = d₁ × d₂ × … × dₖ

3. **Aurian Condition**
   S == (Sum - Product)
Example:
Enter a number: 1124
1124 is an Aurian Number
