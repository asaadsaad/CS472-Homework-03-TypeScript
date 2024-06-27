# CS472-Homework-03-TypeScript
## Exercise 01
1. Explain the difference between primitive types and object references in JavaScript.
2. Write a code snippet demonstrating how changing the value of a property in an object affects all references to that object.

## Exercise 02
Create a TypeScript function that takes an array of numbers and returns a new array with each number squared.
```typescript
// Your function code here
console.log(squareNumbers([1, 2, 3, 4])); // Output: [1, 4, 9, 16]
```
## Exercise 03
* Create an array of numbers and use the map function to create a new array containing the squares of each number.
* Create an array of numbers and use the filter function to create a new array containing all even numbers.

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
Define a TypeScript function that takes an object with the following properties: `name` (string), `age` (number), and `isStudent` (boolean). The function should return a string describing the person (use Template literals).
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
Create two TypeScript modules: one for a Calculator 4 methods add, subtract, multiply, and divide, and another for using this Calculator methods to perform a calculation. 
  
**Note:** Ensure your code is well typed and formatted.
