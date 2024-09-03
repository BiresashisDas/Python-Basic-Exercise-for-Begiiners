# Exercise 11: Get each digit from a number in the reverse order.

Q. For example, If the given integer number is 7536, the output shall be “6 3 5 7“, with a space separating the digits.

***Sol:-***

```python
num = 5678
n = str(num)
print(" ".join(n[::-1]))
```

**Another Way**
```python
n = int(input("Enter your number : "))
n = str(n)
n = n[::-1]
for i in n:
    print(i, end = " ")
```
