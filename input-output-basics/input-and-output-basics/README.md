# 🐍 **Day 6 — Input and Output Basics | Cheat Sheet**

---

## 🎯 **Focus**

To understand how to handle **string operations**, **take input from users**, and **display output** in Python.

---

## 🧠 **Goal**

Learn how to:

- Concatenate and repeat strings
- Take input from the user
- Find string length
- Access characters using indexing

---

## 📝 **Topics Covered**

---

### 1️⃣ **String Concatenation**

Joining strings together is called **string concatenation**.

```python
a = "Hello" + " " + "World"
print(a)
```

**Output:**

```
Hello World
```

---

#### ⚠️ Concatenation Errors

String concatenation is **only possible between strings**.

```python
a = "*" + 10
print(a)
```

**Output:**

```
TypeError: can only concatenate str (not "int") to str
```

✅ To fix this:

```python
a = "*" + str(10)
print(a)
```

**Output:**

```
*10
```

---

### 2️⃣ **String Repetition**

The `*` operator is used to **repeat strings** any number of times.

```python
a = "*" * 10
print(a)
```

**Output:**

```
**********
```

**Example 2:**

```python
s = "Python"
s = ("* " * 3) + s + (" *" * 3)
print(s)
```

**Output:**

```
* * * Python * * *
```

---

### 3️⃣ **Length of a String**

`len()` returns the **number of characters** in a string.

```python
username = input()
length = len(username)
print(length)
```

**Input:**

```
Ravi
```

**Output:**

```
4
```

---

### 4️⃣ **Taking Input from the User**

`input()` is used to **take user input**.
It always returns data as a **string**.

#### 🧩 Example 1:

```python
username = input()
print(username)
```

**Input:**

```
Ajay
```

**Output:**

```
Ajay
```

#### 🧩 Example 2:

```python
username = input()
age = input()
print(username + " is " + age + " years old")
```

**Input:**

```
Ravi
10
```

**Output:**

```
Ravi is 10 years old
```

> **Note:**
> Even though you can’t directly combine strings and integers, this works because `input()` **returns a string**.
> Example: `"10"` is treated as a string, not an integer.

---

### 5️⃣ **String Indexing**

We can access **individual characters** in a string using **index positions** (starting from 0).

```python
username = "Ravi"
first_letter = username[0]
print(first_letter)
```

**Output:**

```
R
```

---

#### ⚠️ IndexError

If you use an index larger than the string length, you’ll get an error.

```python
username = "Ravi"
print(username[4])
```

**Output:**

```
IndexError: string index out of range
```

---

## 📚 **Learned Concepts**

- `+` → Concatenates strings
- `*` → Repeats strings
- `len()` → Finds string length
- `input()` → Takes user input (as string)
- String indexing starts at `0`
- Accessing invalid index → `IndexError`

---
