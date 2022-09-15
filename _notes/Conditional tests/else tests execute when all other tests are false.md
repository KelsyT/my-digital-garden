---
title: else tests execute when all other tests are false
---

`else` tests are a catchall statement. It matches any condition that wasn't matched by a specific [[if tests execute when true|if]] or [[elif tests execute when true in sequence|elif]] test, and that can sometimes include invalid or even malicious data. If you have a specific final condition you are testing for, consider using a final `elif` block and omit the `else` block. As a result, you'll gain extra confidence that your code will run only under the correct conditions.

```python
#amusement park
age = 12

if age < 4:
    price = 0
elif age < 18:
    price = 25
elif age < 65:
    price = 40
else:
    price = 20

print(f"Your admission cost is ${price}.")
```
