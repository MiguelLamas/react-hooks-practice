# React Hooks Practice

## Understanding and practicing all 9 core hooks from React:

- <ins>useState</ins> - It returns an array with two values: the current state and a function to update it. 
- <ins>useReducer</ins> - Use when the state becomes complex, with state values depending on each other or when the next state depends on the previous one. Useful when many different States that are being altered on the same action perhaps, like with an onClick().
- <ins>useEffect</ins> - Use this Hook to tell React that your component needs to do something after render. e.g fetching data, directly updating the DOM, and timers.
- <ins>useRef</ins> - Allows you to persist values between renders. It can be used to store a mutable value that does not cause a re-render when updated. It can be used to access a DOM element directly.
- <ins>useLayoutEffect</ins> - Useful if you want to do something based on the DOM, before it gets printed to the screen. It runs synchronously immediately after React has performed all DOM mutations. This can be useful if you need to make DOM measurements (like getting the scroll position or other styles for an element) and then make DOM mutations or trigger a synchronous re-render by updating state.
- useImperativeHandle
- useContext
- useMemo
- useCallback
