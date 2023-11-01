# Reading 3

## React Docs - lists and keys

**What does .map() return?**

It returns a new array.

**If I want to loop through an array and display each value in JSX, how do I do that in React?**

Use the JavaScript map() function inside your component's return statement.

**Each list item needs a unique ____.**

Each list item needs a unique key.

**What is the purpose of a key?**

It helps React identify what has been changed, added, or removed.

## The Spread Operator

**What is the spread operator?**

Allows an iterable to be expanded in places where zero or more qrguments or elements are expected.

**List 4 things that the spread operator can do.**

a. Copy elements from one array to another.
b. Merge two or more arrays.
c. Create a shallow copy of an object.
d. Spread the elements of an iterable (e.g., string, set) into an array or object.

**Give an example of using the spread operator to combine two arrays.**

const array1 = [1, 2, 3];
const array2 = [4, 5, 6];
const combinedArray = [...array1, ...array2];

**Give an example of using the spread operator to add a new item to an array.**

const originalArray = [1, 2, 3];
const newArray = [...originalArray, 4];

**Give an example of using the spread operator to combine two objects into one.**



## How to Pass Functions Between Components

**In the video, what is the first step that the developer does to pass functions between components?**



**In your own words, what does the increment function do?**



**How can you pass a method from a parent component into a child component?**



**How does the child component invoke a method that was passed to it from a parent component?**


