# Vite 
## Advantages of vite over CRA 
## Steps to create project 
## Project Structure 
## Hot moudle replacement 
## Webpack 
## Babel 

# DOM
# Virtual Dom in react 
## Diffing and reconcialation
reconcialation - process React uses to **update the DOM** efficiently when the state or props of a component change
diffing - process of compariint the old virtual dom with new to indentify changes

## React fibers
## Synthetic Events 
### Event pooling 
# SPA vs MPA 
# CSR vs SSR 
# React.js 
## jsx 

# components 
self contained reusabel piece of code represents a part of ui 
## Class components
uses es6 class , older , stateful ,
### LifeCycle Methods

componentDidMount, componentDidUpdate, componentWillUnmount
shouldComponentUpdate, render , getDerivedStateFromProps
### Pure Component
component only renders when prop or state of it changes 
## Functional components
stateless, easier syntax, better perfomant 
### Higher order component
#### Advantages 
seperation of concerns , enhanced functionality , flexible and composable 
#### Limitatinos 
wrapper hell , props collision 
### Controlled vs unControlled components 
controlled -  maintains the state using react component state 
uncontrolled - maintains interal state using DOM  
## builtin components 
### Fragment 
### Profiler 
### Suspense 
### StrictMode 
# Dynamic Rendering 
ability to **change what gets displayed** on the UI **based on conditions or state** — without refreshing the page
# Hooks 
## Rules of Hooks 
## useState 
### State vs variable
## useEffect 
### examples of side effects 
fetching data from api , dom manupulation , timers, logging , local storage access 
### Dependency array
### Cleanup function 
## useRef 

# React Router 
library enables routing in react applications 
