2024-08-06 15:36

Status: #Completed 

Tags: [[Python Programming|Python Programming]]

Source: 
# 6 - User Input

We can make the user input by using function `input` the value of the input is string data type
``` python
input()
input("Enter Username: ")
```

### Get input value
We can get input value to further process by assign it to variable
``` python
name = input("Enter Username:")
print(name)
```

### Cast input data type
We can casting the data type of the input from string to other data type of other usage
``` python
year = int(input("What year were you born ?: "))
height = float(input("what is your height?: "))
current_year = 2024

print("You're ", current_year - year, "years old")
print("you're " + str(height) + "cm tall")
```
if the value of the input that we casting is the invalid literal of data type we want to casting it will be `error`



# References

