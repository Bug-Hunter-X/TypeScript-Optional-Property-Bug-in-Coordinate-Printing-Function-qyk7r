# TypeScript Optional Property Bug

This repository demonstrates a common but subtle bug in TypeScript related to optional properties and type checking.  The `bug.ts` file contains code that attempts to print the x and y coordinates of a point. However, it fails to handle the case where the point object might be missing either x or y properties, leading to a runtime error.  The `bugSolution.ts` file provides a corrected version that properly handles optional properties using optional chaining and nullish coalescing.