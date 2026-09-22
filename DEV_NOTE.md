# Dev Note

## Chapter 03

- HTML represents the initial page content, whereas the DOM represents the updated page content which was changed by the JavaScript
- As a developer, you can tell React what you want to happen to the user interface, and React will figure out the steps of how to update the DOM on your behalf.

## Chapter 04

- The destructuring syntax is a JavaScript syntax that makes it possible to unpack values from arrays, or properties from objects, into distinct variables. It can be used in locations that receive data (such as the left-hand side of an assignment or anywhere that creates new identifier bindings).
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring

## Chapter 05

- User interfaces can be broken down into smaller building blocks called components.

## Chapter 06

- Similar to a JavaScript function, you can design components that accept custom arguments (or props) 
- Since props is an object, you can use object destructuring to explicitly name the values of props inside your function parameters

## Chapter 07

- [State and hooks](https://nextjs.org/learn/react-foundations/updating-state#state-and-hooks)
-  Unlike props which are passed to components as the first function parameter, the state is initiated and stored within a component. You can pass the state information to children components as props, but the logic for updating the state should be kept within the component where state was initially created.
-  This was only an introduction to state, and there's more you can learn about managing state and data flow in your React applications. To learn more, we recommend you go through the Adding Interactivity and Managing State sections in the React documentation.
