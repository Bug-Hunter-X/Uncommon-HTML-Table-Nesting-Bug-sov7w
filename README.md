# Uncommon HTML Table Nesting Bug

This repository demonstrates an uncommon HTML bug related to incorrect element nesting within a table.  Specifically, it shows the problem of placing a `div` element within a `td` (table data) cell that also contains other content like paragraphs.

This often leads to unexpected layout differences and inconsistencies across different browsers. The solution emphasizes the correct semantic use of HTML table elements and avoids unnecessary nesting.

## Bug
The `bug.html` file showcases the buggy code. Note how the `div` is inappropriately placed within the `td` element.

## Solution
The `bugSolution.html` file presents a corrected version that avoids the issue and promotes semantically clean HTML.