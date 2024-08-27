# Exercise 4: Remove first <code>n</code> characters from a string

Q. Write a program to remove characters from a string starting from zero up to <code>n</code> and return a new string.

For example:

- <code>remove_chars("pynative", 4)</code> so output must be <code>tive</code>. Here, we need to remove the first four characters from a string.  

- <code>remove_chars("pynative", 2)</code> so output must be <code>native</code>. Here, we need to remove the first two characters from a string.

**Note**: <code>n</code> must be less than the length of the string.

***Sol:-***

```python
s = input("Enter the String : ")
n = int(input("Enter the number of characters to remove from the string : "))

if n < len(s):
    res = s[n:]
    print(res)
else:
    print("Retry! Number should be less than string!")
```
