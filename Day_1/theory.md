# Day 1: Write Your FIRST Python Program

## What You Will Learn
- Create and run a Python file
- Use the `print()` function
- Understand strings
- Write comments with `#`
- Read and fix your first errors

## 1. Create the file
Open your code editor and save a new file as `hello.py`. The `.py` extension tells your computer this is a Python file.

## 2. Your first program
```python
# Your first program
print("Hello, World!")
```
Output:
```
Hello, World!
```

## 3. What is `print()`?
`print()` is a **function**. It shows whatever is inside the brackets on the screen.

## 4. Strings
Text inside quotes is a **string**. Use double or single quotes, but they must match.
```python
print("Hello")
print('Hello')
```

## 5. Numbers and maths
Numbers do not need quotes. Quotes turn anything into plain text.
```python
print(2 + 3)      # 5
print("2 + 3")    # 2 + 3
```

## 6. Printing multiple items
```python
print("Hello", "World")                 # Hello World
print("Python", "is", "fun", sep="-")   # Python-is-fun
```

## 7. Comments
Python ignores everything after `#`.
```python
# This line is ignored
print("This line runs")
```

## 8. Python is case-sensitive
`print` works. `Print` and `PRINT` do not.

## Cheat Sheet

| Task | Code |
|---|---|
| Show text | `print("text")` |
| Show a number | `print(10)` |
| Do maths | `print(5 * 4)` |
| Add a comment | `# my note` |
| New line inside text | `print("Line1\nLine2")` |
| Change separator | `print("a", "b", sep="-")` |
| Run a file | `python hello.py` |

## Common Errors

| Error | Usually means | Fix |
|---|---|---|
| `SyntaxError: unterminated string literal` | Missing or mismatched quote | Check opening and closing quotes |
| `SyntaxError: '(' was never closed` | Missing bracket | Add `)` |
| `NameError: name 'Print' is not defined` | Wrong spelling or capital letter | Use lowercase `print` |

Tip: read the error from the bottom up. The last line says what went wrong, and the line number says where.

## Next: Day 2, Variables & Data Types
