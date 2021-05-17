# Reading Assignment 5
## Putting it all together

- #### How would you break a mock into a component heirarchy?
    - draw boxes around every component in the mock and give them all names.

- #### What is the single responsibility principle?
    - A component should be set to do a single action.

- #### What does it mean to build a 'static' version of your application?
    - Building a version of the application that has no state due to it being used for interactivity.

- #### Once you have a static application, what do you need to add?
    - Add interactivity by adding state so that the page will be able to update after being manipulated.

- #### What are the three questions you can ask to determine if something is state?
    - Is it passed in from props? Probably isn't state.
    - As the page is interacted with, will it change? Probably isn't state.
    - Can it be calulated using any other components that live on the page? Probably isn't state.

- #### How can you identify where state needs to live?
    - ID components that are affected by what that state is.
    - Find the corresponding parent component.
    - Create a new component if required.



[<==Table of Contents](TOC.three.md)