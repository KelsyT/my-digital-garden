---
title: Tuples are immutable lists
---

Tuples are immutable (or unchanging) lists for storing items. Tuples look like lists, except with parentheses instead of square brackets.

```
dimensions = (200, 50)
print(dimensions [0])
print(dimensions [1])
```

```
200
50
```

Python will return an [[TypeError]] if a Tuple is altered by assigning a new value to an item.

```
dimensions = (200, 50)
dimensions [0] = 250
```

```
Traceback (most recent call last):
	File "dimensions.py", line 2, in <module>
		dimensions[0] = 250
TypeError: 'tuple' object does not support item assignment
```

A tuple is defined by the **comma**. A trailing comma is used for a single element:

~~~
my_t = (3,)
~~~

Tuples with one element can be often found when generated automatically.


### Looping through all values in a tuple

To loop through a tuple, treat it as a list.

```
dimensions = (200, 50)
for dimension in dimensions:
	print(dimension)
```

~~~
200
50
~~~

### Writing over a tuple

Tuples can be overwritten by assigning a new value to a variable that represents the tuple.

```

```