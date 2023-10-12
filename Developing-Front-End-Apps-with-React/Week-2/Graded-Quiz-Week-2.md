# React Components Graded Quiz Week 2

## Question 1
**What is a State?**

- [ ] A component’s render function that returns data about an attribute
- [ ] A piece of software that passes data between React components
- [ ] A parent component function that takes a string argument
- [x] An object that contains information about the component

In React, the state is an object that holds information about the component and its behavior.

## Question 2
**What is used to pass data between React components?**

- [ ] HTML attribute
- [ ] Shared state
- [x] Prop
- [ ] Local state

Props are used to pass data between React components, allowing the parent component to pass information down to its child components.

## Question 3
**What do you use to pass data from child components to parent components?**
1 point
- [x] Render Callback
- [ ] State Method

Render Callbacks, often used as functions passed as props, can be utilized to pass data from child components to parent components.

## Question 4
**When does a component lifecycle start?**

- [ ] When the component is removed from the DOM
- [x] When components are created or mounted on the DOM
- [ ] When the state of the component first changes
- [ ] When a user clicks the mouse or presses the keyboard

The component lifecycle starts when components are created or mounted on the DOM.

## Question 5
**What do you use to pass data from parent components to child components?**

- [ ] State
- [x] Prop
- [ ] Callback
- [ ] Method

While state can be used, it's common to pass data from parent components to child components using props, which are properties passed from parent to child.

## Question 6
**Which function is invoked right after the component is mounted on the DOM?**

- [ ] componentWillMount
- [ ] componentWillUnmount
- [x] componentDidMount

`componentDidMount` is invoked immediately after a component is mounted on the DOM.

## Question 7
**What do you use to make a call to an external server asynchronous?**

- [x] Promises
- [ ] State Method
- [ ] Props

Promises are used to handle asynchronous operations like making calls to external servers.

## Question 8
**What does the `postDataToServer` method do?**

- [ ] Sets a component with a user state to “None Logged In”
- [ ] Requests all objects in the `usercollection` destination
- [ ] Creates a JSON object and pushes it into the `usercollection` array
- [x] Sends the data to the server and updates the response from the server to the component’s state `completionStatus`

The `postDataToServer` method sends data to the server and updates the component's state based on the server's response.

## Question 9
**What are the phases of a component test?**

- [ ] Chai, Sinon, and Mocha
- [x] Arrange, Act, and Assert

The typical phases of a component test are Arrange (setup), Act (perform the action), and Assert (verify the result).

## Question 10
**What are the two testing approaches?**

- [x] Component and end-to-end
- [ ] Simulated and authenticated
- [ ] Mocha and Chai
- [ ] Regression and event

The two common testing approaches are Component testing (testing individual components in isolation) and End-to-End testing (testing the entire application as a whole).
