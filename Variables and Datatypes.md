# Variables in JavaScript

Variables are containers for storing data
JavaScript Variables can be decared in 4 ways

- using var
- using const
- using let
- Automatically

1. Var
   - Before introducing let and const, var was the original way to declare variables in javascript.
   - var are scoped to the nearest function and if declare outside function thay are accessible globally.
   - var variables are accessible even before their declaration.

2. Const
   - const keyword was introduced in ES6(2015)
   - it is a block scope variable
   - variables declared with var can not be redeclared or reassigned and it must assign a value when they are declared.
   - it does not define constant value. It defines constant reference to a value. because of this you can not reassign a constant value, constant array or constant object but you can change the elements of constant array or properties of constant object 

3. Let
   - let keyword was also introduced in ES6(2015)
   - variables declared with let have block scope
   - variables declared with let must be declared before use
   - variables declared with let can be redeclared in the same scope

## Block Scope
before ES6, Javascript did not have Block Scope, Javascript had global and function scope.
ES6 introduced two new keywords let and const, these two keywords provides block scope in the javascript

# Data Types in JavaScript

JavaScript has 8 Datatypes 
1. String
2. Number
3. Bigint
4. Boolean
5. Undefined
6. Null
7. Symbol
8. Object


