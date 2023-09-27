### JavaScript Variables

Variables are Containers for Storing Data

JavaScript Variables can be declared in 3 ways:

- Using var
- Using let
- Using const

Example Using var

```javascript
var x = 5;
var y = 6;
var z = x + y;
```

Example Using const 

```javascript
const x = 5;
const y = 6;
const z = x + y;
```

Mixed Example

```javascript
const price1 = 5;
const price2 = 6;
let total = price1 + price2;
```

### When to Use var, let, or const?

1. Always declare variables

2. Always use const if the value should not be changed

3. Always use const if the type should not be changed (Arrays and Objects)

4. Only use let if you can't use const

5. Only use var if you MUST support old browsers.




