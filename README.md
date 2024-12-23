# Uncommon HTML Bug: Accessing Non-Existent DOM Properties

This repository demonstrates a common yet easily missed error in HTML: attempting to access a non-existent property of a DOM element.  This can lead to unexpected errors and crashes in the browser's JavaScript console.

The `bug.html` file contains the problematic code, while `bugSolution.html` demonstrates the correct approach.

## Bug Description
The script in `bug.html` tries to access a property ('someNonExistentProperty') that does not exist on the 'myDiv' element. This results in a `TypeError` being thrown by the browser.

## Solution
The solution (`bugSolution.html`) demonstrates the correct way to access properties of DOM elements and handles the potential for undefined properties using optional chaining or checking for their existence before accessing them.