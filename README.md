# Uncommon CSS Specificity Bug: Inheritance and More Specific Selectors

This repository demonstrates an uncommon bug related to CSS specificity and inheritance. The issue arises when a more specific selector exists but is not considered by the `inherit` property.

The `bug.css` file contains the problematic CSS code, while `bugSolution.css` offers a solution to resolve the issue.

## Problem

The `inherit` keyword in CSS inherits styles from the parent element. However, it doesn't always consider the specificity of selectors. If a more specific selector exists that would otherwise override the parent's style, the `inherit` keyword might not apply this more specific selector.

## Solution

The solution involves understanding and applying the correct approach to handle CSS specificity and inheritance. In this case, we need to consider the impact of specificity on the `inherit` keyword.