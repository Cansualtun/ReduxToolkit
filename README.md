# Redux Concepts

Before starting to learn redux toolkit, understanding the basics of redux library will enable us to better understand the principle of redux toolkit.

### Store 

A central place where application state is stored. In Redux, there is a **single store** for the entire application, and the store is the single source of truth for the state of the application.

### Action 

An object that describes an event that has occurred in the application. 
Actions are the only way to modify the state of the store.
Actions carry some information from your app to the redux store.

### Reducers

A function that takes in the current state of the store and an action, and returns a **new state**. 
Reducers are responsible for modifying the state of the store based on the actions that are dispatched.

Reducers are usually written as:

```
function reducer(state, action) {
  switch (action.type) {
    case 'ACTION_TYPE':
      // modify state based on action
      return newState;
    default:
      return state;
  }
}

```

### Dispatch 

A function that sends an action to the store, triggering a state change.

### Middleware 

Functions that can be used to intercept and modify actions as they are dispatched to the store. 
**Middleware**  can be used to perform async operations, log actions, or perform other side effects.