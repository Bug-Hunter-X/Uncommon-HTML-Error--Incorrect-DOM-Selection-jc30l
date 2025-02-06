# Uncommon HTML Error: Incorrect DOM Selection

This repository demonstrates a subtle but common error when working with JavaScript and the Document Object Model (DOM) in HTML.

The bug involves incorrect syntax in selecting an element using `document.getElementById()`.  The solution showcases the correct method and explains the cause of the error.

## Bug

The `bug.html` file shows incorrect DOM selection. The JavaScript attempts to select the element with id "myDiv", but incorrectly omits the '#' character. This results in `document.getElementById()` returning null, causing a runtime error when attempting to modify the element's `innerHTML`.

## Solution

The `bugSolution.html` file demonstrates the corrected code.  The correct syntax for selecting elements by ID is to include the '#' before the ID name.