# Javascript data type

## JavaScript Data Types

JavaScript has seven built-in data types:

- **Number**: represents numeric values. Example: `10`.
- **String**: represents textual data. Example: `'Hello, world!'`.
- **Boolean**: represents a logical value indicating `true` or `false`.
- **Undefined**: represents an undefined value. Example: `let a;`.
- **Null**: represents a null value. Example: `let b = null;`.
- **Symbol**: represents a unique identifier. Example: `const mySymbol = Symbol('foo');`.
- **Object**: represents a collection of related data or functionality. Example: `const person = { name: 'John', age: 30 };`.

ReactJS is a JavaScript library for building user interfaces. It uses JavaScript data types to manage state and props. Here's an example of using the `useState` hook to manage state in a React component:

```jsx
import React, { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  function incrementCount() {
    setCount(count + 1);
  }

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={incrementCount}>Increment</button>
    </div>
  );
}
```

In this example, we use the `useState` hook to define a state variable `count` and a function to update the state `setCount`. We also define a function `incrementCount` that updates the state when a button is clicked. Finally, we render the current count and a button that calls the `incrementCount` function when clicked.
