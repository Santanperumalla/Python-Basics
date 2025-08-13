## 📜 Strings in Python

In Python, a **string** is a sequence of characters enclosed in single quotes (`'`), double quotes (`"`) or triple quotes (`'''` / `"""`).
Strings are **immutable**, meaning their contents cannot be changed after creation.

**Example:**

```python
# Creating strings
name = "Python"
greeting = 'Hello'
multiline = """This
is a
multiline string."""
```

---

## 🔧 Common String Methods

Python provides many built-in methods to work with strings:

| Method               | Description                         | Example                        | Output              |
| -------------------- | ----------------------------------- | ------------------------------ | ------------------- |
| `.upper()`           | Converts to uppercase               | `"hello".upper()`              | `"HELLO"`           |
| `.lower()`           | Converts to lowercase               | `"HELLO".lower()`              | `"hello"`           |
| `.title()`           | Capitalizes each word               | `"python tutorial".title()`    | `"Python Tutorial"` |
| `.strip()`           | Removes whitespace from start & end | `"  hello  ".strip()`          | `"hello"`           |
| `.replace(old, new)` | Replaces part of a string           | `"apple".replace("a", "o")`    | `"opple"`           |
| `.split()`           | Splits into a list                  | `"a,b,c".split(",")`           | `["a", "b", "c"]`   |
| `.join(iterable)`    | Joins iterable into string          | `" ".join(["Hello", "World"])` | `"Hello World"`     |
| `.find(sub)`         | Finds position of substring         | `"hello".find("e")`            | `1`                 |
| `.startswith(sub)`   | Checks if starts with substring     | `"Python".startswith("Py")`    | `True`              |
| `.endswith(sub)`     | Checks if ends with substring       | `"Python".endswith("on")`      | `True`              |

---

**Example Program:**

```python
text = "  Python Programming  "
print(text.strip().upper())  # Output: PYTHON PROGRAMMING
```
