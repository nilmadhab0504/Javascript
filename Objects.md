# Objects 
Objects are collection of key value pairs where keys are string and values are any data type inluding other objects, array, functions.
objects are used to represent and structure data as well as encapsulate behavior through methods.

## How to Define an Object
in javascript we can define objects 
- Using an Object Literal
- Using the new keyword
- Using an Object Constructor

## Object Literal

an object literal is a list of name:value pair inside curly braces `{}`
```html
//method 1 to create object
const person1 = {firstName:"Nil", lastName:"Tewari", age: 20};

//method 2 to create object
const person2 = {};
person2.firstName = "John";
person2.lastName = "Doe";
person2.age = 30;
```
## Using New Keyword

```html
const person = new Object();

person.firstName = "John";
person.lastName = "Doe";
```

we can access object properties in two ways 
1. objectName.propertyName
2. objectName["propertyName"]

## Methods

Methods are the actions that are performed on the objects, Methods are function definitions that are stored as property values.

### Example

```html
const person = {
firstName : "John"
lastName : "Doe"

fullName : function() {
return this.firstName + " " + this.lastName;
}
}

```

### JavaScript Objects are mutble, they are addresed by reference not by value

```html
const person = {
firstName : "Nil"
lastName : "tewari"
age : 24
}

const person2 = person;

person2.age=25
```
the object `person2` is not a copy of `person`, they both share the same memory any changes on `person2` reflacts on `person` also 


### We can delete object properties using the delete keyword

```html
const person = {
firstName : "Nil"
lastName : "tewari"
age : 24
};
delete person[age];
delete person.lastName;
```













