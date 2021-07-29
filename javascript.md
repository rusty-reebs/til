# General

JSON = JavaScipt Object Notation, a data interchange format used to store data


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

A function that lives on an object is called a *method*.

**this** refers to the object the things is sitting on.
