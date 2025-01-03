# Uncommon HTML Bug: Typo in DOM Manipulation

This repository demonstrates a subtle bug in HTML that involves a simple typo in JavaScript code used for DOM manipulation. The bug is easily overlooked, highlighting the importance of careful coding practices.

## Bug Description
The bug lies in the JavaScript code within the HTML file.  The developer mistakenly uses `document.getElementByIdx()` instead of the correct `document.getElementById()`. This incorrect method will fail silently, and there will be no apparent error messages, but the intended DOM manipulation does not occur. This creates a frustrating and potentially hard-to-debug scenario, particularly for beginners.  The solution demonstrates the correct method and the expected outcome.

## Bug Solution
The solution is simple: using the correct function call.  The updated code uses the standard method of `document.getElementById()` to correctly target the element and update its `innerHTML` property. 

## How to Run
1. Clone this repository.
2. Open `bug.html` in your web browser to observe the bug.
3. Open `bugSolution.html` to see the corrected code and expected behavior.
