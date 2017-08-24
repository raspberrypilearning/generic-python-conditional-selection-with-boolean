- A standard `if` statement in Python checks for a single condition. For instance:

```python
x = 5
if x > 0:
	print('x is greater than zero')
```

- But sometimes you might want to check for more than one condition. In these instances you can use logical operators in your code.

- The `and` operator checks to see if both of two conditions have been met. For instance

```python
x = 5
if x > 0 and x < 10:
    print('x is between 0 and 10')
```

- So long as x is any number within the group - `1,2,3,4,5,6,7,8,9`, then the condition will be true.

- You can use the `or` operator to check if either of the conditions are true.

```python
x = 5
if x > 0 or x < 10:
	print('x exists')
```

- In this case, the condition will be true as long as `x` is greater than `0` or if it is less than `10`, so in other words as long as it is a number.
