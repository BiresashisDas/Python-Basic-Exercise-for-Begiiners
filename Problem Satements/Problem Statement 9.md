# Exercise 9: Check Palindrome Number

Q. Write a program to check if the given number is a palindrome number.

A palindrome number is a number that is the same after reverse. For example, 545, is the palindrome numbers

**Expected Output:**

> **original number 121  
> Yes. given number is palindrome number**
> 
> **original number 125  
> No. given number is not palindrome number**

***Sol:-***

**1) Using the <code>input()</code> function**
```python
n = int(input("Original number "))
n = str(n)
if n == n[::-1]:
    print("Yes. given number is palindrome number")
else:
    print("No. given number is not palindrome number")
```

**2) By defining a <code>function</code>**
```python
def number(num):
    print("original number ",num)
    num = str(num)
    if num == num[::-1]:
        print("Yes. given number is palindrome number")
    else:
        print("No. given number is not palindrome number")
    print()
number(121)
number(125)
```
