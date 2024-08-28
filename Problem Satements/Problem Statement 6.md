# Exercise 6: Display numbers divisible by 5 from a list

Q. Iterate the given list of numbers and print only those numbers which are divisible by 5

**Expected Output:**
```
Given list is  [10, 20, 33, 46, 55]
Divisible by 5
10
20
55
```

***Sol:-***

```python
mylist = [10, 20, 33, 46, 55]
print("Given list is ",mylist)

for num in mylist:
    if num % 5 == 0:
        print(num)
```
