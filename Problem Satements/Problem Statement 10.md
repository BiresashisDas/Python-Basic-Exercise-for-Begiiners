# Exercise 10: Merge two lists using the following condition

Q. Given two lists of numbers, write a Python code to create a new list such that the latest list should contain **odd numbers from the first list and even numbers from the second list.**

**Given:**

list1 = [10, 20, 25, 30, 35]  
list2 = [40, 45, 60, 75, 90]  

**Expected Output:**  

result list: [25, 35, 40, 60, 90]


***Sol:-***

```python
l = []
def mylist1(new_list1):
    for i in new_list1:
        if i % 2 == 1:
            l.append(i)
            
def mylist2(new_list2):
    for i in new_list2:
        if i % 2 == 0:
            l.append(i)
    print("result list :", l)            

mylist1([10, 20, 25, 30, 35])
mylist2([40, 45, 60, 75, 90])
```
> [!WARNING]
> Kindly ignore writing code in the above fashion as per **DRY Rule**.

> [!IMPORTANT]
> - Remeber DRY Rule of programming language  
> - It means **Don't Repeat Yourself**. Instead of wriing same line of code everytime we will follow the below method

```python
def mylist(new_list1, new_list2):
    l = []
    
    for i in new_list1:
        if i % 2 == 1:
            l.append(i)
        
    for j in new_list2:
        if j % 2 == 0:
            l.append(j)
    
    print("result is:",l)

mylist([10, 20, 25, 30, 35], [40, 45, 60, 75, 90])
```
