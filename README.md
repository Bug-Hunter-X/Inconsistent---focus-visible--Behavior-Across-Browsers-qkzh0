# Inconsistent `:focus-visible` Behavior Across Browsers

This repository demonstrates a common issue with the CSS `:focus-visible` pseudo-class. The goal is to style focused elements only when the focus is programmatically set (e.g., by a screen reader). However, consistent behavior is not always achieved across different browsers and assistive technologies.

The `focusBug.css` file contains the problematic CSS that shows inconsistent styling. The `focusSolution.css` file offers potential fixes and workarounds to address cross-browser compatibility.

## How to Reproduce

1. Clone this repository.
2. Open `index.html` (you'll need to create a simple HTML file to test the CSS) in different browsers (Chrome, Firefox, Safari, Edge).
3. Observe how the styling of the focused element varies across browsers.
4. Compare the original CSS in `focusBug.css` with the potential solutions in `focusSolution.css`.