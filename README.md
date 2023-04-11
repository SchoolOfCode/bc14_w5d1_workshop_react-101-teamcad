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

Usefull link's to use React.createElement:

- https://react-tutorial.app/app.html?id=338
- https://reactjs.org/docs/add-react-to-a-website.html

## Task 2 - JSX

### 2a

👉 Add the following script to the head of the html document. This will load babel which allow's us to write JSX. Our JSX will be converted back to the raw api.

```html
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```

👉 Give the script tag **above** the `const rootElement = ...` a type attribute of `"text/babel"` so that babel will transpile the contents of our tag to raw JavaScript.

👉 Convert the `Title` component to JSX

### 2b

👉 In the same file you are in for task 2, recreate your components from tasks 1 using JSX instead of `React.createElement()`

## Task 3 - Nesting

👉 in react we can only render one element at the root of our applications root.render, but we can nest items inside one another. have a go at trying to create the following:

- Create a `<ul></ul>` tag
- Nest 2 `<li></li>` tags inside the `<ul>` tag to make a list

here is a usefull link:

https://itnext.io/how-to-easily-render-multiple-elements-in-react-c9193a06f23a#:~:text=In%20Vue%20and%20React%2C%20we,is%20a%20tag.

## Bonus task 4 - JSX Events

👉 use the following resource to see how we apply events to our JSX , once you have understood, create a button with JSX and add a click event to it/

https://reactjs.org/docs/handling-events.html

inside the `root.render(<button/>)` you can add an array to display multiple buttons , try add an array with 2 more buttons

## Bonus Task - Inline styling

using all the information on react have a go at learning about inline styling.


here are some usefull links.

- https://www.w3schools.com/react/react_css.asp
- https://blog.cloudboost.io/using-inline-styles-in-jsx-c1d03cbe6fe0
