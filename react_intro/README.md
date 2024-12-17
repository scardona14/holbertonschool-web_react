# React Project

## Resources

Read or watch:

- [React Official Website](https://reactjs.org/)
- [Getting started with React](https://reactjs.org/docs/getting-started.html)
- [React overview](https://reactjs.org/docs/hello-world.html)
- [Vite | docs](https://vitejs.dev/guide/)
- [React Developer Tools](https://reactjs.org/blog/2019/08/15/new-react-devtools.html)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Jest Matchers](https://jestjs.io/docs/expect)
- [Queries In Testing Library](https://testing-library.com/docs/queries/about/)
- [Mocking functions in testing](https://jestjs.io/docs/mock-functions)
- [Handling user events in RTL](https://testing-library.com/docs/user-event/intro/)
- [dangerouslySetInnerHTML in React](https://reactjs.org/docs/dom-elements.html#dangerouslysetinnerhtml)
- [Deploying React App to GitHub Pages](https://create-react-app.dev/docs/deployment/#github-pages)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- How to create a basic JavaScript application with React
- How to use the build tool Vite to start developing quickly with React
- What JSX is and how it works
- How to add inline styles in React
- How to implement simple forms in React
- How to implement unit tests using React Testing Library
- How to use the React Developer Tools to debug your code
- How to deploy a React application to GitHub Pages

## Requirements

- All your files will be interpreted/compiled on **Ubuntu 20.04 LTS** using **node 20.x.x** or greater and **npm 10.x.x**
- Allowed editors: **vi**, **vim**, **emacs**, **Visual Studio Code**
- All of your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Install Jest globally: `npm install -g jest`

## Tasks

### 0. Basic application (mandatory)

Create a basic app named `dashboard` using the build tool Vite in your `task_0` directory.

You will need a favicon, the Holberton logo, and a close button image. Download these files and place the logo and button images in the `src/assets` folder, and put the favicon in the `public` folder.

- `holberton-logo.jpg`
- `favicon.ico`
- `close-button.png`

Remove the following unused files:

- `index.css`
- `public/vite.svg` and `src/assets/react.svg`

Update the `index.html` file:

- Change the title of the document to be "Holberton - School dashboard"
- Change the icon to be Holberton’s logo

Set up the following files in the project root folder:

- `setupTests.js`
- `.babelrc`
- `fileTransformer.js`

Configure Jest at the end of your `package.json`.

Make sure to install the following packages:

- `@babel/preset-env`
- `@babel/preset-react`
- `identity-obj-proxy`
- `@testing-library/jest-dom`
- `@testing-library/react`
- `jest-environment-jsdom`
- `@testing-library/user-event`

In `task_0/dashboard/src/App.jsx`, create a function `App` that returns:

- A `div` with a class `App-header` containing the Holberton logo with alt text: "holberton logo", and a `h1` with the text "School dashboard" (color: #e1003c)
- A `div` with a class `App-body` containing a paragraph with the text "Login to access the full dashboard"
- A `div` with a class `App-footer` containing a paragraph with the text "Copyright 2024 - Holberton School"

Add the CSS styles to the `App.css` to match the design in the screenshot below:

### Requirements:

- Push your `package.json` and make sure the Jest package is included.
- Use the same names for the downloadable images (`holberton-logo.jpg`, `close-button.png`, `favicon.ico`).
- Ensure the lint check passes without errors (hint: add Jest as the test runner in the ESLint configuration file).
- Make sure the app’s style matches the screenshot.