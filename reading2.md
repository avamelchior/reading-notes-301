# Reading 2

## React lifecycle

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

This is important to understand how rendering works.
Render, because it is the third thing to happen in mount, and componentDidMount is the last thing to happen.

**What is the very first thing to happen in the lifecycle of React?**

Understanding this helps us to better comprehend the React lifecycle.
Render phase of mounting.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**

Knowing the order of rendering keeps us informed on the "hows" of React.
Constructor, render, componentDidMount, React Updates, componentWillUnmount.

**What does componentDidMount do?**

It's important we know how things are loaded in on our applications.
Loads anything using a network request/initializes the DOM.

## React State Vs Props

**What types of things can you pass in the props?**

It is good to understand this because we need to be able to pass the appropriate content.
Primitive data types, JavaScript objects and arrays, functions, react elements, custom data types.

**What is the big difference between props and state?**

It is important to know this difference because they are both extremely important to React.
Props are used for passing data from parent to child, state is used to manage and store data within a component.

**When do we re-render our application?**

It is beneficial to know what makes an application re-render.
When the component's props change, when the component's state changes, when the parent component re-renders.

**What are some examples of things that we could store in state?**

This is important for when we begin creating our own applications and need to create certain data sets.
User input, UI state, data fetched from APIs, component specific flags or toggles, any data that needs to change and cause the component to re-render.
