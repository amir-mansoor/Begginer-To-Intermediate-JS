### Javascript Objects

#### Real life objects, properties and methods

in real life a car is an object.
a car has properties like weight and color, and methods like start and stop.

For example
A car is object
properties of a car are given below

car.name = Honda
car.model = 100
car.weight = 800kg 
car.color = black

methods of a car are given below
car.start()
car.stop()
car.drive()

You have already learned that JavaScript variables are containers for data values.

Objects are variables too. But objects can contain many values. 

let create an object with the name car

```javascript
const car = {type:"Fiat", model:"500", color:"white"}; 
```

The values are written as name:value pairs (name and value separated by a colon).

```javascript
const person = {firstName:"Amir", lastName:"Mansoor", age:20, eyeColor:"brown"};
```
#### Accessing Object Properties

You can access object properties in two ways 


> objectName.propertyName

or 

> objectName["propertyName"]

Example
```javascript
person.lastName;
```

Another Example

```javascript
person["lastName"]; 
``` 

#### Object Methods

Objects can also have methods.

Methods are actions that can be performed on objects.

Methods are stored in properties as function definitions.

Example

```javascript
const person = {
  firstName: "Amir",
  lastName : "Mansoor",
  id       : 111333,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};
```

In the example above, this refers to the person object.

- I.E. this.firstName means the firstName property of person.

### What is this?

In JavaScript, the this keyword refers to an object.

- In an object method, this refers to the object.
- In a function, in strict mode, this is undefined.
- In an event, this refers to the element that received the event.

### NOTE

 this is not a variable. It is a keyword. You cannot change the value of this. 

#### Accessing Object Methods

You access an object method with the following syntax:

> objectName.methodName

```javascript
name = person.fullName();
```

If you access a method without the () parentheses, it will return the function definition:





