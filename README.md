# Day-37-Area-of-Triangle

Day 37/100 - Python Program to Find Area of Triangle

# Find Area of a Triangle

A program to calculate and display the mathematical area of a two-dimensional triangle based on user-provided base and height dimensions.

## 📝 Description

This program prompts the user to input the length of a triangle's base and its corresponding height. It then calculates the total area using the standard geometric formula: $Area = \frac{1}{2} \times base \times height$.

Unlike previous integer-only scripts, this program intentionally casts the user inputs into floating-point numbers (`float()`). This allows for precise measurements using decimals. Additionally, when printing the final calculated area, it utilizes Python's f-string formatting capabilities (`:.2f`) to neatly round and display the result to exactly two decimal places, providing a clean, professional output.

---

## 🎯 Problem Statement

### Input:

* **Input 1:** A floating-point number representing the `base` of the triangle.
* **Input 2:** A floating-point number representing the `height` of the triangle.

### Output:

* A formatted string stating: "The area of the triangle is: [area]" where `[area]` is rounded to two decimal places.

### Rules:

1. The program must accept two inputs from the user (`base` and `height`).
2. Both inputs must be converted to `float` data types to handle decimal values.
3. The program must calculate the area using the formula `0.5 * base * height`.
4. The final output must be formatted to display exactly two decimal places using the `:.2f` format specifier.

---

## 💡 Examples

### Example 1 (Standard Integers)

**Input:**

```
10
5


```

**Output:**

```
The area of the triangle is: 25.00


```

**Explanation:** $0.5 \times 10.0 \times 5.0 = 25.0$. The `:.2f` formatting ensures it displays as `25.00`.

### Example 2 (Decimal Inputs)

**Input:**

```
7.5
3.2


```

**Output:**

```
The area of the triangle is: 12.00


```

**Explanation:** $0.5 \times 7.5 \times 3.2 = 12.0$. It processes the floating-point math accurately and formats the trailing zeros.

### Example 3 (Fractions resulting in long decimals)

**Input:**

```
10
3.33


```

**Output:**

```
The area of the triangle is: 16.65


```

**Explanation:** $0.5 \times 10.0 \times 3.33 = 16.65$. The calculation requires no rounding in this specific case, but perfectly slots into the two-decimal format.

### Example 4 (Zero Dimension)

**Input:**

```
0
15


```

**Output:**

```
The area of the triangle is: 0.00


```

**Explanation:** A triangle with a base of 0 mathematically has an area of 0. $0.5 \times 0.0 \times 15.0 = 0.0$.

---

## 🚀 How to Use

1. **Clone this repository** (or save the script)

```bash
git clone https://github.com/adiaryaz/Day-37-Area-of-Triangle.git
cd area-of-triangle


```

2. **Run the program**:

```bash
python main.py


```

Enter the base and height values (whole numbers or decimals) when prompted to calculate the precise area.
