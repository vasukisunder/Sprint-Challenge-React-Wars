# Answers

1. What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.

React is a library that helps developers create more complex and user-friendly user interfaces. React uses components for different parts of the application, which makes the code more modular and reusable, because each component can be self contained and functional. Additionally, React allows you to import other libraries and is flexible enough to be used for a wide variety of applications and preferences as it it can be used along with many other frameworks. It also solves the problem of too many DOM requests that would slow performance by using a virutal DOM.

1. What does it mean to think in react?

Thinking in React means beginning by breaking up the project you're working on into several different components that will semantically work together in your application's user interface. You can then use these predefined components to build a static version without interactivity yet. Eventually, add state in the right location and add the data flow.


1. Describe state.

State is a built-in object in React that stores properties in a component. Its managed inside the component, and when it changes the component will respond by re-rendering.

1. Describe props.

Props are information that is passed to the component similarly to parameters in a function. React passes JSX attributes and children to a user-defined component as a single object.

1. What are side effects, and how do you sync effects in a React component to state or prop changes?

In React, an effect is something that affects something outside of the function scope - this includes when the user manipulates the DOM manually, API calls for data, and others. useEffect() can be used to re-render your React component with state or prop changes.

