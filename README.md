# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS selector specificity. The `#special` element is intended to have a blue background, but due to a conflict in the specificity of CSS selectors, it renders with a different color. 

The solution shows how to adjust the specificity to resolve this issue.

## Bug
The `bug.css` file contains the erroneous CSS code. Observe the unexpected background color of the `#special` element.

## Solution
The `bugSolution.css` file shows a corrected version of the CSS where specificity is appropriately handled, resulting in the expected blue background for `#special` element.