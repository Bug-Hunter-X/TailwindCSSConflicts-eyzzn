# Tailwind CSS Style Conflicts

This repository demonstrates a common issue encountered when using Tailwind CSS: conflicting styles that lead to unexpected behavior.  The `bug.js` file contains example code that exhibits the problem. The `bugSolution.js` file provides a solution by clarifying the order of styles or resolving the conflict.

## Problem
The hover effect on a button element is not working as expected due to conflicting Tailwind CSS classes. The `bg-red-500` and `hover:bg-blue-700` classes are causing an unexpected visual outcome.

## Solution
The solution involves addressing the style conflict by either prioritizing one style over another or modifying the styles to work together harmoniously.