# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS selector specificity.  The issue arises from conflicting selectors where a more specific selector overrides a more general selector, resulting in unexpected styling.

The `bug.css` file contains the buggy CSS code. The `bugSolution.css` provides the corrected CSS that addresses the specificity issue.

**Problem:**
The intended behavior is to style all list items (`<li>`) within unordered lists (`<ul>`) with blue text. However, due to the more specific selector `.container ul li`, the list items within a container with the class `container` are styled red, overriding the general styling.

**Solution:**
The solution involves carefully reviewing and adjusting selector specificity to ensure the intended styling is applied correctly.  This can often involve restructuring CSS or using more precise selectors.