### **Objects**

1. Create an object `person` with properties `name`, `age`, and `city`, then log all its properties.
2. Write a program to add a new property `hobby` to the `person` object dynamically.
3. Check if the property `age` exists in the `person` object using the `in` operator.
4. Write a function that takes an object and logs all its key-value pairs in the format: `key: value`.

---

### **Object References and Copying**

1. Create an object `original` and assign it to another variable `copy`. Modify `copy` and log `original`—explain the result.
2. Use `Object.assign()` to create a shallow copy of an object and demonstrate how changing nested objects affects both copies.
3. Use the spread operator `{...}` to copy an object and add a new property.
4. Write a function to create a deep copy of an object and demonstrate its usage with nested objects.

---

### **Garbage Collection**

1. Write a program that creates an object, assigns it to another variable, then sets the original variable to `null`. Log both variables and explain garbage collection in this context.
2. Create an object inside a function and return it. Explain when the object is eligible for garbage collection.
3. Write a program to show how objects without references are removed from memory.
4. Explain with code why circular references can prevent garbage collection and demonstrate a solution using `WeakMap`.

---

### **Object Methods, "this"**

1. Create an object `car` with a method `start` that logs "The car has started!". Use `this` to include the car’s `model` in the message.
2. Write a program with an object `user` and a method `greet`. Use `this` to access the `name` property inside the method.
3. Write an object with a nested object and a method. Demonstrate how `this` behaves when accessing properties from the nested object.
4. Bind a method of an object to a different context using `bind` and demonstrate the change in behavior.

---

### **Constructor, Operator "new"**

1. Write a constructor function `Person` that creates objects with properties `name` and `age`. Create two instances of `Person`.
2. Modify the constructor function to include a method `introduce` that logs "Hi, I am [name] and I am [age] years old!".
3. Use the `new` operator to create an object and demonstrate how it differs from creating an object without `new`.
4. Add a default value to a property in the constructor function and show how it works with and without providing a value when creating an object.

---

### **Optional Chaining '?.'**

1. Write an object `user` with nested properties `address` and `city`. Use optional chaining to safely access `user.address.city`.
2. Write a program to safely check if a method exists on an object before calling it using optional chaining.
3. Create a nested object `library` with a list of books. Safely access the first book title even if `library.books` or `books[0]` might not exist.
4. Combine optional chaining with the nullish coalescing operator (`??`) to provide a default value when accessing deeply nested properties. 
