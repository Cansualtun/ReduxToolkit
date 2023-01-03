# Basics of Redux Toolkit

## Prerequisites
Knowing *React* and *React Hooks* will be helpful for this documentation.

First of all, before entering the world of redux toolkit, I will talk about 
the **Redux** structure that you have probably heard before.

Redux is a JavaScript library for managing application **state**. 
It is most commonly used with React, but can be used with other JavaScript frameworks as well.

Let's go from the general to the specific, then what exactly does **state management** mean?

State is actually the properties and information that the components in our application have "at the moment".
State management provides the management and organization of each of these states.
The more components inside the application, the more difficult it becomes to manage these states.
Just because of this management difficulty, we use libraries such as redux and redux toolkit.

### What is the differences between Redux and Redux Toolkit?

*Redux* is a popular JavaScript library for managing state in applications. 
It provides a predictable, single source of truth for application state, making it easier to understand and debug complex applications.

*[Redux Toolkit]*(https://redux-toolkit.js.org/) is a official, opinionated, batteries-included toolset for efficient Redux development. 
It is designed to help you write performant, correct Redux code faster and with fewer errors.

Redux Toolkit is intended to be the standard way to write Redux logic, and includes a number of helpful utilities that make it easier to write performant, correct code without having to worry about the underlying implementation details of Redux. If you're just getting started with Redux, you may want to start with Redux Toolkit, as it can make it easier to get up and running quickly.

### Why should we prefer Redux Toolkit?

- Configuring redux in app seems complicated

- It reduces the amount [boilerplate](https://stackoverflow.com/questions/3992199/what-is-boilerplate-code) code 

- It makes it easier to test your Redux logic, as it includes a number of utilities that make it easier to mock store state and   dispatch actions in your tests.

### When should I use redux toolkit?

- You want to make it easier to test your Redux logic, and want a set of utilities that make it easier to mock store state and dispatch actions in your tests.

- You want a set of utilities for working with async logic and middleware in your Redux store.

- The logic to update that state may be complex

- The app has a medium or large size codebase, and might be worked on by many people
