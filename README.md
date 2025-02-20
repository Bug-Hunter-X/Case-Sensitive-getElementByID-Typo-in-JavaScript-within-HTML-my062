# Case-Sensitive getElementByID Typo in JavaScript within HTML

This repository demonstrates a common, yet easily overlooked, error in HTML: a case-sensitive typo in JavaScript's `getElementById` method.

## Bug Description
The bug lies in a simple typo within the JavaScript code embedded in the HTML.  Instead of the correct `getElementById`, it uses `getElementByID`, causing the script to fail silently without modifying the HTML element.  This kind of error can be difficult to track down, especially in larger projects.

## Bug Solution
The solution involves correcting the typo, ensuring that the method name is correctly cased as `getElementById`.

## How to reproduce the bug
1. Clone this repository.
2. Open the `bug.html` file in a web browser. 
3. Observe that the text within the div element is not modified.

## How to fix the bug
1. Open the `bugSolution.html` file in a web browser.
2. Notice that the text within the div element is now correctly modified.