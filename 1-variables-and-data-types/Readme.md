#### JavaScript Syntax

JavaScript syntax is the set of rules, how JavaScript programs are constructed:

you don't need to understand what's going on here it's just a basic syntax

```javascript
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
```javascript
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
```javascript
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

```javascript
let x = "16" + "Volvo";
```

### NOTE
When adding a number and a string, JavaScript will treat the number as a string as we see above.

**JavaScript evaluates expressions from left to right. Different sequences can produce different results:**
```javascript
let x = 16 + 4 + "Volvo"; 
```
result will be 

```javascript
20Volvo
```

another example
```javascript
let x = "Volvo" + 16 + 4; 
```
Result
```javascript
Volvo164 
```

In the first example, JavaScript treats 16 and 4 as numbers, until it reaches "Volvo".
In the second example, since the first operand is a string, all operands are treated as strings.

### JavaScript Types are Dynamic
JavaScript has dynamic types. This means that the same variable can be used to hold different data types:
```javascript
let x;       // Now x is undefined
x = 5;       // Now x is a Number
x = "John";  // Now x is a String 
```

### Javascript Strings 
A string (or a text string) is a series of characters like "John Doe".
Strings are written with quotes. You can use single or double quotes:

```javascript
// Using double quotes:
let carName1 = "Volvo XC60";

// Using single quotes:
let carName2 = 'Volvo XC60';
```

You can use quotes inside a string, as long as they don't match the quotes surrounding the string:
```javscript
// Single quote inside double quotes:
let answer1 = "It's alright";

// Single quotes inside double quotes:
let answer2 = "He is called 'Johnny'";

// Double quotes inside single quotes:
let answer3 = 'He is called "Johnny"';
```

### Javascript Numbers
All JavaScript numbers are stored as decimal numbers (floating point).

Numbers can be written with, or without decimals:
```javascript
// With decimals:
let x1 = 34.00;

// Without decimals:
let x2 = 34; 
```

### Exponential Notation
Extra large or extra small numbers can be written with scientific (exponential) notation:

```javascript
let y = 123e5;    // 12300000
let z = 123e-5;   // 0.00123 
```

### Javascript BigInt
All JavaScript numbers are stored in a a 64-bit floating-point format.
JavaScript BigInt is a new datatype (ES2020) that can be used to store integer values that are too big to be represented by a normal JavaScript Number.

```javascript
 let x = BigInt("123456789012345678901234567890"); 
```

### Javascript Booleans 
Booleans can only have two values: **true** or **false**.

```javascript
let x = 5;
let y = 5;
let z = 6;
(x == y)       // Returns true
(x == z)       // Returns false 
```

### Javascript Arrays

JavaScript arrays are written with square brackets.
Array items are separated by commas.
The following code declares (creates) an array called cars, containing three items (car names):

```javascript
 const cars = ["Saab", "Volvo", "BMW"]; 
```

Array indexes are zero-based, which means the first item is [0], second is [1], and so on.

### Javascript Objects

JavaScript objects are written with curly braces {}.
Object properties are written as name:value pairs, separated by commas.

```javascript
 const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
```

The object (person) in the example above has 4 properties: firstName, lastName, age, and eyeColor.

### The typeof Operator

You can use the JavaScript typeof operator to find the type of a JavaScript variable.
The typeof operator returns the type of a variable or an expression:
