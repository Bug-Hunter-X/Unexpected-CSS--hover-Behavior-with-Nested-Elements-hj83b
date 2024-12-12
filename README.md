# CSS Specificity Bug: Unexpected :hover Behavior

This repository demonstrates a subtle bug related to CSS specificity and the `:hover` pseudo-class when dealing with nested elements. The hover state is unexpectedly overridden due to specificity conflicts.

## Bug Description

The goal is to style list items in a navigation menu.  The list items should have a white background, which changes to light blue on hover. Links within the list items should have a black color that changes to dark blue on hover.

However, due to specificity issues, the hover effect on the list item is unexpectedly overridden.

## Solution

The solution involves adjusting the specificity of the selectors to ensure the desired hover effects are applied correctly. This usually involves making the selector for the list item hover more specific.