# Exercise 5: Check if the first and last number of a list is the same

Write a function to return True if the first and last number of a given list is same. If numbers are different then return False.

**Given:**

><b>numbers_x = [10, 20, 30, 40, 10]</b>  
><b>numbers_y = [75, 65, 35, 75, 30]</b>

**Expected Output:**
```
Given list: [10, 20, 30, 40, 10]
result is True

numbers_y = [75, 65, 35, 75, 30]
result is False
```

***Sol:-***

```python
def mylistfunction(mylist):

    if mylist[0] == mylist[-1]:
        return True
    else:
        return False
    
print("Given list:",[10, 20, 30, 40, 10],"\nresult is",mylistfunction([10, 20, 30, 40, 10]))
print("\nGiven list:",[75, 65, 35, 75, 30],"\nresult is",mylistfunction([75, 65, 35, 75, 30]))
```
