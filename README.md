# :focus-visible pseudo-class browser compatibility issue

This repository demonstrates a common issue with the CSS `:focus-visible` pseudo-class and its lack of support in older browsers.  The `bug.css` file showcases the problem, while `bugSolution.css` provides a solution for broader compatibility.

## Problem

The `:focus-visible` pseudo-class is intended to improve accessibility by only styling elements when they receive focus in a way that is visible to the user (e.g., not when focus is programmatically set). However, older browsers don't support it, leading to styling issues and inconsistencies across platforms.  The bug example shows how styles are applied regardless of whether the focus is actually visually apparent.

## Solution

The solution employs a JavaScript-based fallback to detect focus visibility. This allows for consistent styling behavior across browsers, providing better cross-browser compatibility and accessibility.