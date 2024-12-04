# What is DOM?
DOM stands for document object model, in simple terms it is a structural representation of the HTML Elements that are present in a webpage or web app.
DOM represent the entire ui of the application, it is a tree data structure.
it contains a node for each UI element present in the web document, it is very useful as it allows to modify the ui using javascript.

## Disadvantage of DOM
Every time the DOM gets updated, the updated elements and it's children have to rendered again to update the ui of the page, for this, each time there is a component update the component needs to be updated and the UI components have to be re-rendered.

## Example
```html
document.getELementBYId('some-id').innerValue="new value";
```
when writing this code 
- the browser parse the HTML to find the node with the same id
- it removes the child element of that specific element
- update the element(DOM) value with the new value
- Recalculate the css for the parent and the chield elements
- update the layout
- finally traverse the tree and paint it on the screen

Recalculating the css and changing the layout involves complex algorithms, and they do affect the performance.
