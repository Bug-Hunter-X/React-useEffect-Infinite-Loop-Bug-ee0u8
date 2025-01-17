# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook: creating an infinite loop by updating a state variable that's also included in the dependency array.  The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected version.