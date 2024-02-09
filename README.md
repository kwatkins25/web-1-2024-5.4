# Lesson 5.5: Using Loops with DOM Manipulation

## Overview
This lesson focuses on utilizing `forEach` loops in JavaScript to manipulate the Document Object Model (DOM) effectively. The primary goal is to iterate over elements and apply changes dynamically to the HTML structure of a webpage.

## Key Concepts

### `forEach` Loops
- The `forEach` loop in JavaScript allows executing a function once for each item in an array.
- Syntax: `array.forEach(function(currentValue, index, arr), thisValue)`

### DOM Manipulation
- Creating, updating, and appending elements to the DOM are fundamental operations.
- Methods like `document.createElement()`, `element.appendChild()`, and property updates (e.g., `element.innerHTML`) are used.

## Code Snippets

### Iterating Over an Array
```javascript
let fruits = ["apple", "banana", "cherry"];
fruits.forEach(function(fruit) {
  console.log(fruit);
});
```

### Creating and Appending Elements
```javascript
let users = ["Alice", "Bob", "Charlie"];
users.forEach(function(user){
  let p = document.createElement("p");
  p.innerHTML = `Hello, ${user}!`;
  document.body.appendChild(p);
});
```

---

Happy Coding! 😊