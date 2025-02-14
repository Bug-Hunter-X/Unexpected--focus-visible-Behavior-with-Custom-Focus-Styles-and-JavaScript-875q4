# Unexpected :focus-visible Behavior with Custom Focus Styles and JavaScript

This repository demonstrates a subtle bug involving the CSS `:focus-visible` pseudo-class, custom focus styles, and JavaScript focus management.

## The Problem

The `:focus-visible` pseudo-class is designed to show focus indicators only when the focus is programmatically noticeable to the user.  However, adding custom focus styles via JavaScript can sometimes interfere with this functionality. This results in focus indicators appearing even when they shouldn't be visible.

## Reproducing the Bug

1. Clone this repository.
2. Open `index.html` in your browser.
3. Observe the behavior of the focus indicator on the button element.

## Solution

The provided solution demonstrates a more robust approach to managing focus styles that ensures compatibility with `:focus-visible`. This may involve carefully structuring CSS rules or using techniques that prioritize `:focus-visible` styles. Check `bugSolution.css` for more details.

## Note

This issue highlights the complexities of implementing accessible and visually appealing focus indicators. Careful consideration of how `:focus-visible` interacts with other styles and JavaScript is essential.