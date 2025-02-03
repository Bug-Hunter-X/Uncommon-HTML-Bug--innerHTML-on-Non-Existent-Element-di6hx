# Uncommon HTML Bug: innerHTML on Non-Existent Element

This repository demonstrates a subtle bug that can occur in HTML when attempting to modify the `innerHTML` property of an element that does not exist in the DOM.  This can lead to unexpected behavior and silent errors, as the JavaScript code might not throw an exception.

The `bug.html` file shows the incorrect implementation, while `bugSolution.html` provides the corrected version.  The solution involves first checking if the element exists before attempting any modifications.

This is an uncommon bug that can be easily overlooked but can be a significant source of frustration. Always validate if your targeted element exists in the DOM before performing manipulation.