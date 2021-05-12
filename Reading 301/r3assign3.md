# Reading Assignment 3
## Passing Functions as Props

- #### What does .map() return?
    - Used to change or adjust an already existing array.

- #### If I want to loop through an array and display each value in JSX, how do I do that in React?
    - Use curly braces to ID what element you want to render.

- #### Each list item needs a unique ---
    - Key

- #### What is the purpose of a key?
    - Used to ID which items have changed, are added, or are removed.

## The Spread Operator

- #### What is the spread operator?
    - "..."

- #### List 4 things that the spread operator can do
    - Using Math functions
    - Using an array as arguments
    - Adding an item to a list
    - Combining Objects

- #### Give an example of using the spread operator to combine two arrays.
     - "...hello, ...world" would combine they arrays hello and world.

- #### Give and example of using the spread operator to add a new item to an array.
    - ['a','b', ...(array that exists)]
- #### Give an example of using the spread operator to combine two objects into one.
    - object a = {} object b = {}
    - object c = {...object a, ... object b, "new object"}
## How to Pass Functions Between Components

- #### In the video, what is the first step that the devloper does to pass functions between components?
    - He determines which state is going to affected, then inserts the function at that state.

- #### In your own words, what does the increment function do?
    - The increment function determines that if the name passed into the function matches the object names that already exist in the array, than the count will go up by one increment.
- #### How can you pass a method from a parent component into a child component?
    - By using this.method that you want to use.
- #### How does the child component invoke a method that was passed to it from a parent component?
     - When the page is rerendered after an update.

[<==Table of Contents](TOC.three.md)