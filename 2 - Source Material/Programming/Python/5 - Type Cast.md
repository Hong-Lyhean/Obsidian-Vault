2024-08-06 14:47

Status: #Completed 

Tags: [[Python Programming|Python Programming]]

Source: 
# 5 - Type Cast

Type casting is to convert the data type of a value to another data type
``` python
a = 1
b = 1.5
c = "3"
```
and type casting is not the permanent change if we want to make the permanent change we need to re-assign it Ex:
``` python
a = str(a)
b = int(b)
c = float(c)
```

### integer
Convert the other data type to integer data type
``` python
print(int(b))
print(int(c))

print(type(int(b)))
print(type(int(c)))
```
if the string contain the invalid literal for integer it will be `error`

### float
Convert the other data type to float data type
``` python
print(float(a))
print(float(c))

print(type(float(a)))
print(type(float(c)))
```
if the string contain the invalid literal for number it will be `error`

### string
Convert the other data type to string data type
``` python
print(str(a))
print(str(b))

print(type(str(a)))
print(type(str(b)))
```


# References

