# React 101

## Task 1

👉 Put the following two script tags at the bottom of your `head` tag. This will load react so that we can use it.

```html
<script
  src="https://unpkg.com/react@18/umd/react.development.js"
  crossorigin
></script>
<script
  src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"
  crossorigin
></script>
```

👉 below the root element add `const root = ReactDOM.createRoot(rootElement);`

👉 convert from `document.createElement` to `React.createElement`

👉 convert from `rootElement.appendChild(element);` to `root.render(element)`

👉 using the above `React.createElement` add a className and text to it, make sure to keep orginal className of `container`

## Task 2

👉 Fill in the Button function component which returns a react element `React.createElement`

👉 Give the element a `className` of `"button"`.

👉 Give the element some text of of `big button`.

## Task 3 - JSX

### 3a

👉 Add the following script to the head of the html document. This will load babel which allow's us to write JSX. Our JSX will be converted back to the raw api.

```html
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```

👉 Give the script tag **above** the `const rootElement = ...` a type attribute of `"text/babel"` so that babel will transpile the contents of our tag to raw JavaScript.

👉 Convert the `Title` component to JSX

### 3b

👉 In the same file you are in for task 3, recreate your components from tasks 1 and 2 using JSX instead of `React.createElement()`

## Task 4 - Props

👉 Complete the list item component so that it returns an `li` containing the data from the text prop

Destructuring is a way to access properties of an object (or array) quickly and easily, and it's often used when accessing props in React.

Learn more about destructuring here:

- [JavaScriptTutorial.net page](https://www.javascripttutorial.net/es6/javascript-object-destructuring/)
- [FreeCodeCamp blog page](https://www.freecodecamp.org/news/destructuring-patterns-javascript-arrays-and-objects/)
- [MDN docs page with examples](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
- [Fireship video (2min)](https://www.youtube.com/watch?v=UgEaJBz3bjY)
- [WebDevSimplified video (13min)](https://www.youtube.com/watch?v=NIq3qLaHCIs)

## Task 5 - Children

👉 Complete the list component so that it renders its children

## Bonus Task - Conditional Rendering

👉 Complete the `CheckBox` component.

Take in a boolean as a prop called checked and make it control the checkbox. Investigate how to use that boolean and conditional rendering to make an element on the page render or not.

(HINT: using the `disabled` attribute makes a button or checkbox un-clickable!)

👉 Create another component that takes in a boolean prop. Respond to that prop in a different way using conditional rendering.

Here are some useful links:

- https://react.dev/learn/conditional-rendering
- https://www.w3schools.com/react/react_conditional_rendering.asp

## Bonus Task - Inline Styling

Using all the information on React and props, have a go at learning about inline styling and using props to your advantage.

Here are some useful links:

- https://www.w3schools.com/react/react_css.asp
- https://blog.cloudboost.io/using-inline-styles-in-jsx-c1d03cbe6fe0
