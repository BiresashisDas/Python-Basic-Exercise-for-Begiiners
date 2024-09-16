# Q. Use for, .split(), and if to create a Statement that will print out words that start with 's':

***Sol:-***

```python
st = 'Sam Print only the words that start with s in this sentence'

for s in st.split():
    if s.upper().startswith('s'):
        print(s)
```

**OUTPUT**

```
start
s
sentence
```
