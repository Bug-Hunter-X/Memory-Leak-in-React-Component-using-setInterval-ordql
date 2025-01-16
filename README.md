# React UseEffect SetInterval Memory Leak

This example demonstrates a common error in React components: using `setInterval` within `useEffect` without proper cleanup. This leads to memory leaks as the interval continues to run even after the component unmounts.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file shows the corrected version.