# 0x02. React props

## Front-end
- JavaScript
- ES6
- React

By: Johann Kerbrat, Engineering Manager at Uber Works
Weight: 1


## Resources
Read or watch:
- [React Official Website](https://reactjs.org/)
- [Getting started with React](https://reactjs.org/docs/getting-started.html)
- [React overview](https://reactjs.org/docs/react-api.html)
- [React Developer Tools](https://reactjs.org/blog/2019/08/15/new-react-devtools.html)
- [Enzyme](https://enzymejs.github.io/enzyme/)
- [React Fragments](https://reactjs.org/docs/fragments.html)
- [Typechecking with PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- How to create basic React components using functions
- How to reuse components
- How to pass properties to components
- How to define types for components
- How to use Fragments
- When to use a key to improve a loop’s performance

## Requirements
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node 12.x.x and npm 6.x.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory

## Tasks

### 0. Basic components (mandatory)
Start with your files from the last task of the 0x01. React intro project

Instead of creating new elements, we’re going to create components to split the project. The App.js is going to become the main entry point, the shell, for every component in the app.

...

### 1. Write the tests for each component (mandatory)
To develop your tests faster, you can watch them. The test suite will run for every change you make:

Add the following script to task_1/package.json: "test-watch": "jest --watch"
Run your suite using npm run test-watch

...

### 2. Split the Notifications component (mandatory)
2.1. Create a NotificationItem.js
The Notifications component is repeating the same tags a lot. It will be hard to maintain and reuse. Let’s create a component to support the li generation.

...

### 3. Checking the application using the React extension (mandatory)
Using the React extension in Chrome:

Modify the type of the first NotificationItem to change from “default” to “urgent”. The first notification should change color to red, take a screenshot
Profile the load of the application and note which Component is the longest to render after App, take a screenshot

...

### 4. Props types & Default props & Shapes (mandatory)
To work on this task, install prop-types with npm first

...

### 5. Shapes, Loops, and Keys (mandatory)
Create the courses array
Create a new Shape named CourseShape containing:

...

## Running the Tests
