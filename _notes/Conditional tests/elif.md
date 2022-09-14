When more than two possible situations need to be tested, use an `elif`. In an `if-elif-else` chain, only one block of code is executed. It runs each [[Conditional tests make decisions|conditional test]] in order until one is true. When it is true, the code following that test is executed and Python skips the rest of the tests.

```python
age = 12

if age < 4:
    price = 0

elif age < 18:
    price = 25

elif age < 65:
    price = 40

elif age >= 65:
    price = 20

print(f"Your admission cost is ${price}.")
```
