# Python

## Python Programming Structure

### Indentation

1. Indentation is separate program into block of code
2. Indentation usually use Tab button on keyboard
```python
a = 15
if a > 4:
  print("Great")
else:
 print("Try Again")
```
3. At the example you can see that the indentation is different, this not recommended due the program will be difficult to read
4. The program should look like this
```python
a = 15
if a > 4:
  print("Great")
else:
  print("Try Again")
```

### Variable

1. Variable is name that have value
```python
a = "Hello python"
b = 8991
pi = 3.14
l = [1,2,3,4]
```
2. At code block above we make 4 variable **a** type data string, **b** type data integer, **pi** type data boolean, **l** type data array

### Variable Name

1. In general programmer use variable name corresponding with perpose and value of variable
2. On python or maybe other programming language have rules for write variable name
3. On python has the following rules:
    1. Variable do not need to be declraed with data types
    ```python
    name: str = "Kun"

    # can be like this
    name = "Kun"
    ```
    2. writing variables must begin with a letter, and for subsequent characters can be letters or numbers
    ```python
    # cannot like this
    1name = "Aba"
    \name = "Aba"

    # must begin with letter
    name = "Aba"
    ```
    3. Variable in python is case-sensitive
    ```python
    Name = "abo"
    name = "abo"
    
    # 2 variable above is different
    ```
    4. Variable name cannot be separated by space
    ```python
    # you cannot use space
    my name = "huk"
    ```
    5. If you want separate variable names use "\_" (underscore)
    ```python
    my_name = "huk"
    ```
    6. Variable names cannot be the same as functions provided by python like:
    ```python
    and
    assert
    break
    class
    etc
    ```
