# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook: an infinite loop caused by a missing dependency in the dependency array.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides the corrected code.  The issue stems from the `useEffect` hook not having `count` in its dependency array, leading to an infinite re-render cycle.