# Functions

Functions is a block of code designed to perform a particular task, in JavaScript Functions are defined with the keyword `function`, followed by the `name` and the parentheses `()`.
the parentheses may include parameters named separated by commas.
the code to be executed by the function, is placed inside the curly brackets

## Example

```html
function name(parameter1, parameter2){
// code to be executed
}
```
the code inside the function only executed when the function is invoked.
function `Arguments` are the values received by the function when it is invoked, inside the function the arguments are behave like local variables.

## Anonymous function/Function Expression
A JavaScript is can also be defined as expressions and stored in a variable.

```html
const x=function(a,b){ return a+b };
const y=x(3,4);
```

## Function() Constructor
Function can also be defined with a build in javascript function constructor called Function()

```html
const x = new Function( "a", "b", "return a*b");
let y=x(3,4);
```

## Hoisting
Hoisting in javascript's default behaviour of moving all the declarations to the top of the current scope ( to the top of the script or the current function )
Hoisting applies to variable declaration and the function declarations, because of that javascript function can be called before they are declared.

## Self-Invoking Function
Function expressions can be made self-invoking.
A self invoking expressions will execute automatically 
adding parentheses around the function make it self-invoking

## Example
```html
(function(){
let x=10;
}
)();
```

## Arrow Function
- Arrow function allows a short syntax for writing an function, you don't need the function and return keywords and the curly brackets.
- Arrow functions do not have their own this. they are not well suited for the object methods.
- Arrow functions are not hoisted, they must be defined before use.
- You can only omit the curly brackets and the return keyword if the function is a single statement. Because of this it is good practice to always keep the brackets and the return keyword.

### Example
```html
const x = (a, b)=>a*b;
const y = (a, b)=>{
return a*b;
}
```


## Function Rest Parameter 
The rest parameter (...) allows a function to treat an indefinit number of arguments as an array

### Example 

```html
const sum =(...args)=>{
let sum=0;
for(let arg of args)sum+=arg;
return sum;
}
const x=sum(1,2,3,4,5,6,7,8,9);
```
## The Arguments abject

The Arguments objects contains an array of arguments when the function invoked 

### Example 
```html
x=findMax(1,2,3,4,5,6);
function findMax(){
let max=-Infinity;
for(let arg of arguments){
if(arg>max)arg=max;
}
return arg;
}
```
we can not use arguments in arraw function as arrow function do not hav their own arguments.



