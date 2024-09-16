# Q. Go through the string below and if the length of a word is even print "even!"

***Sol:-***

```python
st = 'Print every word in this sentence that has an even number of letters'

for i in st.split():
    if len(i) % 2 == 0:
        print(f"lenghth of word '{i}' : even!")
```

**OUTPUT**

```
lenghth of word 'word' : even!
lenghth of word 'in' : even!
lenghth of word 'this' : even!
lenghth of word 'sentence' : even!
lenghth of word 'that' : even!
lenghth of word 'an' : even!
lenghth of word 'even' : even!
lenghth of word 'number' : even!
lenghth of word 'of' : even!

```
