# React lifecycle

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? The render happens first.
What is the very first thing to happen in the lifecycle of React?  The three phases are mounting, unmounting and updating 
Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates?    componentDidMount, render, constructor, componentWillUnmount, React Updates.  constructor, render, Reach Updates, componentDidMount, componentWillUnmount
What does componentDidMount do?  allows us to execute the React code when the component is already placed in the DOM (Document Object Model)
Videos

# React State Vs Props

What types of things can you pass in the props? It can be any data type as props in React components: object, array, boolean, number, string, function, etc
What is the big difference between props and state? Props are used to pass data from a parent component to a child component, while state is used to manage data within a component.
When do we re-render our application? We do it whenever there is a change in their state or props. 
What are some examples of things that we could store in state?   Forms and api