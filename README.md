
# FizzBuzz (C# Implementation)

## 📌 Problem Statement

Given a number `n`, for each integer `i` in the range from `1` to `n` inclusive, print one value per line as follows:

* If `i` is a multiple of both 3 and 5, print **FizzBuzz**.
* If `i` is a multiple of 3 (but not 5), print **Fizz**.
* If `i` is a multiple of 5 (but not 3), print **Buzz**.
* If `i` is not a multiple of 3 or 5, print the value of `i`.

---

## 📂 Function Description

Complete the function **fizzBuzz** below.

### Parameters

* `int n`: upper limit of values to test (inclusive).

### Returns

* **None**

### Prints

The function must print the appropriate response for each value `i` in the set `{1, 2, …, n}` in ascending order, each on a separate line.

---

## 📊 Constraints

* `0 < n < 2 × 10^5`

---

## 📝 Sample Case 0

### Input

```
15
```

### Output

```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

---

## 🔎 Explanation

* The numbers **3, 6, 9, and 12** are multiples of 3 (but not 5), so print **Fizz** on those lines.
* The numbers **5 and 10** are multiples of 5 (but not 3), so print **Buzz** on those lines.
* The number **15** is a multiple of both 3 and 5, so print **FizzBuzz** on that line.
* None of the other values are multiples of either 3 or 5, so print the value of `i` on those lines.

---

This is the **classic FizzBuzz challenge**, widely used in coding interviews to test basic programming concepts like loops, conditionals, and modular arithmetic.

---

👉 Do you also want me to include your **C# code** in the README (so that visitors don’t need to open files), or keep it just as a problem description?
