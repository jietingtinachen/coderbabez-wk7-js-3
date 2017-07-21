# CoderBabez

##  Week Seven - Variables & Functions

### Objectives
Use variables and functions to add and remove puppy pictures on an html page.

### Vocab
* Variable
* Functions
* Parameters

### Review

A function is a reusable set of instructions

It looks like:
```
function functionName() {
  
}
```

You call a function to invoke it
```
functionName();
```

They can make something change
```
function changeBackground() {
  $('body').css('background', 'red');
}
```

They can return a value
```
function getColor() {
  return 'red';
}
```

They can be used together!
```
function changeBackground() {
  $('body').css('background', getColor());
}
```

They can take a parameter:
```
function changeBackground(colorName) {
  $('body').css('background', colorName);
}
changeBackground('red')
```

### Variables

Variables store data. They have a name you use to refer to the data.

We use the word `var` to declare the variable. We use the `=` to assign a value to the variable.

```
var x = 1;
var y = 2;
var z = 1 + 2;
```
What are the variables above? What are their values?


You can change the data that's in a variable
```
var x = 1;
x = 2;
```
What is the value of `x` in each line? How many times did we declare `x`? How many times did we assign a value to `x`?

You can pass variables to functions as parameters
```
function changeBackground(colorName) {
  $('body').css('background', colorName);
}
var color = 'red';
changeBackground(color);
```

### Project

Last week we used functions to update multiple things on a page at once. This week we're going to add a variable that keeps track of the state of the page.

Take a look at the live site:

* What are the html elements?
* What changes when the button is clicked?
* What stays the same between clicks?
* How would you go about implementing this page?

# Reference:

* https://www.w3schools.com/js/js_variables.asp
* https://www.w3schools.com/js/js_functions.asp
* https://api.jquery.com/click/
