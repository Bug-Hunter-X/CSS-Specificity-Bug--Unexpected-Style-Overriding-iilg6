# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity.  The `bug.css` file contains CSS code where the intended styling is overridden due to a higher-specificity rule.  The `bugSolution.css` file demonstrates how to fix the issue.

## Bug Report

The bug is that expected styling is not applied because of conflicting styles with higher specificity. The solution modifies the CSS to ensure the intended style is applied correctly by adjusting specificity, possibly by adding more specific selectors or using the `!important` flag (used cautiously).