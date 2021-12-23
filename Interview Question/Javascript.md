# Javascript Interview Questions

> The below list covers all the **JavaScript** questions for freshers and **JavaScript** interview questions for professional-level candidates. This JS interview questions guide will help you crack the interview and help you get your dream job for **JavaScript** Programming.

## 1. What is JavaScript?

JavaScript is a client-side ( Front-End ) and server-side ( Back-End ) scripting language inserted into HTML pages and is understood by web browsers. JavaScript is also an Object-based Programming language

**What is Object-based programming language?**

Object based languages supports the usage of object and encapsulation. They does not support inheritance or, polymorphism or, both. Object based languages does not supports built-in objects. Javascript, VB are the examples of object bases languages.

**What is encapsulation?**

is the process of combining data and functions into a single unit called class

## 2. Enumerate the differences between Java and JavaScript?

Java is an object-oriented programming (OOPS) or structured programming languages and is a complete programming language.

while javascript is a coded program that can be introduced to HTML pages and also is a client-side scripting language.

## 3. What are JavaScript Data Types?

1. Number
2. String
3. Boolean
4. Undefined
5. Object

## 4. What is the use of isNaN function?

__isNan__ function returns true if the argument is not a number; otherwise, it is false.

## 5. Which is faster between JavaScript and an ASP script?

JavaScript is faster. JavaScript is a client-side language,, and thus it does not need the assistance of the webserver to execute. On the other hand, ASP is a server-side language and hence is always slower than JavaScript. Javascript now is also a server-side language (nodejs).

## 6. What is negative Infinity?

Negative Infinity is a number in JavaScript which can be derived by dividing negative number by zero.

```JAVASCRIPT
// An example of negative Infinity
function checkNumber(number){
    if(number == Number.NEGATIVE_INFINITY){
        return "Number is an Infinity";
    } else {
        return "Number is not an Infinity";
    }
}

// Print The Result In The Console
console.log(checkNumber(2));
```

## 7.  Is it possible to break JavaScript Code into several lines?

Breaking within a string statement can be done by using a backslash, ‘\,’ at the end of the first line.

```JAVASCRIPT
let stringText = "My Javascript Skill Is Highly Motivated \And Well Organized";

// Print the result
console.log(stringText);
```

And if you change to a new line when not within a string statement, then javaScript ignores the break in the line.

## 8. Which company developed JavaScript?

Netscape is the software company that developed JavaScript.

## 9. What are undeclared and undefined variables?

Undeclared variables are those that do not exist in a program and are not declared. If the program tries to read the value of an undeclared variable, then a runtime error is encountered.

Undefined variables are those that are declared in the program but have not been given any value. If the program tries to read the value of an undefined variable, an undefined value is returned.

## 10.  Write the code for adding new elements dynamically?

```HTML
<html>
<head>
    <title>Adding new elements dynamically</title>
</head>

<body id="bodyID">
    <script type="text/javascript">
        let bodyID = document.querySelector('#bodyID');

        // Create H1 Element And Bind It To The Body Tag
        let h1_el = document.createElement('h1');
        h1_el.textContent = "Element Created Dynamically";
        bodyID.appendChild(h1_el); 
    </script>
</body>
</html>
```

## 11.  What are global variables? How are these variable declared?

Global variables are available throughout the length of the code so that it has no scope. The var keyword is used to declare a local variable or object. If the var keyword is omitted, a global variable is declared.

```JAVASCRIPT
// Use the var keyword to create a global variable
// Note that this variable can be used multiple times in your entire code
var global_variable = 123; 
```

The problems faced by using global variables are the clash of variable names of local and global scope. Also, it is difficult to debug and test the code that relies on global variables.

## 12. What is a prompt box?

A prompt box is a box that allows the user to enter input by providing a text box. A label and box will be provided to enter the text or number.

## 13. What is ‘this’ keyword in JavaScript?

**This** keyword refers to the object from where it was called.

## 14. What is the working of timers in JavaScript?

Timers are used to execute a piece of code at a set time or repeat the code in a given interval. This is done by using the functions __setTimeout__, __setInterval__, and clearInterval.

The setTimeout(function, delay) function is used to start a timer that calls a particular function after the mentioned delay. The setInterval(function, delay) function repeatedly executes the given function in the mentioned delay and only halts when canceled. The clearInterval(id) function instructs the timer to stop.

Timers are operated within a single thread, and thus events might queue up, waiting to be executed.