# Strings

Strings are for storing text and they are written with quotes

## Template String 
Template ware introduced with ES6, templates are string enclosed with backticks 

## Strings as Object 

Normally Javascript Strings are primitive values but strings can also be defined as objects with the keyword `new`

But it is not a good practice to use new keyword to create string object as the new keyword complicated the code and slow down the execution speed, sometimes it produce some unexpected results.


## String Methods

Javascript strings are primitive and immutable, all string methods produce a new string without aultering the existing string.

### length
Returns the length of a string

### charAt()
Return the character at a specified position

### charCodeAt()
Return the ascii code of the character at a specified index

### at()
it is introduced in ES2022 and it's almost similar to the chatAt() only difference is it can also give the character at a negetive index instead of charAt(myString.length-2)

```html
const name="nilu"
name.at(-1) //"u"
```

### Access || []
Property Access might be little unpredictable, it makes the string looks like an array
it return undefined if no character was found in some index, while charAt() return an empty string,
It is read only you can not change the any character using it 

```html
let text = "Hello";
text[3] = 'e';
```
this code will not give an error but it will not change the text string


## Extracting String Parts

There are 3 ways to extract a part of a string and return the extracted part in a new string.

1. slice(start, end)
2. substring(start, end)
3. substr(start, length)

### Example

```html
let text = "Apple, Banana, Kiwi";

slice(4,8) //"e, B"

slice(4) //"e, Banana, Kiwi"

slice(-4) //"Kiwi"

//The difference is that start and end values less than 0 are treated as 0 in substring()

text.substr(4,4) //"e, b"

```

## toUpperCase() and toLowerCase() convert the string to uppercase or lowercase
## trim() method removes whitespace from both side of a string, trimStart() and trimEnd() method removes whitespace from start and end of a string.
## replace() replace the only the first match `text.replace("abcd", "xyz")`
## replaceAll() replace all the match `text.replaceAll("abcd", "xyz")` 
## split() convert a string to an array `text.split(",")`

## indexOf() method returns the index of the first occurrence of a string in a string, or it returns -1 if the string is not found.
## lastIndexOf() method returns the index of the last occurrence of a strign in a strign or it return -1 if the string is not found.

