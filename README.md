# useEffect Hook with Empty Dependency Array and Unexpected Re-renders

This example demonstrates a common issue with the `useEffect` hook in React. The effect runs only once when the component mounts, but doesn't re-run if the component re-renders due to prop or state changes outside of the effect's dependencies. 

The `bug.js` file contains the buggy code, showing how the effect does not update when the counter changes. The `bugSolution.js` offers a fix using a suitable dependency array.