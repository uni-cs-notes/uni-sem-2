
# 📚 Detailed Study on Calculus: Functions, Limits, Sequences & Series

## 🧮 Functions and Limits

### What are Functions?
In **mathematics**, a **function** is a relation that assigns exactly one output for each input. Functions help to describe how one quantity depends on another. The output depends on the input value you provide.

- **Notation**: A function is usually written as `f(x)`, where `x` is the input (also called the **independent variable**), and `f(x)` is the output (also called the **dependent variable**).
- **Example**: 
  - Let `f(x) = 3x + 2`.
    - When `x = 2`, `f(2) = 3(2) + 2 = 8`.
    - When `x = 4`, `f(4) = 3(4) + 2 = 14`.
  
### Types of Functions:
1. **Linear Function**: A function of the form `f(x) = mx + b`, where `m` is the slope and `b` is the y-intercept.
   - Example: `f(x) = 2x + 1`
2. **Quadratic Function**: A function of the form `f(x) = ax^2 + bx + c`, where `a`, `b`, and `c` are constants.
   - Example: `f(x) = x^2 + 3x + 2`
3. **Cubic Function**: A function of the form `f(x) = ax^3 + bx^2 + cx + d`
   - Example: `f(x) = x^3 + 2x^2 + x + 1`
4. **Trigonometric Function**: Functions like `sin(x)`, `cos(x)`, `tan(x)`
   - Example: `f(x) = sin(x)`
5. **Exponential Function**: A function of the form `f(x) = a * b^x` where `a` is the initial value and `b` is the base.
   - Example: `f(x) = 2^x`

---

### What is a Limit?
A **limit** is the value that a function approaches as the input approaches a certain value. In simpler terms, it helps to describe the behavior of a function as the input gets closer to a certain point.

- **Notation**: `lim(x→a) f(x)` represents the limit of the function `f(x)` as `x` approaches the value `a`.
- **Example**:
  - Consider the function `f(x) = (x^2 - 4)/(x - 2)`.
  - If we directly substitute `x = 2`, we get `0/0`, which is undefined. But using limits, we can evaluate the function as `x` approaches 2:
    - `lim(x→2) (x^2 - 4)/(x - 2) = 4`
  
### Formal Definition:
- The limit of a function `f(x)` as `x` approaches a value `a` is the value `L` that `f(x)` approaches as `x` gets closer to `a`:
  - `lim(x→a) f(x) = L`

### Types of Limits:
1. **Finite Limits**: When the function approaches a specific finite value.
2. **Infinite Limits**: When the function approaches infinity or negative infinity.
3. **One-sided Limits**: Limits evaluated from one direction (left or right).

---

## 🔢 Domain and Range

### What is Domain?
The **domain** of a function is the set of all possible **input** values (x-values) for which the function is defined. 

- **Example**: 
  - For `f(x) = √x`, the domain is `x ≥ 0`, because square roots of negative numbers aren't defined in the set of real numbers.
  
### What is Range?
The **range** of a function is the set of all possible **output** values (f(x)) that the function can produce based on its domain.

- **Example**:
  - For `f(x) = x^2`, the range is `f(x) ≥ 0`, because squaring any real number always gives a non-negative result.

### How to Find Domain and Range?

1. **For Functions with Square Roots**:
   - Ensure that the expression inside the square root is non-negative.
   - **Example**: For `f(x) = √(x - 2)`, domain: `x ≥ 2`.

2. **For Rational Functions**:
   - Set the denominator not equal to zero.
   - **Example**: For `f(x) = 1/(x - 3)`, domain: `x ≠ 3`.

3. **For Polynomial Functions**:
   - The domain of polynomial functions is usually all real numbers.
   - **Example**: For `f(x) = x^3 + 5x + 2`, domain: all real numbers.

---

## 🔢 Sequences and Series

### What is a Sequence?
A **sequence** is an ordered list of numbers. Each number in the sequence is called a **term**, and the position of the term is indicated by a subscript, such as `a_1`, `a_2`, etc.

- **Example**: 
  - `2, 4, 6, 8, 10,...` is a sequence.

### What is a Series?
A **series** is the sum of the terms in a sequence.

- **Example**: 
  - For the sequence `1, 2, 3, 4`, the corresponding series is `1 + 2 + 3 + 4 = 10`.

### Types of Sequences:
1. **Arithmetic Sequence**: A sequence in which the difference between consecutive terms is constant.
   - Example: `2, 4, 6, 8, 10`
2. **Geometric Sequence**: A sequence in which each term is found by multiplying the previous term by a constant.
   - Example: `1, 2, 4, 8, 16`

---

## 🔢 Arithmetic Progression (AP)

### What is an Arithmetic Progression?
An **Arithmetic Progression (AP)** is a sequence where the difference between consecutive terms is constant. This constant difference is called the **common difference** (denoted as `d`).

- **Formula**: `a_n = a_1 + (n - 1) * d`
  - Where `a_n` is the nth term, `a_1` is the first term, and `d` is the common difference.

### Example Arithmetic Sequences:
1. `3, 5, 7, 9, 11` with common difference `d = 2`
2. `10, 8, 6, 4, 2` with common difference `d = -2`
3. `1, 4, 7, 10, 13` with common difference `d = 3`
4. `-1, 0, 1, 2, 3` with common difference `d = 1`
5. `20, 15, 10, 5, 0` with common difference `d = -5`

### Arithmetic Series:
An **Arithmetic Series** is the sum of the terms of an arithmetic sequence.

- **Formula**: `S_n = n/2 * (2a_1 + (n - 1) * d)`
  - Where `S_n` is the sum of the first `n` terms, `a_1` is the first term, `d` is the common difference, and `n` is the number of terms.

- **Example**: Sum of the first 5 terms of the sequence `2, 4, 6, 8, 10`:
  - `S_5 = 5/2 * (2(2) + (5 - 1) * 2) = 5/2 * (4 + 8) = 5/2 * 12 = 30`

---

## 📊 Geometric Sequence (GS)

### What is a Geometric Sequence?
A **Geometric Sequence** is a sequence of numbers where each term is found by multiplying the previous term by a constant called the **common ratio** (`r`).

- **Formula**: `a_n = a_1 * r^(n - 1)`
  - Where `a_n` is the nth term, `a_1` is the first term, and `r` is the common ratio.

### Example Geometric Sequences:
1. `2, 4, 8, 16, 32` with common ratio `r = 2`
2. `3, 9, 27, 81, 243` with common ratio `r = 3`
3. `5, 10, 20, 40, 80` with common ratio `r = 2`
4. `1, -2, 4, -8, 16` with common ratio `r = -2`
5. `10, 5, 2.5, 1.25, 0.625` with common ratio `r = 0.5`

### Geometric Series:
A **Geometric Series** is the sum of the terms in a geometric sequence. The sum of the first `n` terms of a geometric series is given by:

- **Formula**: `S_n = a_1 * (1 - r^n) / (1 - r)` for `r ≠ 1`
  - Where `a_1` is the first term and `r` is the common ratio.

---

## 🚀 LECTURE No: 1/2 >> "Conclusion".

This detailed overview of **Calculus** covers essential concepts such as:

- **Functions**: Relations that assign outputs to inputs.
- **Limits**: Describing the behavior of a function as the input approaches a specific value.
- **Domain and Range**: Understanding the set of allowable inputs and outputs for a function.
- **Sequences** and **Series**: Ordered lists of numbers and their sums.
- **Arithmetic Progression (AP)**: A sequence with a constant difference between terms.
- **Geometric Sequence (GS)**: A sequence where each term is multiplied by a constant ratio.

Master these fundamental concepts by practicing different problems and applying these formulas. Happy studying and learning! ✨📚
