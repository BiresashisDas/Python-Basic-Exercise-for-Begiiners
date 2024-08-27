# Exercise 3: Print characters from a string that are present at an even index number

Q. Write a program to accept a string from the user and display characters that are present at an even index number.

For example, <code>str = "pynative"</code> so you should display ‘p’, ‘n’, ‘t’, ‘v’.

***Sol:-***

```python
s = input("Enter your string : ")
print(f"Original String is {s}")
print("Printing only even index chars")
s = s[::2]
for i in s:
    print(i)
```
