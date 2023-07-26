# Hello world! in React JS ⚛️

Live demo - [https://srikanth-kandi.github.io/react-hello-world/](https://srikanth-kandi.github.io/react-hello-world/)

Implemented with the help of React CDN v17.0.0 - [https://reactjs.org/docs/cdn-links.html](https://reactjs.org/docs/cdn-links.html) and Babel CDN - [https://babeljs.io/docs/en/babel-standalone](https://babeljs.io/docs/en/babel-standalone)

I used the `JSX` syntax and Babel to convert it to JavaScript.

React will dynamically create a `<h1>` tag with the content "Hello world!" in it.

```jsx
const element = <h1 className = "greeting">Hello world!</h1>;
```

The `className` is an inbuilt attribute in React which is used to add CSS classes to the HTML elements.

The `ReactDOM.render()` method is used to render the `h1` element into the DOM in the container specified (in this case, the `root` div).

`ReactDOM.render()` will take two arguments, the first one is the element to be rendered and the second one is the container in which the element should be rendered.

```jsx
ReactDOM.render(element, document.getElementById('root'));
```

After rendering, the DOM will look like this:

```html
<div id="root">
    <h1 class="greeting">Hello world!</h1>
</div>
```

Resulting in the following output:

![Hello world! output](./images/output.png)