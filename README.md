# CSS Specificity and !important Bug

This repository demonstrates an uncommon bug related to CSS specificity and the `!important` declaration.

The bug occurs when a more specific selector overrides a style declared with `!important`.  This unexpected behavior can be difficult to debug if you're not familiar with CSS specificity rules.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` in your preferred text editor.
3. Observe the unexpected color of the `.child` element within the `.parent` element.  It will be green instead of red. 
4. Open `bugSolution.css` to see a possible solution.

## Solution

Review the solution file, `bugSolution.css`, to see how we handle specificity more carefully.