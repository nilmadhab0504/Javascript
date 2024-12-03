# Basic JavaScript 

- Javascript is a high-level, dynamic language that is widely used in web developent, although it can be used in developing mobile application.
- JavaScript code can be written directly in the HTML files using `<script>` tags or as separate `.js` files.
- Browsers use javascript engines (V8 in Chrome) to interpret and execute the code.

## Insert Javascript in Html Document using `<script>` Tag

In HTML, Javascript code inserted between `<script>` and `</script>` tags.
we can place any number of `<script>` in HTML Document, Scripts can be placed in both `<head>` and `<body>` tags

There are two ways to insert javascript in html document
1. write the code in between `<script>` tag 
2. add the path of the javascript file in the `src` attribute of the script tag

## Example

```html
<!DOCTYPE html>
<html>
<head>
<script>
function myFunction(){
document.getElementById("Heading").innerHtml="Heading Chnages";
}
</script>
</head>
<body>
<h1 id="Heading"> Heading of the Document</h1>
<button type="button" onclick="myFunction()">Try it</button>
</body>
</html>
```

```html
<script src="Javascript.js"></src>
```
## Output in JavaScript

Javascript can display data in different ways 

- writing into an Html Element using innerHTML.
- writing into the Html output using document.write().
- writinng into an alart bon using window.alert().
- writing into the browser console using console.log().

