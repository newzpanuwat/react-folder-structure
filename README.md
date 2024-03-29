# React js

- React js is frontend library of javascripts
- Components-Based

## Why react?

- Flexibility
  -- the React code is easier to maintain and is flexible due to its modular structure.
- Performance
  -- The core of the framework offers a virtual DOM program and server-side rendering
- Reusable Components
  -- It saves time for developers as they don’t have to write various codes for the same features

## Javascripts need to know before learning react.js

- Callback Functions in JavaScript, map(), filter(), setTimeout()
- Promises in JavaScript, Pending, Resolved, Rejected
- Destructuring Arrays and Objects in JavaScript
- Object destructuring
- Rest and Spread Operators in JavaScript, {...}
- ES6 -ES10
- Optional chaining in JavaScript
- Fetch API & Errors in JavaScript
- Async/Await in JavaScript

## Tools

- macOS, Ubuntu
- VS Code, Atom, etc. (any whatever you want)
- Node v.16+
- npm

## VSCODE extensions

- Atom keymap
- Eslint
- Prettier Codeformatter
- Gitlens
- Path Intellisense
- ES7+ React/Redux/React-Native snippets
- HTML CSS Support
- Simple React Snippets
- vscode-icons

## Folder Structure

This example below is only my designed, you can adjust them whatever you want.

```sh
https://codesandbox.io/s/react-folder-stucture-diro5w
```

#### 1. JSX ?

You can write html tag in javascripts
`const element = <h1>Hello, {name}</h1>;`

```sh
https://medium.com/niawjr/react-the-series-ep1-intro-to-jsx-a2e4b924864a
```

#### 2. React Hooks ?

- It's allows you to use state and other React features without writing a class

##### Hooks features

- useEffect()
- useState()

##### Optional

- useContext()
- useReducer()
- useTransition (v.18)
- useDeferredValue (v.18)

#### 3. Function Components

`const data = getData = () => <div>show data </div>`


#### 4. Props

```
const data = getData = (props) => <div>show data {props} </div>
```

#### 5. Deployment

- Vercel
- Jenkins deployment for VPS

### Code Example

```sh
https://codesandbox.io/s/react-basic-components-j17om4
```

This example all included

- useState
- Components based
- Props
- Destructing data
- Spread operators
- Reusable components (Input)
- Event handler
