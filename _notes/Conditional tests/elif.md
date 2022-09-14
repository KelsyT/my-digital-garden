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

In the code above, there is no [[else statements execute when all other tests are false|else]] statement. This means that every block of code must pass a specific test in order to be executed. 

