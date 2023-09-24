#### JavaScript Syntax

JavaScript syntax is the set of rules, how JavaScript programs are constructed:

you don't need to understand what's going on here it's just a basic syntax

```
// How to create variables:
var x;
let y;

// How to use variables:
x = 5;
y = 6;
let z = x + y;
```

#### JavaScript Variables

##### Variables are Containers for Storing Data

JavaScript Variables can be declared in 4 ways:

- Using var 
- Using const 
- Using let

In this first example, x, y, and z are undeclared variables.

They are automatically declared when first used:

Example 
```
x = 5;
y = 6;
z = x + y;
```

### NOTE

**It is considered good programming practice to always declare variables before use.**

From the examples you can guess:

- x stores the value 5
- y stores the value 6
- z stores the value 11

### NOTE
- The **var** keyword was used in all JavaScript code from 1995 to 2015.
- The **let** and **const** keywords were added to JavaScript in 2015.
- The **var** keyword should only be used in code written for older browsers.

#### When to Use var, let, or const?

1. Always declare variables
2. Always use **const** if the value should not be changed
3. Always use **const** if the type should not be changed (Arrays and Objects) 
4. Only use **let** if you can't use **const**
5. Only use i **var** if you MUST support old browsers.

#### Javascript Identifiers
All JavaScript **variables** must be identified with **unique** names.
These unique names are called **identifiers**.
The general rules for constructing names for variables (unique identifiers) are:

- Names can contain letters, digits, underscores, and dollar signs.
- Names must begin with a letter.
- Names can also begin with $ and _ (but we will not use it in this tutorial).
- Names are case sensitive (y and Y are different variables).
- Reserved words (like JavaScript keywords) cannot be used as names.






