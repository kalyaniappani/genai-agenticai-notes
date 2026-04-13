# 🐍 Python Complete Notes (Beginner → Advanced)

---

## 📌 Table of Contents

* [Introduction](#introduction)
* [Why Python?](#why-python)
* [Python History](#python-history)
* [Applications](#applications)

### 🔢 Basics

* [Numbers](#numbers)
* [Strings](#strings)
* [Escape Sequences](#escape-sequences)

### 🧪 Data Types

* [Data Types Overview](#data-types-overview)
* [Type Casting](#type-casting)

### 🧠 Variables

* [Variables](#variables)
* [Rules](#rules)

### 🖨 Print Function

* [Basic Print](#basic-print)
* [Formatted Print](#formatted-print)
* [f-Strings](#f-strings)
* [end & sep](#end--sep)

### 🔤 Strings Deep Dive

* [Indexing](#indexing)
* [Slicing](#slicing)
* [Immutability](#immutability)
* [String Methods](#string-methods)

### 📦 Lists

* [Basics](#list-basics)
* [Operations](#list-operations)
* [Nested Lists](#nested-lists)

### 🔁 Control Flow

* [While Loop](#while-loop)
* [Fibonacci](#fibonacci)

### ⚠️ Errors

* [Common Errors](#common-errors)

### 💡 Interview Questions

* [Top Questions](#top-questions)

### 🤖 AI Context

* [Python in AI](#python-in-ai)

---

## 📖 Introduction

Python is a **high-level, interpreted programming language**.

* Easy to learn
* Powerful
* Beginner friendly

---

## 🚀 Why Python?

* Simple syntax
* Less code
* Platform independent
* Huge ecosystem

---

## 🕰 Python History

* Created in 1989
* Released in 1991
* Named after *Monty Python*

---

## 🌍 Applications

* AI / ML
* Web Development
* Automation
* Data Science

---

# 🔢 Numbers

```python
print(2+3)
print(2**3)
print(2//3)
print(2%3)
```

---

# 🔤 Strings

```python
"hello"
'hello'
'''hello'''
```

---

# 🔡 Escape Sequences

```python
print("Hello\nWorld")
print("Hello\tWorld")
print("\\")
```

---

# 🧪 Data Types Overview

```python
int
float
complex
str
list
tuple
set
dict
bool
```

---

# 🔄 Type Casting

```python
int("10")
float(5)
```

---

# 🧠 Variables

```python
x = 10
name = "kalyani"
```

* Dynamic typing
* No declaration needed

---

# 📏 Rules

* Start with letter/_
* No numbers at start
* No keywords

---

# 🖨 Basic Print

```python
print(10,20)
```

---

# 🧾 Formatted Print

```python
print("sum is", a+b)
```

---

# 🎯 f-Strings

```python
print(f"sum is {a+b}")
```

---

# 🔚 end & sep

```python
print("hello", end=" ")
print("world")

print("a","b","c", sep="-")
```

---

# 🔢 Indexing

```python
name = "python"
print(name[0])
print(name[-1])
```

---

# ✂️ Slicing

```python
name[1:4]
name[:3]
name[2:]
```

---

# ❌ Immutability

```python
# strings cannot change
```

---

# 🔤 String Methods

```python
text.upper()
text.lower()
text.strip()
text.split()
text.replace("a","b")
```

---

# 📦 List Basics

```python
numbers = [1,2,3]
```

---

# 🔄 List Operations

```python
numbers.append(4)
numbers[0] = 10
```

---

# 🧩 Nested Lists

```python
x = [["a"],[1]]
```

---

# 🔁 While Loop

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

---

# 🔢 Fibonacci

```python
a,b = 0,1
while a < 10:
    print(a)
    a,b = b,a+b
```

---

# ⚠️ Common Errors

```python
NameError
SyntaxError
ZeroDivisionError
IndexError
```

---

# 💡 Top Questions

| Question       | Answer       |
| -------------- | ------------ |
| int(True)      | 1            |
| "7.1" type     | str          |
| Dynamic typing | Type changes |

---

# 🤖 Python in AI

* ML
* AI
* GenAI
* Agentic AI

---
