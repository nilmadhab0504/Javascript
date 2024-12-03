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

