# Function definition syntax

In Python, functions are defined with the keyword `def`{.python}, a function name, parameters in parentheses, and a colon. The body of the function is indented. User-defined functions are called the same way as intrinsic functions.

```py-cell
def function_name(arg1, arg2):
    # function body
    print(arg1, arg2)

# Unindented code signifies the end of the function definition
x = 1
function_name(x, 4)
```

# Return Values

Functions can return values using the `return`{.python} statement. The value of the expression following the `return`{.python} keyword is returned to the caller.

```py-cell
def add(a, b):
    return a + b

result = add(3, 5)
print(result)
```

If no `return`{.python} statement is encountered, the function returns `None`{.python}.

```py-cell
def no_return():
    print("This function does not return a value")

result = no_return()
print(result)
```
