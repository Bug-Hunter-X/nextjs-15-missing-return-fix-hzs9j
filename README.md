# Missing Return Statement in Next.js 15 Page Component

This repository demonstrates a common error in Next.js 15: forgetting to include an explicit `return` statement in a page component.  Next.js 15, unlike previous versions, requires explicit return statements for page components to function correctly.  This change aims to improve type safety and code predictability.

The `bug.js` file shows the problematic code. The `bugSolution.js` file presents the corrected code. This is a simple example, but in larger applications, this error can be difficult to debug.