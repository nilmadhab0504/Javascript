# Array
An array is a special type of variable which can hold more than one value.

### Example
`const cars = ["Saab", "Volvo", "BMW"];`

## Array Methods

### pop() method return the value that was popped
### push() method add a new element in the array
### shift() method removes the first element and shifts all other elements to a lower index and return the value that was shifted out.
### unshift(value) method add a new element at the beginning of the array and unshift older elements.
### length gives the size of the array

### concat() method creates a new array by merging two arrays.

```html
const arr1 = [1,2,3];
const arr2 = [4,5,6];
const resArray = arr1.concat(arr2); // [1,2,3,4,5,6]
```

### flat() method creates a new array with sub-array elements concatenated to a specific depth.

```html
const arr = [ [1,2,3], [4,5], [6]];
const resArr = arr.flat() //[1,2,3,4,5,6];
```

### flatMap() method first maps all elements of an array and then creates a new array by flattening the array.

```html
const arr = [1,2,3,4];
const resArr = arr.flatMap(x=>[x,x*10]) // [1,10,2,20,3,30,4,40]
```

### indexOf() method search the array for an element value and return its position and return -1 if the value not present
### lastIndexOf() method search the array for an element value and return the last position of the value
### includes() it also search element in the array and return boolean value true/false
### find() and findIndex() these two method return the value and the index of the element that satisfy the function condiion shared with the method
```html
const numbers = [4, 9, 16, 25, 29];
let first = numbers.find(myFunction); //25
let firstInd=numbers.findIndex(myFunction); //3
function myFunction(value, index, array) {
  return value > 18;
}
```

## Sort

### sort() method sort the array 
### toSorted() method create a new sorted array without aultering the original array
### reverse() resverse the array 
### toReversed() create a new reversed array without aultering the original array

By Default the sort() function sort values as string, this works well for strings but produce incorrect results for numbers.
we can fix this by providing the compare function

```html
const array=[1,4,3,2,8]
array.sort(function(a,b){
return a-b;
})

```

