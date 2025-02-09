# Tailwind CSS JIT Mode Compilation Error

This repository demonstrates a common issue encountered when using Tailwind CSS's Just-in-Time (JIT) mode.  The problem arises from typos in class names or the use of undefined classes, leading to styling errors that are not immediately apparent.  The solution involves careful code review and use of Tailwind's features to detect these issues early.

## Bug
The `bug.js` file contains a simple React component with a typo in the Tailwind CSS class name.  This causes the text to not be styled as expected.

## Solution
The `bugSolution.js` file corrects the typo in the class name, resolving the styling issue.  It also emphasizes the importance of using a linter that's aware of Tailwind class names, allowing for the early detection of similar issues.