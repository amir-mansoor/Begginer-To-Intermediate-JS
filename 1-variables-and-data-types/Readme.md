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

JavaScript Variables can be declared in 3 ways:

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

### Javascript Data Types 

#### Javascript has 8 DataTypes
1. String
2. Number
3. Bigint
4. Boolean
5. Undefined
6. Null
7. Symbol
8. Object 

#### The Object DataType
The object data type can contain:
- An object
- An array
- A date

#### Examples
```
// Numbers:
let length = 16;
let weight = 7.5;

// Strings:
let color = "Yellow";
let lastName = "Johnson";

// Booleans
let x = true;
let y = false;

// Object:
const person = {firstName:"John", lastName:"Doe"};

// Array object:
const cars = ["Saab", "Volvo", "BMW"];

// Date object:
const date = new Date("2022-03-25"); 
```
### Note

A JavaScript variable can hold any type of data.

#### The Concept Of Data Types
In programming, data types is an important concept.
To be able to operate on variables, it is important to know something about the type.
Without data types, a computer cannot safely solve this:

```
let x = 16 + "Volvo";
```
Does it make any sense to add "Volvo" to sixteen? Will it produce an error or will it produce a result?
JavaScript will treat the example above as:

```
let x = "16" + "Volvo";
```

### NOTE
When adding a number and a string, JavaScript will treat the number as a string as we see above.

**JavaScript evaluates expressions from left to right. Different sequences can produce different results:**
```
let x = 16 + 4 + "Volvo"; 
```
result will be 

```
20Volvo
```

another example
```
let x = "Volvo" + 16 + 4; 
```
Result
```
Volvo164 
```

In the first example, JavaScript treats 16 and 4 as numbers, until it reaches "Volvo".
In the second example, since the first operand is a string, all operands are treated as strings.

### JavaScript Types are Dynamic
JavaScript has dynamic types. This means that the same variable can be used to hold different data types:
```
let x;       // Now x is undefined
x = 5;       // Now x is a Number
x = "John";  // Now x is a String 
```


