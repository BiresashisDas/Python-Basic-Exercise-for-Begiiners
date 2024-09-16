# Q. Use List Comprehension to create a list of the first letters of every word in the string below:

***Sol:-***

```python
st = 'Create a list of the first letters of every word in this string'

l = list(st.split())

for i in l:
    print(f"{i[0]} : First letter of '{i}'")
```

**OUTPUT**

```
C : First letter of 'Create'
a : First letter of 'a'
l : First letter of 'list'
o : First letter of 'of'
t : First letter of 'the'
f : First letter of 'first'
l : First letter of 'letters'
o : First letter of 'of'
e : First letter of 'every'
w : First letter of 'word'
i : First letter of 'in'
t : First letter of 'this'
s : First letter of 'string'
```
