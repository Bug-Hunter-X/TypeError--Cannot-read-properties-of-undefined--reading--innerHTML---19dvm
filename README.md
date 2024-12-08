# Uncommon HTML Bug: TypeError from accessing undefined object property

This repository demonstrates a common yet easily overlooked error in JavaScript code within an HTML file.  The bug arises from attempting to access a property of an object that is undefined.

## Bug Description
The provided `bug.html` file contains a script that tries to access the `nonExistentProperty` of the `myDiv` element *before* checking if the element exists or has the property.