### **Methods of Primitives**  
1. Take a string and find its length using `.length`.  
2. Convert a number to its exponential form using `.toExponential()`.  
3. Convert the first letter of a string to uppercase using `.toUpperCase()` and concatenate it with the rest of the string.  
4. Check if a string starts with a specific character using `.startsWith()`.  

---

### **Numbers**  
1. Generate a random number between 50 and 100 using `Math.random()`.  
2. Round the number `3.14159` to the nearest integer using `Math.round()`.  
3. Check if a number is finite using `Number.isFinite()`.  
4. Write a program to calculate the square root of a number using `Math.sqrt()`.  

---

### **Strings**  
1. Find the position of the first occurrence of the letter `'o'` in the string `"hello world"` using `.indexOf()`.  
2. Replace `"world"` with `"universe"` in the string `"hello world"` using `.replace()`.  
3. Repeat the string `"ha"` three times using `.repeat()`.  
4. Reverse the string `"hello"` using array methods and `.split()`.  

---

### **Arrays**  
1. Create an array of five fruits and log the second fruit.  
2. Check if the element `'apple'` exists in the array using `.includes()`.  
3. Sort an array of numbers in ascending order using `.sort()`.  
4. Join all elements of an array into a single string with a comma separator using `.join()`.  

---

### **Array Methods**  
1. Write a program to multiply all elements in an array by 2 using `.map()`.  
2. Find the first number greater than 10 in an array using `.find()`.  
3. Create a new array of even numbers from an existing array using `.filter()`.  
4. Calculate the average of an array of numbers using `.reduce()`.  

---

### **Iterables**  
1. Iterate over a string `"JavaScript"` using a `for...of` loop and log each character.  
2. Write a function to iterate through an array and log only odd-indexed elements.  
3. Convert a NodeList (like document.querySelectorAll result) to an array using `Array.from()` and log the result.  

---

### **Map and Set**  
1. Create a `Map` to store country names as keys and their capitals as values. Retrieve a capital.  
2. Write a program to add and delete elements in a `Set`.  
3. Check if a `Map` has a specific key and a `Set` has a specific value.  
4. Convert an array of objects into a `Map` where each key is a property from the object.  

---

### **WeakMap and WeakSet**  
1. Demonstrate the difference between a `Map` and a `WeakMap` by adding primitive and object keys.  
2. Write a program to show how `WeakSet` holds only objects and automatically removes unreferenced objects.  
3. Use a `WeakMap` to associate metadata with an object without affecting garbage collection.  

---

### **Object.keys, values, entries**  
1. Log all keys of the object `{name: "John", age: 30}` using `Object.keys()`.  
2. Write a program to find the sum of all values of an object using `Object.values()`.  
3. Convert an object to an array of key-value pairs using `Object.entries()`.  

---

### **Destructuring Assignment**  
1. Destructure the properties `name` and `age` from the object `{name: "Alice", age: 25}`.  
2. Use destructuring to swap two variables `a` and `b`.  
3. Write a function that takes an object as a parameter and destructures its properties.  
4. Destructure an array with more elements than variables, using the rest operator.  

---

### **Date and Time**  
1. Write a program to log the current day of the week using `new Date().getDay()`.  
2. Add 7 days to the current date and log the result.  
3. Write a program to calculate how many days are left until the end of the year.  
4. Format the current time as `HH:MM:SS` using `Date` methods.  

---

### **JSON Methods, toJSON**  
1. Convert the object `{name: "Alice", age: 25}` into a JSON string using `JSON.stringify()`.  
2. Parse the JSON string `'{"name":"Alice","age":25}'` back into an object using `JSON.parse()`.  
3. Create an object with a `toJSON` method and demonstrate how it customizes JSON serialization.  
4. Write a function that takes an object and saves it as a JSON file in the browser (using `Blob` or `FileSaver.js`).  

