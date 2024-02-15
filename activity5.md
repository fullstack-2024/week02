# Activity: Introduction to JavaScript

## Part 1/2

Here's a simple lab exercise that guides you through creating an HTML file and a JavaScript file, along with instructions on how to execute the program:

1. **Install Visual Studio Code (VSCode) Extension: Live Preview**:
   - If you haven't already, install the **Live Server** extension for VSCode. This extension allows you to preview your HTML files in real-time as you make changes.

2. **Create `index.html`**:
   - Open VSCode and create a new folder for your lab (e.g., "my-lab").
   - Inside this folder, create a file named `index.html`.
   - Copy and paste the following content into `index.html`:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="shortcut icon" href="#">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Lab</title>
</head>
<body>
    <script src="./demo.js"></script>
</body>
</html>
```

3. **Create `demo.js`**:
   - In the same folder, create a file named `demo.js`.
   - Copy and paste the following content into `demo.js`:

```javascript
// This is a comment. Comments are ignored by the JavaScript interpreter.
// They are used to provide explanations or notes about the code.

// Variables and Data Types
let name = "John"; // String data type
let age = 30; // Number data type
let isStudent = true; // Boolean data type

// Control Structures
if (age >= 18) {
    console.log(name + " is an adult.");
} else {
    console.log(name + " is a minor.");
}

// Functions
function greet(name) {
    return "Hello, " + name + "!";
}

console.log(greet(name)); // Output: Hello, John!

// Input/Output
let userInput = prompt("Enter your name:"); // Prompt the user to enter their name
console.log("You entered: " + userInput); // Output the user's input
```

4. **Preview the Lab**:
   - Open `index.html` in VSCode.
   - Right-click on the file and choose **Open with Live Server**.
   - A new browser tab should open, displaying your HTML content.
   - Open the browser's developer tools (usually by pressing F12 or right-clicking and selecting "Inspect").
   - Go to the **Console** tab and observe the output from your JavaScript code.

That's it! You've created a simple lab that demonstrates variables, control structures, functions, and input/output in JavaScript. Feel free to modify the code and experiment further! 🚀

### Part 2/2

Let's create a different example in the `demo.js` file. This time, we'll focus on a simple JavaScript function that calculates the area of a rectangle. Here's the updated `demo.js`:

```javascript
// Calculate the area of a rectangle
function calculateRectangleArea(length, width) {
    if (length <= 0 || width <= 0) {
        return "Invalid dimensions. Length and width must be positive.";
    }
    return length * width;
}

// Example usage
const rectangleLength = 5;
const rectangleWidth = 3;
const area = calculateRectangleArea(rectangleLength, rectangleWidth);

console.log("Rectangle area:", area);
```

In this example:
- We define a function called `calculateRectangleArea` that takes two parameters: `length` and `width`.
- The function checks if the dimensions are positive. If not, it returns an error message.
- Otherwise, it calculates the area by multiplying the length and width.
- Finally, we call the function with sample dimensions (length = 5, width = 3) and log the result to the console.



