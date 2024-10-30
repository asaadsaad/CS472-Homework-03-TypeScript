# CS472-Homework-03-TypeScript
## Exercise 01
1. Explain the difference between primitive types and object references in JavaScript.
2. What are the advantage for using TypeScript?
3. How can we run TypeScript code in the browser?
4. What are the differences between `let` and `const`? and what is their scope?
5. What is an IIFE and write a snippet code for one.

## Exercise 02
Create a TypeScript function that takes an array of numbers and returns the second largest number within that array.
```typescript
// Your function code here
console.log(secondLargest([20 ,120 ,111 ,215 ,54 ,78])); // Output: 120
```
Note: you may NOT use `Array.sort()`.
  
## Exercise 03
* Create a TypeScript function that takes an array of numbers and returns a new array containing the squares of each number (use `Array.map()`).
* Create a TypeScript function that takes an array of numbers and returns a new array containing all even numbers (use `Array.filter()`).

## Exercise 04
Create a TypeScript function that takes any number of arguments and returns their sum using the rest operator.

## Exercise 05
Given two arrays:
```typescript
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
```
Use the spread operator to concatenate them into a single array.

## Exercise 06
Create a TypeScript function that takes an object with the following properties: `name` (string), `age` (number), and `isStudent` (boolean). The function should return a string describing the person (use Template literals).
```typescript
interface Person {
    name: string;
    age: number;
    isStudent: boolean;
}

function describePerson(person: Person): string {
    // Your code here
}

const person: Person = { name: "Alice", age: 25, isStudent: true };
console.log(describePerson(person)); // Output: "Alice is 25 years old and is a student."
```
## Exercise 07
Create two TypeScript modules: one module contains 4 methods that calculate add, subtract, multiply, and divide between two numbers passed as parameters. The other module will import the calculator methods to test and print out the results. 
  
**Note:** Ensure your code is well typed and formatted.
