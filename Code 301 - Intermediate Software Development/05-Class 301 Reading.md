# Reading

# React Docs - Thinking in React

What is the single responsibility principle and how does it apply to components?The idea behind the SRP is that every class, module, or function in a program should have one responsibility/purpose in a program
What does it mean to build a ‘static’ version of your application? A Static Web Application is any web application that can be delivered directly to an end user's browser without any server-side alteration of the HTML, CSS, or JavaScript content.
Once you have a static application, what do you need to add? After developing a static application, you can add dynamic content, user interactivity, authentication/user management, database integration, notifications, performance optimization, and analytics/monitoring to enhance its functionality and user experience.
What are the three questions you can ask to determine if something is state?  
Does the data change over time or in response to user interaction
Does the component need to remember or store information to use later
Does the data affect the rendering or behavior of the component

How can you identify where state needs to live? Determine the minimal representation of state: Identify the smallest number of components that need the state data to render correctly. This helps in keeping state management focused and avoiding unnecessary complexity

# Higher-Order Functions

What is a “higher-order function”? A higher order function is a function that takes one or more functions as arguments, or returns a function as its result.
Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing? It is saying that if something is greater than something else then return whatever the value is else return the opposite 
Explain how either map or reduce operates, with regards to higher-order functions.  
map() method: It applies a given function on all the elements of the array and returns the updated array. 
educe() method: It reduces all the elements of the array to a single value by repeatedly applying a function
