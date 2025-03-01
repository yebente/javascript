# javascript

## Description
This is a JavaScript learning forlder that I will use to host different functions as I learn how to code in javascript.
## Table of Contents
1. [Variables and Data Types](#variables-and-data-types)
2. [Operators](#operators)
3. [Control Structures](#control-structures)
4. [Functions](#functions)
5. [Arrays and Objects](#arrays-and-objects)
## Variables and Data Types
### Variables
javascript
// declare a variable
let name = 'John Doe';
console.log(name); // John Doe
### Data Types
javascript
// declare a variable of type number
let age = 30;
console.log(age); // 30
javascript
// declare a variable of type string
let name = 'John Doe';
console.log(name); // John Doe
## Operators
### Arithmetic Operators
javascript
// declare variables
let a = 5;
let b = 3;
javascript
// add a and b
console.log(a + b); // 8
javascript
// subtract b from a
console.log(a - b); // 2
javascript
// multiply a and b
console.log(a * b); // 15
javascript
// divide a by b
console.log(a / b); // 1.6666666666666667
### Comparison Operators
javascript
// declare variables
let a = 5;
let b = 3;
javascript
// check if a is greater than b
console.log(a > b); // true
javascript
// check if a is less than b
console.log(a < b); // false
## Control Structures
### Conditional Statements
javascript
// declare variables
let age = 30;
javascript
// check if age is greater than or equal to 18
console.log(age >= 18); // true
### Loops
javascript
// declare variables
let numbers = [1, 2, 3, 4, 5];
javascript
// use a for loop to iterate over the numbers array
for (let i = 0; i < numbers.length; i++) {
    console.log(numbers[i]);
    javascript
    // use a for...of loop to iterate over the numbers array
    javascript
    for (const number of numbers) {
        console.log(number);
        }
        ### Functions
        javascript
        // declare a function that takes two parameters
        function add(a, b) {
            return a + b;
            }
            // call the add function with arguments 2 and 3
            console.log(add(2, 3)); // 5
            ### Object-Oriented Programming
            javascript
            // declare a class
            class Person {
                constructor(name, age) {
                    this.name = name;
                    this.age = age;
                    }
                    // declare a method
                    sayHello() {
                        console.log(`Hello, my name is ${this.name} and I am ${this.age}
                        javascript
                        ## Arrays
                        Arrays are a fundamental data structure in JavaScript. They are used to store collections of values, and can
                        be accessed and manipulated using various methods and properties.
                        ### Creating Arrays
                        javascript
                        // declare an array
                        let colors = ['red', 'green', 'blue'];
                        javascript
                        // declare an array with initial values
                        let numbers = [1, 2, 3, 4, 5];
                        ### Array Methods
                        Array methods are used to perform various operations on arrays, such as adding or removing elements, sorting,
                        and searching for specific values.
                        ### Adding Elements
                        javascript
                        // declare an array
                        let numbers = [1, 2, 3];
                        // add an element to the end of the array
                        numbers.push(4);
                        console.log(numbers); // [1, 2, 3, 4]
                        javascript
                        // declare an array
                        let numbers = [1, 2, 3];
                        // add an element to the beginning of the array
                        numbers.unshift(0);
                        console.log(numbers); // [0, 1, 2, 3]

            
        
    


