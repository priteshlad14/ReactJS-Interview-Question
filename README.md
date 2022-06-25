# React Interview Questions & Answers

[Reference](https://github.com/sudheerj/reactjs-interview-questions/blob/master/README.md#what-is-react)

### Table of Contents

| No. | Questions |
| --- | --------- |
|   | **Core React** |
|1  | [What is React?](#what-is-react) |
|2  | [What is JSX?](#what-is-jsx) |



1. ### What is React?

    React is an **open-source front-end JavaScript library** that is used for building user interfaces, especially for single-page applications. It is used for handling view for web and mobile apps. 

   **[⬆ Back to Top](#table-of-contents)**
   
2. ### What is JSX?

    *JSX* is a XML-like syntax extension to ECMAScript (the acronym stands for *JavaScript XML*). Basically it just provides syntactic sugar for the `React.createElement()` function, giving us expressiveness of JavaScript along with HTML like template syntax.

    In the example below text inside `<h1>` tag is returned as JavaScript function to the render function.

    ```jsx harmony
    class App extends React.Component {
      render() {
        return(
          <div>
            <h1>{'Welcome to React world!'}</h1>
          </div>
        )
      }
    }
    ```
    [Reactjs.org JSX reference](https://reactjs.org/docs/introducing-jsx.html)

    [w3School JSX reference](https://www.w3schools.com/react/react_jsx.asp)

   **[⬆ Back to Top](#table-of-contents)**
