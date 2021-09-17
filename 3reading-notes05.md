*Reading Notes 05*

1. React Docs - Thinking in React
    1. What is the single responsibility principle and how does it apply to components? A component should do one thing, and if it does more it should be broken down into multiple components
    2. What does it mean to build a ‘static’ version of your application?
    3. Rendered UI but no interactivity
    4. Once you have a static application, what do you need to add?
    5. Identify the State
    6. What are the three questions you can ask to determine if something is state?
2. Is it passed in from a parent via props? If so, it probably isn’t state.
3. Does it remain unchanged over time? If so, it probably isn’t state.
4. Can you compute it based on any other state or props in your component? If so, it isn’t state
    1. How can you identify where state needs to live?
* Find a common owner component (a single component above all the components that need the state in the hierarchy).
* Either the common owner or another component higher up in the hierarchy should own the state.
* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

1. Higher-Order Functions
    1. What is a “higher-order function”?Functions that operate on other functions, that take them in a s arguments or returning them
    2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?Returning the value of m > n coming from another function 
    3. Explain how either map or reduce operates, with regards to higher-order functions.
    4. It changes the form of arrays, it builds a new array of values, retaining their values, but in different orders etc.

## Things I want to know more about  Interested in seeing these concepts applied to real world coding projects. Biger scale.etc

[Back](README.md)