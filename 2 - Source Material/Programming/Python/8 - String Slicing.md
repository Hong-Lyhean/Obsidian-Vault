2024-08-06 20:51

Status: #Completed 

Tags: [[Python Programming]]

Source:
# 8 - String Slicing

Slicing is an action that create a sub-string by extracting elements from another string we can slice string by using these method:

- `indexing[]`
- `slice()`

for `indexing[]` format is `[start:stop:step]`
for `slice()` param form is `start, stop, step` in the parenthesis 
``` python
name = "Gu Yue Fang Yuan"
```

### indexing
indexing is the process of accessing an element in a sequencing using its position in the sequence (its index)
``` python
print(name[0])
```
just like array it position start from `0`

to get slice the string we need to use `start` and `stop` in indexing
``` python
print(name[0:5])
```
in this it only give `Gu Yu` because the `start index` is inclusive and the `stop index` is exclusive

default start index
``` python
print(name[:5])
```

default stop index
``` python
print(name[7:])
```

`step` is the value that we want to increase the index by, between `start` and `stop`
``` python
print(name[0:7:2])
```
and the default value of step is `1`

in case we want to use default `start` and `stop` with `step`
``` python
print(name[::2])
```

reverse string
``` python
print(name[::-1])
```
in this case we just need to count backward

### slice
we can using `slice` function to create a slice object which is actually reusable
``` python
print
```



# References

