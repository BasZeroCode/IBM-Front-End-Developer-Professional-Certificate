## Advanced React Graded Quiz Week 3

## Question 1
**Which is an advantage of using Hooks in a React application?**

- [x] You can handle events and logics in functional components without using classes
- [ ] Hooks enable you to write a functional component without state
- [ ] Code used to write Hooks is complicated
- [ ] Hooks can only be called inside React function components

Using Hooks, such as `useState` and `useEffect`, allows handling events and logic in functional components without the need for class components.

## Question 2
**Which standard Hook is used to manage Redux state changes?**

- [ ] useContext
- [ ] useState
- [x] useReducer
- [ ] useEffect

`useReducer` is the standard Hook used to manage state changes in Redux.

## Question 3
**What is a characteristic of an uncontrolled input?**

- [ ] Functions govern passing of data
- [ ] Props take the current value and notify changes
- [x] Allows the browser to handle most of the form elements
- [ ] A parent component controls the changes

An uncontrolled input allows the browser to handle most form elements without React controlling their state.

## Question 4
**What helps developers in developing a React application using Redux?**

- [ ] Redux reloads the whole page when state changes
- [ ] Redux enhances the state prediction factor
- [ ] In Redux, individual components handle their own state
- [x] Redux helps in creating user interface elements

Redux helps in managing the state of the application in a centralized manner, aiding in the development of user interface elements.

## Question 5
**In which application scenarios is Redux used?**

- [ ] Only in local applications to manage the state of components
- [ ] In applications with a single state mapping to a single container component
- [x] In a big application where state needs to be managed
- [ ] In an application where all props associated with a component are utilized

Redux can be used wherever there’s state to be managed, especially in larger applications.

## Question 6
**What are Actions?**

- [x] An object that performs changes to the application state
- [ ] An object that updates the store
- [ ] An object that stores information about the user event
- [ ] An object that describes changes to the application state

## Question 7
**What is the function of the store?**

- [ ] A store describes what happened
- [ ] A Store can dispatch and receive actions
- [x] A store can perform any changes to the application state
- [ ] A store contains a type field

## Question 8
**Why is middleware required in Redux React applications?**

- [ ] To restore the synchronous data flow
- [ ] To compute the new state
- [ ] To make actions faster
- [x] To use asynchronous operations

Middleware is required in Redux to handle asynchronous operations, such as dispatching actions after receiving a response from a server.

## Question 9
**Which middleware uses ES6 Generators to enable async operations?**

- [ ] Async/Await
- [x] Saga
- [ ] Promise-based
- [ ] Thunk

Redux Saga uses ES6 Generators to enable asynchronous operations.

## Question 10
**Which element in the Redux data flow generates the modified state based on the dispatched action?**

- [ ] UI
- [ ] Action creator
- [x] Reducer
- [ ] Store

The reducer in Redux generates the modified state based on the dispatched action.
