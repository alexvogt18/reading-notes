# Reading Assignment 2
## State and Props

- #### Based off the diagram, what happens first, the 'render' or the 'componentDidMount'?
    - On the diagram, render comes from getDerivedStateFromProps, which eventually becomes componentDidMount.

- #### What is the very first thing to happen in the lifecycle of React?
    - Mounting, beginning with the constructor function being created.

- #### Put the following things in the order that they happen:
    - 1) constructor 2) render 3) componentDidMount /componentWillUnmount 4) React Updates

- #### What types of things can you pass in the props?
    - counter component, title and subtitle

- #### What is thee big difference between props and state?
    - Props pass into a component while state already exists within a component.

- #### When do we re-render our application?
    - when the computer detects that the state has changed the components.

- #### What are some examples of things that we could store in state?
    - Things that require a count, for instance reducing the number of guesses.
    - Great for form entry.