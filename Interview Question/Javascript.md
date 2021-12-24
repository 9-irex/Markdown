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

## 30. What is an undefined value in JavaScript?

Undefined value means the

1. Variable used in the code doesn’t exist
2. Variable is not assigned to any value
3. Property does not exist.

## 31. What are all the types of Pop up boxes available in JavaScript?

1. Alert
2. Confirm and
3. Prompt

## 32. What is the use of Void (0)?

Void(0) is used to prevent the page from refreshing, and parameter “zero” is passed while calling.

Void(0) is used to call another method without refreshing the page.

## 33. How can a page be forced to load another page in JavaScript?

The following code has to be inserted to achieve the desired effect:

```JAVASCRIPT
window.location.href = "/index.html";
```

## 34. What is the data type of variables in JavaScript?

All variables in JavaScript are object data types.

## 35. What is the difference between an alert box and a confirmation box?

An alert box displays only one button, which is the OK button.

But a Confirmation box displays two buttons, namely OK and cancel.

## 36. What are escape characters?

Escape characters (Backslash) is used when working with special characters like single quotes, double quotes, apostrophes, and ampersands. Place backslash before the characters to make it display.

```JAVASCRIPT
document.write = "I m a "good" boy."
document.write =  "I m a \"good\" boy."
```

## 37. What are JavaScript Cookies?

Cookies are the small test files stored in a computer, and they get created when the user visits the websites to store information that they need. Examples could be User Name details and shopping cart information from previous visits.

## 38. What a pop() method in JavaScript is?

The pop() method is similar to the shift() method, but the difference is that the Shift method works at the array’s start. The pop() method takes the last element off of the given array and returns it. The array on which it is called is then altered.

```JAVASCRIPT
var cloths = ["Shirt", "Pant", "TShirt"];
cloths.pop();
//Now cloth becomes Shirt,Pant
```

## 39. Does JavaScript has concept level scope?

No. JavaScript does not have concept-level scope. The variable declared inside the function has scope inside the function.

## 40. What are the disadvantages of using innerHTML in JavaScript?

If you use innerHTML in JavaScript, the disadvantage is

1. Content is replaced everywhere
2. We cannot use it like “appending to innerHTML
3. Even if you use +=like “innerHTML = innerHTML + ‘html'” still the old content is replaced by html
4. The entire innerHTML content is re-parsed and builds into elements. Therefore, it’s much slower
5. The innerHTML does not provide validation, and therefore we can potentially insert valid and broken HTML in the document and break it

## 41. What is break and continue statements?

Break statement exits from the current loop.

Continue statement continues with next statement of the loop.

## 42. What are the two basic groups of data types in JavaScript?

1. They are as—Primitive.
2. Reference types.

Primitive types are number and Boolean data types. Reference types are more complex types like strings and dates.

## 43. How can generic objects be created?

Generic objects can be created as:

```JAVASCRIPT
var I = new object();
```

## 44. What is the use of a type of operator?

**Typeof** is an operator used to return a string description of the type of a variable.

## 45. Which keywords are used to handle exceptions?

Try… Catch—finally is used to handle exceptions in the JavaScript.

```JAVASCRIPT
try{
    Code
}
catch(exp){
    Code to throw an exception.
}
finally{
    Code runs either it finishes successfully or after catch
}
```

## 46. Which keyword is used to print the text on the screen?

Document.Write (“Welcome”) is used to print the text–Welcome on the screen.

```JAVASCRIPT
document.Write("Hello World");
```

## 47. What is the use of the blur function?

Blur function is used to remove the focus from the specified object.

## 48. What is variable typing?

Variable typing assigns a number to a variable and then assigns a string to the same variable. An example is as follows:

```JAVASCRIPT
i = 8;
i ="john";
```

## 49. How to find an operating system in the client machine using JavaScript?

The Navigator. the app version is used to find the operating system’s name in the client machine.

## 50. What are the different types of errors in JavaScript?

There are three types of errors:

1. **Load time errors**: Errors that come up when loading a web page, like improper syntax errors, are known as Load time errors and generate the errors dynamically.
2. **Runtime errors**: Errors that come due to misuse of the command inside the HTML language.
3. **Logical Errors**: These are the errors that occur due to the bad logic performed on a function with a different operation.