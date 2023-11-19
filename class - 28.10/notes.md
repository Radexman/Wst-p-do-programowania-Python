# **Wstęp do programowania Python - 28.10**

## **Python Features**

-   Dynamic typing,
-   Whitespace is part of syntax,
-   Language of data science,
-   Endorses Object Programming,

## **Fundamentals**

-   Print methos works like console.log in JS,
-   '+' operathor is used for string contatination,
-   Pyhon doesn't use EOL character,
-   Unexpected indentations causes compilation errors,

Just like in JavaScript data types are declared dynamically and variables can be redeclared.

### **Declaring Variables**

Variable naming conventions

**Accepted**
Variable names are case-sensitive. Accepted variable names are listed below. Can use camelCase, Snake_case.

```py
# Legal Variable Names
myvar = 'John'
my_var = 'John'
_my_var = 'John'
myVar = 'John'
My_var = 'John'
myVar = 'John'
MYVAR = 'John'
myvar2 = 'John'
```

**Unaccepted**

Variable names cannot start with integer, can't include space
between characters ot have white space between them.

```py
# Illegal Variable Names
2myvar = 'John'
my-var = 'John'
my var = 'John'
```

**Example**

Example of variables declaration, print and input methods.
Comments in Python are created with '#' character in front of it comment.

```py
# Example
userName = input('Please input your name: ')
catName = input("Please input your cat's name: ")
print ('Your name is ' + userName + 'and your cat name is ' + catName)
```

### **Conditional Statements**

There is no "block" syntax in "if" statement in Python, there is just simply whitespace. Strict comparison operator is double equality symbol (in JS it's three).

'elif' is 'else if' in Python but 'else' stays the same.

```py
a = 5
b = 5

if a>b:
    print('a is bigger than b')
elif a==b:
    print('a is equal to b')
else:
    print('Other case')
```

We don't use any kind of keyword for creating variables, we just need to put down variables name.

**Comparing Strings**

Exclamation mark is the 'not' operator.

#### **Weak Typing**

We cannot compare two different data types, this will cause an TypeError. We can compare two same data types.

### **Lists**

Lists are arrays in Python

```py
list = [3, 45, 567, 'kitty']
print(list)
```

## **Do To**

-   [ ] Pyhon basics
-   [ ] How Python works on low level
-   [ ] ASCII Table
-   [ ] Notepad++
