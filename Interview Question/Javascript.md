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

## 15.  Which symbol is used for comments in Javascript?

```JAVASCRIPT
// This is a single comment

/*
This is a multi-line comment
*/
```

## 16. What is the difference between ViewState and SessionState?

__ViewState__  is specific to a page in a session.

__SessionState__  is specific to user-specific data that can be accessed across all web application pages.

## 17. What is === operator?

is called a strict equality operator, which returns true when the two operands have the same value without conversion.

```JAVASCRIPT
let num = 2;
let text = "2";

// let's compare these values
// note that their types are different

if(num === text){
    console.log("True");
} else {
    console.log("False");
}

// In this case the result will be False
// because of their are types are different that not means are equal
// So === will check even the data types

// what if i dont want to check the data types
// the you can use == instead of ===

if(num == text){
    console.log("True");
} else {
    console.log("False");
}

// In this case the result will be True

```

## 18.  How you can submit a form using JavaScript?

```JAVASCRIPT
// Select the from using the DOM element
var subForm = document.querySelector('.form');

// then submit by writing this code
subForm.submit();
```
## 19.  Does JavaScript support automatic type conversion?

Yes, JavaScript does support automatic type conversion. It is the common way of type conversion used by JavaScript developers

## 20. How can the style/class of an element be changed?

```JAVASCRIPT
// Select the element using the DOM element
var button = document.querySelector('.save_btn');

// then change the style by writing this code
button.style.backgroundColor = '#000000';
```

## 21. How to read and write a file using JavaScript?

There are two ways to read and write a file using JavaScript

1. Using JavaScript extensions.
2. Using a web page and Active X objects.

## 22.  What are all the looping structures in JavaScript?

Following are looping structures in Javascript:

1. For Looping
2. While Looping
3. Do While Looping

## 23. What is called Variable typing in Javascript?

Variable typing is used to assign a number to a variable. The same variable can be assigned to a string.

```JAVASCRIPT
var num = 1; // assign a number to a variable
var text = "hello world" // assign a string to a variable
```

## 24.  How can you convert the string of any base to an integer in JavaScript?

The parseInt() function is used to convert numbers between different bases. parseInt() takes the string to be converted as its first parameter. The second parameter is the base of the given string.

To convert 4F (or base 16) to integer, the code used will be –
```JAVASCRIPT
parseInt ("4F", 16);
```

## 25. Difference between “==” and “===”?

__==__ checks only for equality in value, whereas **===** is a stricter equality test and returns false if either the value or the type of the two variables are different.

## 26. What would be the result of 3+2+”7″?

Since 3 and 2 are integers, they will be added numerically. And since 7 is a string, its concatenation will be done. So the result would be 57.

## 27. How to detect the operating system on the client machine?

In order to detect the operating system on the client machine, the navigator. Platform string (property) should be used.

```JAVASCRIPT
let operatingSytem = navigator.appVersion; // Returns the operating system of the client machine
```

## 28. What do you mean by NULL in Javascript?

The NULL value is used to represent no value or no object. It implies no object or null string, no valid boolean value, no number, and no array object.

## 29. What is the function of the delete operator?

The delete keyword is used to delete the property as well as its value.

```JAVASCRIPT
// Assume we have this object
let objList = {
    Name: "Mansuur Abdullahi Abdirahman",
    Age: 23,
    Status: "Single",
    Phone: "252-617-608-849",
    Email: "mansuurtech101@gmail.com"
};

// Now let's use delete keyword to delete on item from object
delete objList.Email;
```