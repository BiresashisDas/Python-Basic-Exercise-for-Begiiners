# Exercise 7: Return the count of a given substring from a string

Q. Write a program to find how many times substring “Emma” appears in the given string.

**Given:**

> **str_x = "Emma is good developer. Emma is a writer"**

**Expected Output:**

> **Emma appeared 2 times**

***Sol:-***

```python
n = input("Enter a sentence : ")
search = input("Enter the substring : ")
if search in n:
    print(f"{search} appeared {n.count(search)} times.")
else:
    print("Given substring isn't present on the sentence. Try again!")
```
