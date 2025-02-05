# Uncontrolled setInterval in useEffect causing memory leak
This example demonstrates a common mistake in React: using setInterval inside useEffect without proper cleanup.  This leads to memory leaks and unexpected behavior.

The bug.js file shows the incorrect implementation, while bugSolution.js provides the corrected version.

This issue is easily resolved by returning a cleanup function from the useEffect hook.