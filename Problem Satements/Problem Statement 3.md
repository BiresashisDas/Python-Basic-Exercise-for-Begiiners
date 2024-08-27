# Exercise 3: Print characters from a string that are present at an even index number

Q. Write a program to accept a string from the user and display characters that are present at an even index number.

For example, <code>str = "pynative"</code> so you should display ‘p’, ‘n’, ‘t’, ‘v’.

**Expected Output:**
```
Orginal String is  pynative  
Printing only even index chars  
p  
n  
t  
v  
```
***Sol:-***

```python
s = input("Original String is ")
print("Printing only even index chars")
s = s[::2]
for i in s:
    print(i)
```
