# General

JavaScript ES6 was released in 2015. Stands for ECMAScript 6, the organization ECMA International creates the standard.
JSON = JavaScript Object Notation, a data interchange format used to store data.


# DOM Manipulation

*Event Listeners*

`grandparent.addEventListener("click", e => {
    console.log(e);
})`

e = the event object, in other words, the mouse click. This is a callback function.

`let examples = document.querySelectorAll(".example")` will return a NodeList, not an array.
To get array, use `let examplesarray = Array.from(examples)`


# Pop up forms

Can show or hide a popup form in JS like this:

`document.getElementById("popupform").style.display = "block"; // makes form appear`
`document.getElementById("popupform").style.display = "none"; // makes form disappear`

# Buttons

Can disable a button after clicking, for example, or at end of process/game.
`document.getElementById("myBtn").disabled = true;`

# Methods

The array.forEach() method calls a provided callback function once for each element in an array.

The Object.keys() method returns an array of a given object's (or array's) own enumerable property names.
Can piggyback a forEach method on top. For example, `Object.keys(book).forEach(prop => {` 
returns an array of property names and initiates a callback function for each property.

# Factories and Modules

Factories are simply plain old JS functions that return objects for us to use in our code. Use a factory over and over to create multiple objects.

A function that lives on an object is called a *method*.

**this** refers to the object the thing is sitting on.

A module is like a factory except that it is wrapped in an IIFE (Immediately Invoked Function Expression).

# webpack

webpack is a JavaScript module bundler
*entry* is src (source) and *output* is dist (distribution)


