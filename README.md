# JAVASCRIPT INTERVIEW

**What is JavaScript?**
Javascript is a high dynamic shingle threaded programming language that is to create interactive eb effects with in a browser.

**What is High Level Programming Language?**
A high-level programming language is human-readable code that is translated into machine instructions and interacts with the operating system kernel indirectly—primarily through system calls when a program needs hardware or OS resources.

**What is Template literals?**
when we combine `$` sign, `` and `{}` in together with in a string. 

**What is Hoisting?**
unlike other programming language For example Python if we call function Before its definition It will throw an error But in JavaScript it will actually run And this phenomena is called hoisting. in hoist function or variable Loop to the top of the scope before execution. two type of hoisting is available One is for functional hosting another is called variable hosting.

**What are the main difference between late var and const?**
In Javascript let, var and const both are used to initialize variable, main difference are in case of var we can assign value after it's initialization but it will always hoist it to the top of the scope, where in let we can can do the same but it will not moving top of the scope, in case of cost as the name suggest it's constant so once we define after we can't change the value of it.

**What are the data types in Javascript?** 
In Javascript we have two datatypes avaible these are premtive and non-primtive.

| Primtive | Non Primtive 
| :--- | :---: | ---: |
| String | Object
| Symbol | Array
| Number | Function
| Null 
| Boolean 
| Bigint 
| Undefined  

**What is an array in JavaScript and How we can access its element?**
in Javascript array is an linear data structure it is a order collection of list that is use to store multiple values of a same type. To access the array element's we need to use it's index.

**What is the purpose of the isNAN function?**
as the name suggest NAN stands for Not a number, so it is use to check whether the value is number or not if not then it will give us true otherwise false.

**What is the use of typeOf?**
typeOf is a special keyword in JavaScript that is use to check datatype.

**What are null and undefined?**
Null is something when user need to assign a value Intentional absence perpose. And undefined is something basically it's a default datatype in Javascript, when user forgot to assign an value to a variable then undefined assigned automatically

**What are the purpose of Map method?**
map method is for iterational operation in an array, but it replicate the actual array that it wouldn't change the actual array.

**What are event bubbling and event capturing?**
Event bubbling and event capturing both are propagation technique in Javascript The main difference is in event bubbling event handles innermost element to outermost element And in event capturing event handels from outermost element to innermost element.

**What are higher order function?**
when a function accepts another function as an argument or return as result.

**What is an IIFE?**
As the name suggest IIFE is stands for Immediately Invoked Function Expression. it executes after its definition no need to call it seperately.

**What is closure?**
Closer is a concept in Javascript to hide data, in which fashion the code was actually written Inner function should memorise the outer function's scope, even after outer function got executed.

**How do setTimeout and setInterval works?**
Both setTimeout and setInterval are JavaScript Web APIs used for scheduling asynchronous tasks. setTimeout executes a callback function once after a specified delay, whereas setInterval executes a callback function repeatedly after a specified time interval until it is explicitly stopped using clearInterval.

**What is promise?**
A promise is a Javascript object that represents a value that might be ready for now or later, It has three states Pending, Resolve and Reject.

**What is the use of async and await?**
async and await both are part of javascript web api's, if we define any function with async keyword then the function must return a promise. and await is something for asyncronous task it will block the whole code untill promise meet it's resolve or reject state.

**What are the purpose of call bind apply method?**
-   `call()` = Execute with individual arguments.
-   `apply()` = Execute with array arguments.
-   `bind()` = Create a new function for later execution.

**What is event delegation?**
It is a technique where we attach a single event listener to a parent element instead of attaching separate event listeners to each child element.