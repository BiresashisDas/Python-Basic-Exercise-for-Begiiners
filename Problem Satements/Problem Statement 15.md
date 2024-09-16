# Q. Use a List Comprehension to create a list of all numbers between 1 and 50 that are divisible by 3.

***Sol:-***

```python
l = []

for i in range(1,51):
    if i % 3 == 0:
        l.append(i)
print(l)
```

**OUTPUT**
```

[3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48]

```
