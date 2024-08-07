2024-07-22 22:41

Status: #Completed 

Tags: [[Python Programming|Python Programming]]

Source: 
# 4 - String Method

Some of useful string method
``` python
name = "Heaven Refining Demon Venerable"
```

### len
To get the length of the string
``` python
print(len(name))
```

### find
To find the index of the character or string in string, index start from zero
``` python
print(name.find('a'))
```
when have the character or string that want to find doesn't have in string it will return `-1`

### capitalize
Transform the string to capitalize but it only work for the first string or letter
``` python
print(name.capitalize())
```

### upper
Transform all the string or character to uppercase letter
``` python
print(name.upper())
```

### lower
Transform all the string or character to lowercase letter
``` python
print(name.lower())
```

### isdigit
To check the string or character is a digit or not, return `True` or `False`
``` python
print(name.isdigit())
```

### isalpha
To check the string or character is an alphabet or not, return `True` or `False`
``` python
print(name.isalpha())
```
if the string have white-space it will return `False`. cause white-space is not the alphabet

### count
To count the character or string to see how many of it in the string
``` python
print(name.count('a'))
```

### replace
To replace the old string or character to new string or character in string
``` python
print(name.replace('old', 'new'))
```
for replace method it accept string only

### useful tip
to print the same character or string multiple time we can multiple it with number
``` python
print(name*5)
```


# References

