# CS472-Homework-03-TypeScript
## Exercise 01
Write your answers in a new file `answers1.md`:
1. Explain the difference between primitive types and object references in JavaScript.
2. What are the advantages for using TypeScript?
3. How can we run TypeScript code in the browser?
4. What are the differences between `let` and `const`? and what is their scope?
5. What is an IIFE?
 
**Note:** For all of the coding exercises below, code must be strictly typed and formatted.

## Exercise 02
Create a TypeScript function that takes an array of numbers and returns the second largest number within that array.
```typescript
// Your function code here
console.log(secondLargest([20 ,120 ,111 ,215 ,54 ,78])); // Output: 120
```
Note: you may NOT use `Array.sort()`.
  
## Exercise 03
* Create a TypeScript function that receives an array of numbers and returns a new array containing the squares of each number (use `Array.map()`).
* Create a TypeScript function that receives an array of numbers and returns a new array containing all even numbers (use `Array.filter()`).

## Exercise 04
Create two TypeScript files: 
* One file contains 4 methods to add, subtract, multiply, and divide two numbers passed as parameters.
* The other file imports the 4 methods and tests/prints out the results. 

## Exercise 05
Given the following code:
```typescript
const user = { username: "theo", role: "dog" };
const contact = { email: "theo@miu.edu", city: "Fairfield" };
const courses = ["WAP"];
```
Perform the following tasks:
1. Create a new object profile that combines the properties of user and contact using the spread operator.
2. Create a new array allCourses that includes "FPP" and "MPP" at the beginning, followed by the values from the courses array, and "WAA" at the end.

## Exercise 06
Given the following code:
```typescript
const users = [
  { id: 101, name: "Alice", age: 28, role: "admin", active: true },
  { id: 102, name: "Bob", age: 17, role: "user", active: true },
  { id: 103, name: "Charlie", age: 34, role: "user", active: false },
  { id: 104, name: "Diana", age: 22, role: "user", active: true },
  { id: 105, name: "Ethan", age: 40, role: "admin", active: false }
];
```
1. Use filter() to create a new array containing only active users who are 18 years or older.
2. From the result of step (1), use map() to create a new array of objects containing only id and name.
3. Use find() to retrieve the active admin user from the original users array. If no active admin user is found, return null.
  
Each step should:
* Return a new value
* Leave the original users array unchanged
