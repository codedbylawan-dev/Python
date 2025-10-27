# 🐍 **Day 4: Sequence of Instructions | Cheat Sheet**

---

## **Program**

A **program** is a **sequence of instructions** given to a computer to perform specific tasks.

---

## **Defining a Variable**

A variable is **created automatically** when you **assign a value** to it for the first time.

**Example:**

```python
age = 10
```

---

## **Printing Value in a Variable**

**Example 1:**

```python
age = 10
print(age)
```

**Output:**

```
10
```

**Example 2:**

```python
age = 10
print("age")
```

**Output:**

```
age
```

📝 **Note:**

- When a variable name is **inside quotes**, Python prints it **as text**.
- When **not inside quotes**, Python prints the **value stored** in that variable.

---

## **Order of Instructions**

Python executes the program **line by line (top to bottom)**.

**Example:**

```python
print(age)
age = 10
```

**Output:**

```
NameError: name 'age' is not defined
```

👉 The variable `age` was **used before being defined**, so Python throws an error.

---

## **Spacing in Python (Indentation)**

Python uses **indentation (spaces)** to define structure.
Having **extra spaces at the beginning** of a line can cause **errors**.

**Example:**

```python
a = 10 * 5
b = 5 * 0.5
 b = a + b
```

**Output:**

```
IndentationError: unexpected indent
```

🧠 **Tip:** Always start code from the **left margin** unless writing inside a block (like loops or functions).

---

## **Variable Assignment**

Values in variables can **change** at any time.

**Example:**

```python
a = 1
print(a)
a = 2
print(a)
```

**Output:**

```
1
2
```

---

### **More Examples**

**Example 1:**

```python
a = 2
print(a)
a = a + 1
print(a)
```

**Output:**

```
2
3
```

**Example 2:**

```python
a = 1
b = 2
a = b + 1
print(a)
print(b)
```

**Output:**

```
3
2
```

---

## **Expression**

An **expression** is a valid combination of **values, variables, and operators** that produces a result.

**Examples:**

```
a * b
a + 2
5 * 2 + 3 * 4
```

---

## **BODMAS Rule**

Python follows the **BODMAS** order for evaluating expressions:

| Symbol | Meaning         |
| :----: | :-------------- |
| **B**  | Brackets        |
| **O**  | Orders (powers) |
| **D**  | Division        |
| **M**  | Multiplication  |
| **A**  | Addition        |
| **S**  | Subtraction     |

---

### **Example:**

Expression:

```
5 * 2 + 3 * 4
```

Step-by-step:

```
(5 * 2) + (3 * 4)
10 + 12
22
```

---

### **Code Example:**

```python
print(10 / 2 + 3)
print(10 / (2 + 3))
```

**Output:**

```
8.0
2.0
```

---

### ✅ **Key Takeaways**

- Code runs **line by line**.
- **Indentation** (spacing) matters.
- Variables can be **reassigned** anytime.
- Expressions follow **BODMAS** order.

---

Would you like me to add a **Practice Section** after each cheat sheet (with 3–5 mini problems to try daily)?
