# Reading

# React Docs - lists and keys

What does .map() return? map() loops over the items of an input iterable (or iterables) and returns an iterator that results from applying a transformation function to every item in the original input iterable. map() applies a function to each item in iterable in a loop and returns a new iterator that yields transformed items on demand.
If I want to loop through an array and display each value in JSX, how do I do that in React? You can use the map() method on an array to loop through the elements and create components, or generate JSX, inside the return block
Each list item needs a unique When creating a list in the UI from an array with JSX, you should add a key prop to each child and to any of its' children.
What is the purpose of a key? to check if a particular key exists.

# The Spread Operator

What is the spread operator? The spread operator is commonly used to make deep copies of JS objects. 
List 4 things that the spread operator can do. Copying an array, Combining objects , Adding to state i React,  Converting NodeList to an array
Give an example of using the spread operator to combine two arrays. To combine two or more arrays, you can either use the functional method []. concat(arr1, arr2) or the spread operator [...arr1,...arr2]. The merging outcome is kept in a new array, making these methods immutable
Give an example of using the spread operator to add a new item to an array. The method to push the element at the end of the array. array. push(element) accepts complete array to push into another array using spread operator
Give an example of using the spread operator to combine two objects into one. The spread operator creates a new object with all the properties from the first and second object

# Videos

### How to Pass Functions Between Components
In the video, what is the first step that the developer does to pass functions between components? Create a function in the parent component that accepts a callback as an argument.
How can you pass a method from a parent component into a child component? To pass a function from a child to a parent, you need to: Create a function in the parent component that accepts a callback as an argument
How does the child component invoke a method that was passed to it from a parent component? In order to call the method from the child component, we need to expose it first

