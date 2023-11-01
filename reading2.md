# Reading 2

## React lifecycle

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

Render, because it is the third thing to happen in mount, and componentDidMount is the last thing to happen.

**What is the very first thing to happen in the lifecycle of React?**

Render phase of mounting.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**

Constructor, render, componentDidMount, React Updates, componentWillUnmount.

**What does componentDidMount do?**

Loads anything useing a network request/initializes the DOM.

## React State Vs Props

**What types of things can you pass in the props?**

Primitive data types, JavaScript objects and arrays, functions, react elements, custom data types.

**What is the big difference between props and state?**

Props are used for passing data from parent to child, state is used to manage and store data within a component.

**When do we re-render our application?**

When the component's props change, when the component's state changes, when the parent component re-renders.

**What are some examples of things that we could store in state?**

User input, UI state, data fetched from APIs, component specific flags or toggles, any data that needs to change and cause the component to re-render.
