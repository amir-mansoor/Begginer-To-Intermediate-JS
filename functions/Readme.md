### JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task.
A JavaScript function is executed when "something"calls it

Example function to add two numbers
```javascript
function sum(a,b) {
    return a + b
}
```

#### JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

#### Function Calling 

The code inside the function will execute when "something" calls the function:

- When an event occurs
- When it is called from JavaScript code
- Automatically (self call)

#### Function Return

When JavaScript reaches a return statement, the function will stop executing.
```javascript
let x = addition(4, 3);

function addition(a, b) {
// Function returns the sum of a and b
  return a + b;
}
```

You can use the function code many times
You can use the same code with different arguments like we pass 4,3 after that we can pass other numbers

we can call a function by simple using function name and parentheses()
Example
```javascript
function product(a,b) {
    return a * b
}

// Call a function
let x = product(1,2)
```

### Local Variables
Variables declared within a JavaScript function, become LOCAL to the function.
Local variables can only be accessed from within the function.

```javascript

// code here cannot use number variable
function getPrime(x) {
    let number = 0;
    // code here can use number variable
}

// code here cannot use number variable
```

Local variables are only recognized inside their functions, variables with the same name can be used in different functions.
Local variables are created when a function starts, and deleted when the function is completed.


