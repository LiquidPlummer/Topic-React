
# Hooks
[React Docs - Hooks](https://reactjs.org/docs/hooks-intro.html)

Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don’t work inside classes — they let you use React without classes. React provides a few built-in Hooks like useState, useEffect, etc. You can also create your own Hooks to reuse stateful behavior between different components.

Hooks are JavaScript functions, but they impose two additional rules:

 - Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
 - Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)

There are a number of built-in hooks, some commonly used ones include:
- useEffect 
- useState
- useRef
- useContext
