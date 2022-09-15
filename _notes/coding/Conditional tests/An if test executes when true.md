---
title: An if test executes when true
---

`if` tests use [[bools are either true or false|bools]] or boolean values (`True` or `False`) to decide whether or not to execute. If the test of `x > y` is true, the compiler will register it as `True` and execute the code.

```python
x = 3
y = 4

if x < y:
	print("x is less than y")
```

`x is less than y`

If you want only one block of code to run, use an if-elif-else chain. If more than one block of code needs to run, use a series of independent if tests.