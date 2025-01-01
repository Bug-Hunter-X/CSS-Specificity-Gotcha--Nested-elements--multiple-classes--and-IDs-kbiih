# CSS Specificity Issue: Unexpected Color Inheritance

This repository demonstrates a subtle issue related to CSS specificity.  The problem involves understanding how selectors with different levels of specificity interact, especially when dealing with nested elements and elements having multiple classes and IDs. 

The `bug.css` file contains CSS code with the unexpected behavior. The `bugSolution.css` shows the corrected code and explains the fix.

## Problem
The main issue is the unexpected color inheritance or overriding of styles due to incorrect assumptions about CSS specificity. The primary goal is to understand which rule applies to a given element and why.  The behavior may be non-obvious for developers not completely familiar with CSS specificity rules.

## Solution
The solution file, `bugSolution.css`, provides a clearer way to style elements, ensuring that the expected style is applied. This solution involves careful consideration of CSS selector specificity to correctly control style inheritance.