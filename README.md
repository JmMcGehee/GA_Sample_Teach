# GA_Sample_Teach

## Lesson Objectives

After this lesson, your should be able to: 
  1. Declare a function in JavaScript.
  2. Call ("invoke" or "run") that function. 

### What you'll need:
  1. Some understanding of what JavaScript is (know that it's a coding language -- having some exposure to variables, data types, and `consol.log()` wouldn't hurt).
  2. Access to a coding enviroment, like [CodePen](https://codepen.io/pen/) or a Browser (`Command + Option + J` for Mac or `Control + Shift + J` for Windows)

## Lesson/Example:

#### Q. What is a function? 
A. A way to save lines of code and deploy when needed. Functions also help to breakdown code into reusable pieces.

Say we want to get the console to say hello to us, we could just type this command into the console: 
```javascript
console.log("Hello Joshua")
```
That imediately prints to the console: 

![Screen Shot 2022-06-12 at 7 12 04 PM](https://user-images.githubusercontent.com/45159628/173262664-93bbf98f-4a30-4a36-a86a-e710f25da308.png)

### DECLARE the function

Though we've been successful, this wasn't very useful because it only ran once. Instead let's write a function that will allow us to use this code whenever we need. 

```javascript
const sayHello = function() {
  console.log("Hello, Joshua")
}
```

### CALL the function

If we add this to the console, it looks like nothing happens. But that's not the case. The browser has stored our code in the constant `sayHello`. To access it, we just need to call or invoke the function. We do this by typing the name of the function with some parenthesis, so 

```javascript
sayHello()
```

And this is our output. 

![Screen Shot 2022-06-12 at 7 19 54 PM](https://user-images.githubusercontent.com/45159628/173263153-a069e6c1-d9d3-4817-91ba-80ecf5d900ab.png)

Now we can acces this function whenever we need. 

### Make it REUSABLE

You might see different ways of declaring functions: 

```javascript
function sayGoodBye() {
  console.log("Goodbye, " + name)
}
```

![Screen Shot 2022-06-12 at 7 28 30 PM](https://user-images.githubusercontent.com/45159628/173263794-9d99e9b7-680c-4d9a-b6a1-23a33ce0b9a3.png)

### Add a PARAMETER

If we wan a function to work for any name we put in, we can add a parameter. A parameter serves a placeholder for any value we want the function to work with: 

```javascript
function sayMyName(myName) {
  console.log("Hello, " + myName)
}
```

![Screen Shot 2022-06-12 at 7 30 22 PM](https://user-images.githubusercontent.com/45159628/173263931-631a599b-28ac-4003-bfbb-8411b3b579bd.png)

## Exercise: 

  1. DECLARE a function that prints your name (or anything you want) to the console. 
  2. CALL that function. 
  
*Extra Credit*: Make the function REUSABLE

*Extra Extra Credit*: Write a function that takes a PARAMETER.

*Extra Extra Extra Credit*: Write a function what uses the parameters `firstName` and `lastName`.


## Further Learning

[Mozzilla Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
[You Don't Know JS](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/README.md)

### Instructor notes 

[Code on CodePen](https://codepen.io/JMcGehee/pen/poaqNdv)


