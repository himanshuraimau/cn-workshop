#### **An Introduction to JavaScript**
1. Write a program that shows an alert saying "Welcome to your first JavaScript program!".
2. Log your name and favorite programming language to the console.
3. Open the browser console and manually execute `alert("Hello from the console!")`.

#### **Manuals and Specifications**
1. Find the ECMAScript specification online. Write down one interesting fact you learned about JavaScript.
2. Explain what the "latest specification" means in simple terms.
3. Search for the difference between `var`, `let`, and `const` and write examples for each.

#### **Code Editors**
1. Install a code editor (e.g., VSCode) and write a script to print "Code editor setup complete!".
2. Save a file named `test.js` with a script to log "Testing complete!" and execute it.
3. Customize your editor's theme and share your favorite one with the class.

#### **Developer Console**
1. Open the developer console and log "Hello, Console!".
2. Use the console to calculate `5 * 10` and explain the result.
3. Find an error in this code using the console:  
   ```js
   alrt("Missing 'e' in alert");
   ```

---

### **JavaScript Fundamentals**

#### **Hello, world!**
1. Write a program to display "Hello, world!" in an alert box.
2. Log "Let's learn JavaScript fundamentals!" to the console.
3. Create a simple HTML file and link a JavaScript file that displays "Hello, Students!" in an alert.

#### **Code Structure**
1. Write a program with multiple `console.log` statements and organize them using comments.
2. Correct the syntax errors in this code:  
   ```js
   console.log("Hello"
   console.log("World!);
   ```
3. Write a program where each line demonstrates a valid comment in JavaScript.

#### **The modern mode, "use strict"**
1. Write a script with `"use strict"` and try creating a variable without `let`, `const`, or `var`. Observe the behavior.
2. Remove `"use strict"` and run the above script again. What changes?
3. Write a program with `"use strict"` that logs "Strict mode is active!" to the console.

#### **Variables**
1. Declare variables `firstName` and `lastName` and log them together as "Hello, [firstName] [lastName]!".
2. Declare a constant `PI` with the value `3.14` and try to change its value. What happens?
3. Write a program that swaps the values of two variables:  
   ```js
   let x = 5;
   let y = 10;
   ```

#### **Data Types**
1. Declare and log variables of types: string, number, boolean, and undefined.
2. Write a program to check the type of a variable using `typeof`.
3. Convert a number into a string and log the result. Then convert it back to a number.

#### **Interaction: alert, prompt, confirm**
1. Write a script that asks the user for their favorite color using `prompt` and displays it in an alert.
2. Use `confirm` to ask, "Do you like coding?" and log the response.
3. Write a script that asks for the user's name using `prompt` and confirms their input with a `confirm`.

#### **Type Conversions**
1. Convert the string `"123"` to a number and log it.
2. Write a program to check if a value is `NaN` using `isNaN`.
3. Convert `true` and `false` to numbers and log the results.

#### **Basic Operators, Maths**
1. Write a program to add, subtract, multiply, and divide two numbers.
2. Use the modulo operator `%` to find the remainder when 17 is divided by 3.
3. Write a script to calculate the square of a number.

#### **Comparisons**
1. Compare two numbers and log whether they are equal, greater, or less.
2. Write a program to check if a number is between 10 and 100.
3. Log the result of the comparison `0 == false` and explain the output.

#### **Conditional Branching: if, '?'**
1. Write a script that checks if a user is an adult based on their age.
2. Rewrite the above script using the ternary operator `?`.
3. Write a program to check if a number is positive, negative, or zero.

#### **Logical Operators**
1. Check if two variables, `x` and `y`, are both greater than 0.
2. Write a script to log `true` if either `x` or `y` is greater than 10.
3. Write a program to log the logical AND (`&&`), OR (`||`), and NOT (`!`) operations for `true` and `false`.

#### **Nullish Coalescing Operator '??'**
1. Assign a default value to a variable using `??`.
2. Write a program to check if `null ?? "default"` evaluates to `"default"`.
3. Replace `||` with `??` in the following:  
   ```js
   let user = prompt("Enter your name") || "Anonymous";
   ```

#### **Loops: while and for**
1. Write a `for` loop to print numbers from 1 to 10.
2. Write a `while` loop to calculate the factorial of 5.
3. Use a `for` loop to log all even numbers between 1 and 20.

#### **The "switch" statement**
1. Write a `switch` statement to log the season based on the month number.
2. Modify the above program to handle invalid numbers.
3. Use `switch` to log a greeting in different languages based on a given `language` variable.

#### **Functions**
1. Write a function `greet` that takes a name and logs "Hello, [name]!".
2. Create a function to calculate the sum of two numbers.
3. Write a function that returns `true` if a number is even and `false` otherwise.

#### **Function Expressions**
1. Write a function expression to find the cube of a number.
2. Rewrite the `greet` function above as a function expression.
3. Create an immediately invoked function expression (IIFE) that logs "IIFE executed!".

#### **Arrow Functions, The Basics**
1. Write an arrow function to calculate the area of a rectangle.
2. Convert the following function into an arrow function:  
   ```js
   function subtract(a, b) {
       return a - b;
   }
   ```
3. Create an arrow function that checks if a number is greater than 50.

#### **JavaScript Specials**
1. Write a script demonstrating type coercion: `"5" * 2` and `"5" + 2`.
2. Compare `0 == false` and `0 === false`. Log the results.
3. Write a script to show that objects are compared by reference, not value.
