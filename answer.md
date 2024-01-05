## what is react ?
- React is a java Script library for building user interfaces. It is declarative,efficient and flexible.It lets you to compose complex UIs from just a small piece of code called " Components". It create single page application and reduces server load and perform better.

## Who made React?
- React is owned by facebook .

## What is Babel?
- Bable is a javaScript compiler that converts modern javaScript code(ES6) to browser compatible code. Mostly react and typeScript users use babel.

## How does Babel convert html code in React into valid code?
- Babel use JSX version of react and it converts this jsx into javaScript functions
 - ### Example :
    const user=<div  class="intro">Hello world</div>(jsx)
                    TO
    const user=React.createElement("div",{
        className:"intro",
        children:"Hello world",
    })-----(JavaScript browser readable code)

## What is ReactDOM used for? Write an example?
- ReactDOM is a JavaScript library and and co-partner of react. It is used for rendering elements and components on the UI.
 - ### Example :
 <script type="text/babel">
 let Element=<h1>I'm Ayush .</h1>
 let rootEl=ReactDOM.createRoot(document.getElemtByID("root"));
 rootEl.render(Element)
 </script>

## What are the packages that you need to import for react to work with?
#### Here are some improtant package given below :

- ### React : 
  This is the main react package . It provides the core functionality to for creating React application.

- ### react-dom: 
  This package provides the ReactDOM API which is used to render React components to the DOM.

- ### babel-core:
  This package provides the babel compiler which is used to transpile React code to JavaScript that can be understood by browsers.

- ### webpack :
  This package provides the Webpack module bundler which is used to bundle React applictions into a single file that can be served to the browser.

- ### babel-loader :
  This package provides the babel loader which is used to load babel-compiled React code  into Webpack.

- ### css-loader:
  This package provides the CSS loader which is used to load CSS files into Webpack.

- ### style-loader:
  This package provides the style loader which is used to inject CSS into the DOM.

- These are just the basic packages that you need to get started with React.There are  many other packages that you can use to add additional functionality to your applications.


## How do you add react to a web application?
 steps :
 1. Add two script files to add packages before closing body tag
 2. create an element using react keyword
 3. use react , root and render in your script environment.

## What is React.createElement?
- React.createElement is a function to create react elements . It takes three arguments.

## What are the three properties that createElement accept?
1. Tag
2. props(properties)
3. Children

## What is the meaning of render and root?
1. render : render() is a method that is used to display React components into DOM.
2. root : The Root element is the DOM node where the React components are rendered.
