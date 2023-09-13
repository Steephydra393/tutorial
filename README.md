basic function:
```py
def basicfunction():
  print("Basic Function was Ran") # This line of code is ran
  #... it will run untill there is no more code to run OR it calls return()
```And you call this function with
```py
basicfunction()
```

basic function w/ arguments
```py
def argfunction(arg1, arg2):
  print("Argument Function was Ran") # This line of code is ran
  print(arg1)
  print(arg2)
  #... it will run untill there is no more code to run OR it calls return()
```and you call this function with
```py
argfunction("String", 2) # You can replace these with ANY datatype (you will learn these later)
```

function w/ a description
```py
def disfunction():
  """This function is part of a course made by...
  JOSEPH :)"""
  print("Disfunction")
```And ofcourse you can call this function with
```py
disfunction()
```

`return` & `return()`

`return()` can be used to end a function by just doing
```py
return()
``` but you can also pass some data with it
`return(datavariable)` will send the value of `datavariable` to the caller
```py
return(datavariable)
```

## You can use `return` and `return()` as the same.
Note: If you use `return`, make sure to have a space after `return` before adding any variables

Here is an example:

`return()` w/ one value - ```py
def ask():
  inputvar = input("Enter a value: ")
  return(inputvar) # or `return inputvar`

data = ask()
print(data)
```

`return()` w/ many values - ```py
def ask():
  inputvar1 = input("Enter a value: ")
  inputvar2 = input("Enter a value: ")
  inputvar3 = input("Enter a value: ")
  return(inputvar1, inputvar2, inputvar3) # or `return inputvar1, inputvar2, inputvar3`

data = ask()
print(data[0]) # data[0] gets the value of the first value in the list `data`
print(data[1]) # data[1] gets the value of the second value in the list `data`
print(data[2]) # data[2] gets the value of the third value in the list `data`
```

## Python starts counting from 0 instead of 1.
0 = 1
1 = 2
2 = 3
...

(basic) Data types:
## Strings:
- Starts with " and ends with "
- Is normally text

example:
```py
print("String 1.2 1") 
```will print `String 1.2 1`

## Integers:
- Whole numbers only
- No decimal points
- No text

example:
```py
print(1)
print(2)
print(0)
```will print:
1
2
0

## Floats:
- Decimal points required
- No text
- No whole numbers

example:
```py
print(1.1)
print(1.0)
print(0.64)
```will print:
1.1
1.0
0.64
in the console

## Lists:
- Contains multiple datatypes
- Contains multiple values
- Surrounded by square brackets

example:
```py
variable = ["data", 1, 1.0]
print(variable[0]) # This will print "data" into the console
print(variable[1]) # This will print 1 into the console
print(variable[2]) # This will print 1.0 into the console
```

## Tuples:
- Contains multiple of one datatype
- Surrounded by ()'s

example:
```py
variable = ("data1", "data2", "data3")

print(variable) # Print the entire tuple
print(variable[0]) # Prints "data1" in this case
print(variable[1]) # Prints "data2" in this case
print(variable[2]) # Prints "data3" in this case
```
notes:
- A tuple containing only strings would be called a "tuple of strings"
- A tuple containing only integers would be called a "tuple of integers"
- A tuple containing only floats would be called a "tuple of floats"
- A tuple containing only lists would be called a "tuple of floats"
