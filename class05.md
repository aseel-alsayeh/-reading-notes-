### React Docs - thinking in React
- How would you break a mock into a component heirarchy?
1- draw boxes around every component (and subcomponent) in the mock and give them all names.
2- Use the same techniques for deciding if you should create a new function or object.( single responsibility principle).
3- decomposed into smaller subcomponents.

- What is the single responsibility principle and how does it apply to components?
  - that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

- What does it mean to build a ‘static’ version of your application?
building a static version requires a lot of typing and no thinking.

- Once you have a static application, what do you need to add?
adding interactivity.
- What are the three questions you can ask to determine if something is state?
1.Is it passed in from a parent via props? If so, it probably isn’t state.
2.Does it remain unchanged over time? If so, it probably isn’t state.
3.Can you compute it based on any other state or props in your component? If so, it isn’t state.
How can you identify where state needs to live?