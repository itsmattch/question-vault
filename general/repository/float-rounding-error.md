## What does it mean to say that floating point numbers have "rounding errors"?

### 🎯 Key Concepts

- Rounding errors
- Floating point precision
- Limitations of digital representation

### 👑 Flawless Answer

Rounding errors in the context of floating point numbers refer to the
inaccuracies that occur when a value cannot be exactly represented due to the
finite precision of the floating point format. These errors occur because the
number of possible floating point numbers is finite, but the number of real
numbers within a given range is infinite. As such, many real numbers can only be
approximately represented as floating point numbers. The degree of inaccuracy -
the rounding error - depends on the specific value and the precision of the
floating point format.

For example, the decimal number 0.1 cannot be exactly represented as a binary
floating point number. Instead, it is represented by a nearby value that is
slightly more than 0.1. When this is added to another number, or used in other
calculations, the small error becomes part of the result.

### 🌿 Acceptable Answer

Rounding errors are small mistakes that happen when a computer can't exactly
represent a number. For example, the decimal number 0.1 can't be exactly
represented as a binary floating point number, so the computer uses a value
that's very close, but not exactly the same. When we use this number in
calculations, this small error can become part of the result.

### 💎 Extra Points

- Understanding how finite precision leads to rounding errors.
- Examples of real-world impact of rounding errors.
- Knowledge of how to mitigate rounding errors.

### 🤓 Explanation

Computers store numbers in binary format, but some numbers can't be perfectly
translated from decimal to binary, kind of like how one-third (1/3) can't be
perfectly represented with a finite number of digits in decimal form (0.333...).
This results in very small mistakes, or rounding errors, when we do calculations
with these numbers.

### 💡 Evaluation Tips

- Candidates should be able to explain what rounding errors are and why they
  occur in the context of floating point numbers.
- A candidate with deep understanding may provide real-world examples of how
  rounding errors can cause issues, and possibly how to avoid them.

### ✨ Insights

- While it may seem like a small detail, understanding rounding errors is
  crucial for any role involving numerical calculations, as these errors can
  lead to significant inaccuracies in certain contexts.
- This question gives an opportunity to assess the candidate's depth of
  knowledge on fundamental computing concepts and their attention to detail.

### 📚 Resources

- [What Every Programmer Should Know About Floating-Point Arithmetic](https://floating-point-gui.de/)
- [What Every Computer Scientist Should Know About Floating-Point Arithmetic](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)