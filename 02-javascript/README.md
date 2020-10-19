# Part II: JavaScript - Adding Interactive features

## Terminologies

### Programming language
A **programming language** is a formal language, which comprises a set of instructions that produce various kinds of output. ([Wikipedia](https://en.wikipedia.org/wiki/Programming_language))

### JavaScript
**JavaScript**, often abbreviated as **JS**, is a programming language that conforms to the ECMAScript specification. ([Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### ECMAScript
**ECMAScript** (or **ES**) is a scripting-language specification standardized by Ecma International. ([Wikipedia](https://en.wikipedia.org/wiki/ECMAScript))

## Getting ready for JavaScript

### JavaScript Console

In Google Chrome, go to View > Developer > Developer Tools, then go to the *Console* panel.

![Chrome Devtools - Console](images/chrome-devtools-console.png)

Console is where JavaScript code can output information with `console.log();`. It is a place where developers can monitor what is going on in the code. We can even enter JavaScript code here directly to see real-time results, but **code entered here is only temporary and will not be saved**.

### Adding JavaScript to HTML

Similar to CSS, there are two ways to add JavaScript to HTML.

#### Internal 
```html
<!DOCTYPE html>
<html>
  <body>
    // put your HTML code here
    <script>
      // put your JavaScript code here
    </script>
  </body>
</html>
```

#### External

```html
<script src="path/to/javascript.js"></script>
```

## Introduction to Programming

### Variables

In JavaScript, we use `let` to declare a variable and `const` to declare a variable that will not be reassigned.

```javascript
let views = 0;
const USERNAME = 'jack';
```

![let and const](images/variables-let-and-const.png);

In the above example, `views` and `USERNAME` are the __names__ of the variables, and `0` and `'jack'` are the __values__ of the variables.

- JavaScript let: [https://www.w3schools.com/js/js_let.asp](https://www.w3schools.com/js/js_let.asp)
- JavaScript const: [https://www.w3schools.com/js/js_const.asp](https://www.w3schools.com/js/js_const.asp)

#### Data types

In JavaScript, a variable can hold a number, string, and Boolean, etc.

```javascript
let age = 20;
let name = "John Doe";
let isStudent = true;
```

- JavaScript data types: [https://www.w3schools.com/js/js_datatypes.asp](https://www.w3schools.com/js/js_datatypes.asp)
- JavaScript data types and data structures: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)

### Operators

#### Arithmetic operators

One of the most basic operations you can do in JavaScript is arithmetic operations, namely, addition (`+`), substraction (`-`), multiplication (`*`), and division (`/`), etc.

```javascript
let a = 10;
let b = 5;
let c = a + b; // the value of 15 (the sum of a and b) is assigned to the variable c
```

![Addition Example](images/operators-addition-example.png);

#### Assignment operators

We have been using the simple assignment operator (`=`) since the beginning of this workshop, which assigns the value of its right operand to its left operand. But there are more.

```javascript
let x += y; // same as let x = x + y;
let x -= y; // same as let x = x - y;
let x *= y; // same as let x = x * y;
let x /= y; // same as let x = x / y;
```

#### String operators

We can use the concatenation operation (`+`) to concatenate two string values.

```javascript
let firstName = 'John';
let lastName = 'Doe';
let fullName = firstName + ' ' + lastName; // the string value 'John Doe' is assigned to fullName
```

![Concatenation Example](images/operators-concatenation-example.png)

#### Comparision operators

We can use comparision operators to compare two values and it returns a Boolean value based on whether or not the comparsion if true.

```javascript
let a = 2;
let b = 3;
let c1 = (a == b)  // Boolean value false is assigned to c1
let c2 = (a != b)  // Boolean value true is assigned to c2
let c3 = (a > b)   // Boolean value false is assigned to c3
let c4 = (a < b)   // Boolean value true is assigned to c4
```

#### Logical operators

Logical operators are used with Boolean values. There are logical AND (`&&`), logical OR (`||`), and logical NOT (`!`).

```javascript
let a1 = true && true;          // Boolean value true is assigned to a1
let a2 = true && false;         // Boolean value false is assigned to a2
let b1 = true || false;         // Boolean value true is assigned to b1
let b2 = false || false;        // Boolean value false is assigned to b2
let c1 = !true;                 // Boolean value false is assigned to c1
let c2 = !false;                // Boolean value true is assigned to c2
let d1 = (3 > 2) || !(2 == 2);  // Boolean value true is assigned to d1
let d2 = (3 > 2) && !(2 == 2);  // Boolean value false is assigned to d2
```

There are many more types of operators. You can check them out in the links below.

- JavaScript operators: [https://www.w3schools.com/js/js_operators.asp](https://www.w3schools.com/js/js_operators.asp)
- JavaScript expressions and operators: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

### DOM

#### innerHTML

#### style

### input

### for loop

### conditionals

### arrays

## Other resources

- JavaScript style guide and coding conventions: [https://www.w3schools.com/js/js_conventions.asp](https://www.w3schools.com/js/js_conventions.asp)
- Airbnb JavaScript Style Guide: [https://github.com/airbnb/javascript](https://github.com/airbnb/javascript)

## Suggested homework

- Make a simple game with all that you have learned
- It does not need to be a conventional video game, be creative!
- Note down your questions and bring them to the next workshop
- Of course, also bring your game to the next workshop so we can all have some fun together
