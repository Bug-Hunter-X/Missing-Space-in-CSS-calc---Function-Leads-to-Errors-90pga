# Missing Space in CSS calc() Function

This repository demonstrates a subtle but important error in using the `calc()` function in CSS.  Forgetting to include spaces around operators within the `calc()` function can lead to unexpected results or parsing errors.  The example provided shows the incorrect and correct usage, highlighting the importance of proper spacing.

## How to reproduce

1. Open `bug.css` and observe the incorrect use of `calc()`. 
2. Open `bugSolution.css` and observe the corrected version.
3. Compare the rendered output to see the effect of the missing space. 

## Resolution

Always ensure there's a space before and after operators (+, -, *, /) within the `calc()` function to prevent unexpected behavior.