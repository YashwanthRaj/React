# What is React ?

React is a Javascript framework which is used in designing Front End of web applications. 

Essentially what react does is it will render the html code written inside to a javascript code. So when we type html or css, its getting converted into js for the compiler to be understood as javascript. 

Code Sandbox is an online tool which was designed to instantly deploy whatever was coded. This tool was built with react framework in mind. 

JSX stands for JavaScript XML. It's a syntax extension for JavaScript that allows you to write HTML-like structures within your JavaScript code. JSX is primarily used with the React library, but it can be used with other libraries as well.

In HTML, we always create a div with an id of root which will be the contents of the react. 

There is a compiler called babble which can understand every version of javascript so that It can be rendered in every browser. 

ReactDOM is able to render only one html element. Hence if we want to render multiple h1 or p elements, then we just add them inside a div element. 

If we want to insert Javascript expressions like variable name or some value to display into html inside a javascript file, we use {}. 

Also when we include a react file into html, we have to mention it as JSX file rather than type=”text/javascript”. Just change javascript into JSX.

The HTML attributes which are just written as normal text, should be written as camel text in .js file. 

If we want include a style into the JSX. then we need to insert it as javascript object notation. 

In react, we have to capitalize the first letter of every word. 

We can create a function and insert it into the html as if they are html elements. Now as we use capital letter in function names in react, this way the react can differentiate the native and custom elements. 

React props or properties are just like variable that store values. When creating a custom component, we can pass in the values, and while creating a function, we will receive all the values under an object name called props. 

We should always add css class names in our actual component jsx file, we cannot add them in our custom components while rendering in our App.jsx file. Because all the properties that we enter in out custom components will be considered as props and not css class names. 

## React Dev Tools

This is very similar to the chrome developer tools. Shows kinda like a DOM tree but for the react components. 

## Mapping Data to Components

Map is a javascript function that allows us to deal with arrays or JSON. When we have an object or array, then we place the map function to it, the map function will take in another function as its parameter and pass each value of the array/json to the callback function. 

## Filter

For a given array, Filter will create a new array by keeping the items that return true.

## Reduce

Accumulate a value by doing something to each item in an array.

## Find

Find the first item that matches from an array.

## FindIndex

Find the index of the first item that matches.

## Ternary Operator

Condition ? do if true : do if false

## State

The elements in UI will have something called State. Essentially what it means is that the components and elements are the same but depending on the state, components will change its appearance. 

## Declarative Programming

When we write code based on a variable and the style is dependent on that variable. 

## Imperative Programming

When we write code and preset its properties to something, then its imperative programming. 

## Hooks

Hooks are used to help change the UI in accordance with state. So whenever the state changes, it will re-render some properties that depend on the state. 

## ES6 Javascript concept - Deconstructing complex structures

const rgb = [23, 56, 20]

const [red, green, blue] = [23, 56, 20] //Now the variables inside will be mapped to the values according to the position. In this way it will be easier to access each values. 

## Spread Operator

Suppose there are some objects or list with us and we want to include the contents of one data type into another, we can add the …datatype_name in the contents of other data type. this will add the elements/contents of this to another.
