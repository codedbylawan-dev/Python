# 🐍 **Day 8 — Type Conversions & String Slicing | Cheat Sheet**

---

## 🎯 **Focus**

To understand how to **slice strings** and **convert data types** in Python, enabling flexible data manipulation and arithmetic operations.

---

## 🧠 **Goal**

Learn to:

- Extract parts of a string using **slicing**
- Check the **data type** of a value or variable
- Perform **type conversion (casting)** between string, integer, float, and boolean
- Safely handle user input for **arithmetic operations**

---

## 📝 **Topics Covered**

---

### 1️⃣ **String Slicing**

Obtaining a part of a string is called **string slicing**.

**Syntax:**

```python
variable_name[start_index:end_index]
```

- **start_index** → starting position (inclusive)
- **end_index** → stopping position (exclusive)

**Example:**

```python
message = "Hi Ravi"
part = message[3:7]
print(part)
```

**Output:**

```
Ravi
```

---

#### **Slicing to the End**

If **end index is omitted**, slicing goes to the **end of the string**:

```python
message = "Hi Ravi"
part = message[3:]
print(part)
```

**Output:**

```
Ravi
```

---

#### **Slicing from the Start**

If **start index is omitted**, slicing starts from index `0`:

```python
message = "Hi Ravi"
part = message[:2]
print(part)
```

**Output:**

```
Hi
```

---

### 2️⃣ **Checking Data Type**

Use `type()` to check the **data type** of a value or variable.

```python
print(type(10))
print(type(4.2))
print(type("Hi"))
```

**Output:**

```
<class 'int'>
<class 'float'>
<class 'str'>
```

---

### 3️⃣ **Type Conversion (Casting)**

**Type Conversion** is changing a value from **one data type to another**.

Common conversions:

- String → Integer
- Integer → Float
- Float → String
- Any type → Boolean

---

#### **String to Integer**

```python
a = "5"
a = int(a)
print(type(a))
print(a)
```

**Output:**

```
<class 'int'>
5
```

⚠️ Invalid conversion examples:

```python
a = "Five"
a = int(a)
```

**Output:**

```
ValueError: invalid literal for int() with base 10: 'Five'
```

```python
a = "5.0"
a = int(a)
```

**Output:**

```
ValueError: invalid literal for int() with base 10: '5.0'
```

---

#### **Adding Two Numbers (with Input)**

```python
a = int(input())
b = int(input())
result = a + b
print(result)
```

**Input:**

```
2
3
```

**Output:**

```
5
```

---

#### **Integer to String**

```python
a = int(input())
b = int(input())
result = a + b
print("Sum: " + str(result))
```

**Input:**

```
2
3
```

**Output:**

```
Sum: 5
```

---

### 4️⃣ **Summary of Conversion Functions**

| Function  | Converts To |
| --------- | ----------- |
| `int()`   | Integer     |
| `float()` | Float       |
| `str()`   | String      |
| `bool()`  | Boolean     |

> ✅ **Tip:** Always convert **input()** values before performing arithmetic because `input()` returns **string by default**.

---
