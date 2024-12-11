# Uncommon HTML Bug: Asynchronous DOM Manipulation

This repository demonstrates an uncommon bug related to asynchronous DOM manipulation in HTML. The bug occurs when a script attempts to modify a DOM element before the element is fully loaded into the DOM.

## Bug Description
The script attempts to change the `innerHTML` and the `style.display` of the element with id `myDiv`. However, the order of execution is not properly handled which can cause the second modification to be skipped or fail.