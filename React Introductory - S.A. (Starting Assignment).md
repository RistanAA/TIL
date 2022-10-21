# Starting Assignment
### What are the characteristics of JavaScript - data type and JavaScript?
* loosely typed dynamic language is we dont need to specify the data type when we declare variable like in javascript 'let' can be use to any data type.
* JavaScript Type Casting is to convert or parsing data type to another data type in javascript.
* (==, ===) is comparison operator to determine equality or difference between variables. the '==' operator mean it will compare the equality of variables by ignoring the data type but '===' will comparing identically with value and data type (5 === "5" it will return false because it has different type).

#### What is the problem of a loosely typed dynamic language, and what are the ways to supplement it?
When i google it i found that back in 2005, there are many discussion about the dengerous about the security but too much evidence exists to the contrary. regardless of language type, we must makes our code safe and make sure you apply that to all our development.

#### Difference between undefined and null
* we got 'undefined' when we try to call the variable that doesn't exist
* we got 'null' when we call the variable but doesn't have value

### What is JavaScript object and Immutability?
* Primitive type data is the data type it doesn't have any object or methods exemple (numbers, strings, booleans, null, and undefined)
* Reference type data is unlike primitive data types, they are dynamic in nature. So they do not have a fixed size, most of them are considered as objects, and therefore have methods example(arrays, functions, collections, and all other types of objects).

#### How to make Immutable Object?
We can freeze (make immutable) an object using the function Object.freeze(obj). The object passed to the freeze method will become immutable. The freeze() method also returns the same object.

#### What are shallow copy and deep copy. What are the differences?
* shallow copy is where a new object is created and it has the same copy of the values in the original object, If any of the object fields refer to the other object then in such cases only the reference address is copied. It stores references of the object in the main memory. The changes made in the copied object also reflect the original object.
* deep copy is When the process of copying occurs repetitively and a copy of the object is always copied in another object. There is no reflection on the original object when the changes are made in the copied object. 

### Hoisting and TDZ
* Scope is the area of code
* Hoisting is mechanism where variables and function declarations are moved to the top of their scope before code execution. Inevitably, this means that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local.
* TDZ(temporal dead zone) is the area of a block where a variable is inaccessible until the moment the computer completely initializes it with a value.

* Different ways of hoisting in Function Declarations and Function Expressions. 
  * Function declarations are executing on compilation phase ( Function declarations load before any code is executed )
  * Function expressions are executing on execution phase of JS engine ( Function expressions load only when the interpreter reaches that line of code )

* Execution Context is an environment in which a piece of JavaScript is executed. It stores all the necessary information for some code to be executed, such as local variables or arguments passed into a function.

![image](https://user-images.githubusercontent.com/85722211/197224040-a72549d6-7c03-44ba-bd5e-cd03d0a51a6d.png)


* Call Stack is place where execution contexts get stacked on top of each other, in order to keep track of where we are in the program’s execution (the order of execution).

![image](https://user-images.githubusercontent.com/85722211/197223968-428ff327-1b85-4e8c-a2d0-ca1e5d49c715.png)

* Scope Chain means that one variable has a scope (it may be global or local/function or block scope) is used by another variable or function having another scope (may be global or local/function or block scope). This complete chain formation goes on and stops when the user wishes to stop it according to the requirement.
* In terms of programming, information hiding refers to the practice of concealing implementation details that are unfit for the consumers of the code. the consumers would be the other developers and end user.


#### Exercise
```javascript
let b = 1;

function hi () {

const a = 1;

let b = 100;

b++;

console.log(a,b);

}

//console.log(a);

console.log(b);

hi();

console.log(b);
```

* What would be the “b” value printed on the console? the value is 1 and b in hi function is 101
* Which “b” value would be printed from which line of console.log? Explain why. it will use the global declared at first line, not 'b' in hi function, because console.log called outsite the hi function.
* What would be `//console.log(a);` in the comment? If there’s an error, explain why and fix the error. the error is caused by we call a at outsite the hi function, because variable a was declared in hi function, so we just declared a at global scope and it will fix the error
