# 0x02. React props

## Front-end
- JavaScript
- ES6
- React

By: Johann Kerbrat, Engineering Manager at Uber Works
Weight: 1

Project will start Aug 24, 2023 6:00 AM, must end by Aug 29, 2023 6:00 AM
Manual QA review must be done (request it when you are done with the project)

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
" Start with your files from the last task of the 0x01. React intro project

" Instead of creating new elements, we’re going to create components to split the project. The App.js is going to become the main entry point, the shell, for every component in the app.

" Create a Header component
" Create a new folder Header:
mkdir Header

" Move the code of the header from the App.js to a new file Header.js
mv App.js Header/Header.js

" Move the css code, related to the header, of the App.css to a new file named Header.css
mv App.css Header/Header.css

" Create an empty Header.test.js. We’ll add tests for it later.
touch Header/Header.test.js

" Create a Footer component
" Create a new folder Footer:
mkdir Footer

" Move the code of the footer from the App.js to a new file Footer.js
mv App.js Footer/Footer.js

" Move the css code, related to the footer, of the App.css to a new file named Footer.css
mv App.css Footer/Footer.css

" Create a Footer.test.js, we will add the tests later
touch Footer/Footer.test.js

" Create a Login component
" Create a new folder Login:
mkdir Login

" Move the code of the login section from the App.js to a new file Login.js
mv App.js Login/Login.js

" The code should be wrapped in a React Fragment

" Move the css code, related to the login, of the App.css to a new file named Login.css
mv App.css Login/Login.css

" Create a Login.test.js, we will add the tests later
touch Login/Login.test.js
" Modify the shell
" In the index.js:
" Remove the root-notifications
" Remove the Notifications import
" In the App.js:
" Import Notifications, Login, Footer, and Header
" Add the new Notifications component before the div.App element
" Wrap Notifications and the rest of the div.App within a React Fragment
" In the div.App, replace the header code by the new Header component
" In the div.App-body, replace the login code by the new Login component
" In the div.App-footer, replace the footer code by the new Footer component
" In the App.test.js:
" Most tests will fail, only keep the one testing that the component renders without crashing

" Requirements:
" At this point, reloading the App should display the exact same page as the last task
" The console in your browser should not show any error or warning

" Repo:

" GitHub repository: alx-react
" Directory: 0x02-react_props
" File: task_0/dashboard/dist/index.html, task_0/dashboard/src/App/App.js, task_0/dashboard/src/Footer/Footer.css, task_0/dashboard/src/Footer/Footer.js, task_0/dashboard/src/Footer/Footer.test.js, task_0/dashboard/src/Header/Header.css, task_0/dashboard/src/Header/Header.js, task_0/dashboard/src/Header/Header.test.js, task_0/dashboard/src/Login/Login.css, task_0/dashboard/src/Login/Login.js, task_0/dashboard/src/Login/Login.test.js

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
