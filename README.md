# 🔢 Reverse Integer in C

A clean and efficient C implementation of the **Reverse Integer** problem from LeetCode.

## 📌 Problem Statement

Given a signed 32-bit integer `x`, return `x` with its digits reversed.

If reversing `x` causes the value to go outside the signed 32-bit integer range  
`[-2^31, 2^31 - 1]`, then return `0`.

⚠️ The solution must not use 64-bit integers.

---

## 🧠 Examples

| Input  | Output |
|--------|--------|
| 123    | 321    |
| -123   | -321   |
| 120    | 21     |

---

## 🚀 Approach

- Extract digits using modulo (`% 10`)
- Remove last digit using division (`/ 10`)
- Build reversed number step-by-step
- Check for overflow before multiplying by 10
- Return `0` if overflow occurs

---

## ⏱ Time Complexity

```
O(log₁₀ n)
```
(Number of digits in the integer)

## 📦 Space Complexity

```
O(1)
```
(Constant extra space)

---

## 🎯 Key Concepts Used

- Integer arithmetic
- Modulo & division operations
- Overflow detection
- 32-bit signed integer limits
- Defensive programming



