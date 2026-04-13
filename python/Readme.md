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

<a id="introduction"></a>

## 📖 Introduction

Python is a **high-level, interpreted programming language**.

* Easy to learn
* Powerful
* Beginner friendly

---

<a id="why-python"></a>

## 🚀 Why Python?

* Simple syntax
* Less code
* Platform independent
* Huge ecosystem

---

<a id="python-history"></a>

## 🕰 Python History

* Created in 1989
* Released in 1991
* Named after *Monty Python*

---

<a id="applications"></a>

## 🌍 Applications

* AI / ML
* Web Development
* Automation
* Data Science

---

<a id="numbers"></a>

# 🔢 Numbers

```python
print(2+3)
print(2**3)
print(2//3)
print(2%3)
```

---

<a id="strings"></a>

# 🔤 Strings

```python
"hello"
'hello'
'''hello'''
```

---

<a id="escape-sequences"></a>

# 🔡 Escape Sequences

```python
print("Hello\nWorld")
print("Hello\tWorld")
print("\\")
```

---

<a id="data-types-overview"></a>

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

<a id="type-casting"></a>

# 🔄 Type Casting

```python
int("10")
float(5)
```

---

<a id="variables"></a>

# 🧠 Variables

```python
x = 10
name = "kalyani"
```

* Dynamic typing
* No declaration needed

---

<a id="rules"></a>

# 📏 Rules

* Start with letter/_
* No numbers at start
* No keywords

---

<a id="basic-print"></a>

# 🖨 Basic Print

```python
print(10,20)
```

---

<a id="formatted-print"></a>

# 🧾 Formatted Print

```python
print("sum is", a+b)
```

---

<a id="f-strings"></a>

# 🎯 f-Strings

```python
print(f"sum is {a+b}")
```

---

<a id="end--sep"></a>

# 🔚 end & sep

```python
print("hello", end=" ")
print("world")

print("a","b","c", sep="-")
```

---

<a id="indexing"></a>

# 🔢 Indexing

```python
name = "python"
print(name[0])
print(name[-1])
```

---

<a id="slicing"></a>

# ✂️ Slicing

```python
name[1:4]
name[:3]
name[2:]
```

---

<a id="immutability"></a>

# ❌ Immutability

```python
# strings cannot change
```

---

<a id="string-methods"></a>

# 🔤 String Methods

```python
text.upper()
text.lower()
text.strip()
text.split()
text.replace("a","b")
```

---

<a id="list-basics"></a>

# 📦 List Basics

```python
numbers = [1,2,3]
```

---

<a id="list-operations"></a>

# 🔄 List Operations

```python
numbers.append(4)
numbers[0] = 10
```

---

<a id="nested-lists"></a>

# 🧩 Nested Lists

```python
x = [["a"],[1]]
```

---

<a id="while-loop"></a>

# 🔁 While Loop

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

---

<a id="fibonacci"></a>

# 🔢 Fibonacci

```python
a,b = 0,1
while a < 10:
    print(a)
    a,b = b,a+b
```

---

<a id="common-errors"></a>

# ⚠️ Common Errors

```python
NameError
SyntaxError
ZeroDivisionError
IndexError
```

---

<a id="top-questions"></a>

# 💡 Top Questions

| Question       | Answer       |
| -------------- | ------------ |
| int(True)      | 1            |
| "7.1" type     | str          |
| Dynamic typing | Type changes |

---

<a id="python-in-ai"></a>

# 🤖 Python in AI

* ML
* AI
* GenAI
* Agentic AI

---
