# React Props

## Description

In this project, you will learn to create basic React components, reuse components, and pass properties between them. You will also learn about Fragments, conditional rendering, typechecking with PropTypes, and using keys in loops to improve performance.

---

## Resources

Read or watch the following resources to help you complete the project:

- [React Official Website](https://reactjs.org/)
- [Getting started with React](https://reactjs.org/docs/getting-started.html)
- [React Overview](https://reactjs.org/docs/hello-world.html)
- [React Developer Tools](https://reactjs.org/blog/2019/08/15/new-react-devtools.html)
- [React Fragments](https://reactjs.org/docs/fragments.html)
- [Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)
- [Typechecking with PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Query within an element](https://testing-library.com/docs/queries/about/)
- [Jest Matchers](https://jestjs.io/docs/expect)

---

## Learning Objectives

At the end of this project, you should be able to explain to anyone, without the help of Google:

- How to create basic React components using functions
- How to reuse components
- How to pass properties to components
- How to use Fragments in React
- When to use a key to improve a loop’s performance

---

## Requirements

- All your files will be interpreted/compiled on **Ubuntu 20.04 LTS** using **node 20.x.x** and **npm 10.x.x**
- Allowed editors: **vi, vim, emacs, Visual Studio Code**
- All your files should end with a new line
- A **README.md** file, at the root of the folder of the project, is mandatory
- Install Jest globally: `npm install -g jest`

---

## Tasks

### 0. Basic Components (Mandatory)

Start with the files from the last task of the React intro project. Instead of creating new elements, you'll create components to split the project into more manageable parts. 

#### 1. Create a Header Component:
- Create a new folder `Header`.
- Inside the folder, create a functional component `Header` in a file named `Header.jsx` and move the header code from `App.jsx` into it.
- Move the CSS code related to the header from `App.css` to a new file `Header.css`.
- Create an empty test file `Header.spec.js`.

#### 2. Create a Footer Component:
- Create a new folder `Footer`.
- Inside the folder, create a functional component `Footer` in a file named `Footer.jsx` and move the footer code from `App.jsx` into it.
- Move the CSS code related to the footer from `App.css` to a new file `Footer.css`.
- Create an empty test file `Footer.spec.js`.

#### 3. Create a Login Component:
- Create a new folder `Login`.
- Inside the folder, create a functional component `Login` in a file named `Login.jsx` and move the login form code from `App.jsx` into it.
- Move the CSS code related to the login from `App.css` to a new file `Login.css`.
- Create an empty test file `Login.spec.js`.

#### 4. Modify the Shell:
- In `App.jsx`, import the `Header`, `Login`, and `Footer` components.
- Pass the components in the order `Header`, `Login`, and `Footer`.
- Wrap the above elements inside a React `<Fragment>`.

---

## Tests

### 1. App.spec.js:
- As an entry point, in the `App.spec.js` file, check that all components are rendered correctly.

### 2. Header.spec.js:
- Copy all Header-related unit tests from your previous setup into the `Header.spec.js` file.

### 3. Login.spec.js:
- Copy all Login-related unit tests into the `Login.spec.js` file.

### 4. Footer.spec.js:
- Copy all Footer-related unit tests into the `Footer.spec.js` file.

---

## Requirements (Revisited)

- After implementing the changes, reloading the App should display the exact same page as the last task.
- The browser's console should not show any errors or warnings.

---

## Additional Notes

- If you encounter any issues, refer to the React documentation and testing libraries provided in the resources section.
- Make sure to follow React's best practices for creating components, passing props, and structuring your application.

---

Good luck with your project! If you need further help, feel free to reach out.
