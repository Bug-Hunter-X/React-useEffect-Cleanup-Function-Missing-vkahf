# React useEffect Cleanup Function Missing

This example demonstrates a common error in React's `useEffect` hook: forgetting to include a cleanup function to remove event listeners or other side effects when the component unmounts.

The `bug.js` file contains the problematic code, while `bugSolution.js` provides the corrected version.

This oversight can lead to memory leaks, unexpected behavior, and inconsistencies.

## How to reproduce
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the behavior (count incrementing even after the component should be unmounted) in the `bug.js` example.
5. Compare to the corrected behavior in the `bugSolution.js` example. 