---
title: Conditional tests make decisions
---

Expressions that are evaluated to determine whether an[[An if test executes when true| if test]] is `True` or `False` are known as *conditional tests*. These examine an exact set of conditions and decide which action to take using [[bools are either true or false|boolean values]]. A set of symbols called [[Operators compare values|operators]] can be used for comparison, such as `==` for "equal to".

```python
>>> car = 'bmw'
>>> car == 'bmw'
True
```

If you want only one block of code to run, use an if-elif-else chain. If more than one block of code needs to run, use a series of independent if tests.