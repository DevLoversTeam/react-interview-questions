**Read in other languages: [English 🇺🇸](README.en.md),
[Polska 🇵🇱](README.pl.md), [German 🇩🇪](README.de.md), [French 🇫🇷](README.fr.md),
[Українська 🇺🇦](README.md).**

<h1>
  React <img src="./assets/react.svg" width="40" height="40" />
</h1>

<h2>Most Popular React Interview Questions and Answers</h2>

<details>
<summary>1. What is React?</summary>

#### React

React is a JavaScript library for building user interfaces. Main
characteristics:

1. **Component-based approach:** The UI is split into separate components that
   can be reused.

2. **Virtual DOM:** Ensures efficient UI updates by minimizing manipulations of
   the real DOM.

3. **Declarative nature:** You describe what the UI should look like in a given
   state, and React keeps it in sync.

4. **One-way data flow:** Data is passed from top to bottom through props, which
   makes state control easier.

React was created by Facebook and is widely used for developing SPAs (Single
Page Applications).

</details>

<details>
<summary>2. List the features of React.</summary>

#### React

1. **Component-based approach:** Code is divided into reusable, independent
   components.

2. **Virtual DOM:** Fast UI updates without directly manipulating the DOM.

3. **One-way data flow:** Data is passed from parent components to child
   components through props.

4. **JSX:** A JavaScript syntax extension for writing UI as XML-like code.

5. **State and lifecycle:** Components can store and manage their own state.

6. **React Hooks:** Add state and side effect capabilities to functional
   components.

7. **Ecosystem:** Supports libraries such as React Router and Redux to extend
   functionality.

8. **SEO-friendly (with Next.js):** Server-side rendering improves indexing.

9. **Mobile development:** React Native allows you to build mobile applications
   based on React.

10. **Open source:** Actively supported by the community.

</details>

<details>
<summary>3. What are the main functions of React?</summary>

#### React

#### Main functions of React:

1. **Declarative approach:** React allows you to build an interactive interface
   by describing how it should look, while the library optimizes DOM updates.

2. **Component structure:** An application is built from independent, reusable
   components, which simplifies development, testing, and maintenance.

3. **Virtual DOM:** React uses the Virtual DOM to efficiently update the real
   DOM, which significantly improves performance.

4. **One-way data flow:** Data is passed from parent components to child
   components through props, which simplifies state management.

5. **Hooks:** Allow you to use state and lifecycle methods in functional
   components.

6. **JSX:** A JavaScript extension for describing UI with syntax similar to
   HTML.

7. **React Native:** The ability to build native mobile applications using the
   same principles as for the web.

8. **Ecosystem:** A large set of libraries and tools such as React Router,
   Redux, and Context API.

9. **Server-side rendering (SSR) support:** Helps optimize SEO and speed up the
   initial page load.

10. **State management:** Using `useState`, Context API, Redux, or other
    libraries.

These features make React a powerful and flexible library for building modern
applications.

</details>

<details>
<summary>4. What are the key advantages of using React?</summary>

#### React

#### Key advantages of using React

1. **Speed**: Thanks to the Virtual DOM, React minimizes interactions with the
   real DOM, which improves performance.

2. **Component-based approach**: Code is split into reusable components, which
   simplifies development and maintenance.

3. **One-way data flow**: Data in React flows in one direction (top-down), which
   makes debugging easier.

4. **Large community**: React has a huge ecosystem of libraries, tools, and
   extensions.

5. **Compatibility with mobile development**: Using React Native, you can build
   cross-platform mobile applications.

6. **JSX**: Syntax that allows you to write JavaScript together with HTML-like
   markup, improving code readability.

7. **Hooks support**: Simplifies working with state and lifecycle in functional
   components.

8. **SEO friendliness**: Server-side rendering with tools like Next.js improves
   SEO optimization.

9. **Flexibility**: React can be integrated into any project or framework
   without significant code changes.

10. **React DevTools**: A debugging tool that makes it convenient to inspect
    components and application state.

</details>

<details>
<summary>5. What is JSX?</summary>

#### React

**JSX (JavaScript XML)** is a syntax that allows you to write UI structures as
XML-like code inside JavaScript. JSX is an extension of JavaScript and is used
in React to describe what the interface looks like.

#### Main features of JSX:

1. **XML-like syntax:** It resembles HTML, but is used in JavaScript.

```jsx
const element = Hello, world!;
```

2. **Embedded JavaScript:** You can write JavaScript code inside curly braces
   `{}`.

```jsx
const name = 'Alice';
const element = Hello, {name}!;
```

3. **Compilation:** JSX is compiled into regular JavaScript using libraries such
   as Babel.

```jsx
const element = Hello;
// Becomes:
const element = React.createElement('h1', null, 'Hello');
```

4. **Attributes:** They are used similarly to HTML, but instead of `class` you
   write `className`, and instead of `for` you write `htmlFor`.

```jsx
const input = ;
```

5. **JSX returns an element tree:** A JSX expression can return only one root
   element. Use `<React.Fragment>` or an empty tag `<>` for grouping.

```jsx
return <>Title Description</>;
```

#### Advantages:

- Convenient creation of UI components.
- Clear and readable syntax.
- Tight integration with JavaScript logic.

JSX is not mandatory in React, but it is widely used because of its convenience
and flexibility.

</details>

<details>
<summary>6. What is the difference between state and props?</summary>

#### React

#### Difference between state and props

| Criterion            | State                                                       | Props                                                     |
| -------------------- | ----------------------------------------------------------- | --------------------------------------------------------- |
| **Purpose**          | Stores the internal state of a component.                   | Passes data from a parent component to a child component. |
| **Mutability**       | Can be changed inside the component.                        | Immutable (read-only).                                    |
| **Availability**     | Available only in the component where it is defined.        | Available in the child component through attributes.      |
| **Initialization**   | Set inside the component using `useState` or a constructor. | Defined by the parent component.                          |
| **Usage scope**      | Used for storing dynamic data that can change.              | Used for passing fixed or dynamic data.                   |
| **Who controls it?** | The component where the state is defined.                   | The parent component.                                     |

</details>

<details>
<summary>7. What is the difference between an element and a component?</summary>

#### React

#### Difference between an element and a component in React:

| Criterion           | Element                                                       | Component                                                                                          |
| ------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Definition**      | An object that describes what the interface should look like. | A function or class that returns React elements.                                                   |
| **Type**            | Immutable.                                                    | Reusable and may have state.                                                                       |
| **Creation syntax** | `React.createElement` or JSX (`<div />`).                     | Function or class (`function MyComponent() {}` or `class MyComponent extends React.Component {}`). |
| **Purpose**         | Represents a single node in the DOM.                          | Encapsulates UI logic and structure.                                                               |
| **Usage**           | Used to create UI at a basic level.                           | Used to build more complex structures with business logic.                                         |
| **Example**         | `<h1>Hello</h1>`                                              | `function Hello() { return <h1>Hello</h1>; }`                                                      |

An element is a "building block," while a component is a "constructor" for
creating complex interfaces.

</details>

<details>
<summary>8. How do you create components in React?</summary>

#### React

#### In React, components can be created in two ways:

1. **Functional component:** This is a simple function that returns React
   elements.

```jsx
function Greeting(props) {
  return Hello, {props.name}!;
}

// Usage:
;
```

2. **Class component:** This is a class that extends `React.Component` and must
   have a `render` method.

```jsx
class Greeting extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Usage:
;
```

#### Differences:

- Functional components are simpler and are better suited for components without
  state.

- Class components are used for more complex components with their own state or
  lifecycle methods.

**Note:** The modern approach is to use functional components with hooks instead
of class components.

</details>

<details>
<summary>9. What is state in React?</summary>

#### React

**State** in React is an object used to store data that can change over time and
affects how a component is rendered. State allows React components to be dynamic
and respond to events, user input, and more.

#### Features of state:

1. **Local to the component:** State is available only in the component where it
   is defined.

2. **Changes asynchronously:** React batches `setState` calls to optimize
   rendering.

3. **Initialized in the constructor** (for class components) or with `useState`
   (in functional components).

#### In class components:

```jsx
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        Count: {this.state.count}
        Increment

    );
  }
}
```

#### In functional components (with the `useState` hook):

```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (

      Count: {count}
      <button onClick={() => setCount(count + 1)}>Increment

  );
}
```

#### Main differences between state and props:

- **State** is local to the component and can change.

- **Props** are passed from outside and are immutable.

</details>

<details>
<summary>10. What are props in React?</summary>

#### React

**Props** in React are an object that contains data passed from a parent
component to a child component. They are used to configure components and are
immutable.

#### Features of props:

1. **Passed from top to bottom** (unidirectional data flow) from the parent
   component to the child component.

2. **Immutable**: A component cannot change the props it receives.

3. **Dynamic**: Prop values can change if the data in the parent component
   changes.

#### Using props:

1. **In a functional component:**

```jsx
function Welcome(props) {
  return Hello, {props.name}!;
}

// Usage:
;
```

2. **In a class component:**

```jsx
class Welcome extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Usage:
;
```

#### Passing props:

```jsx
function App() {
  return (

  );
}
```

**Result:**

```bash
Hello, Alice!
Hello, Bob!
```

#### Props destructuring:

```jsx
function Welcome({ name }) {
  return Hello, {name}!;
}
```

#### Default prop values:

```jsx
function Welcome({ name = 'Guest' }) {
  return Hello, {name}!;
}

// Usage:
; // Outputs: Hello, Guest!
```

Props provide React components with flexibility and reusability.

</details>

<details>
<summary>11. Why is the `key` attribute needed when rendering lists?</summary>

#### React

The `key` attribute is used to identify elements in lists during rendering.

#### Purpose:

1. **_Update optimization:_** React uses `key` to efficiently update the UI by
   quickly determining which elements need to be changed, added, or removed.

2. **_Preventing unnecessary renders:_** `key` helps avoid rerendering unchanged
   elements.

3. **_Preserving component state:_** For example, if a list item contains a
   form, `key` allows React to preserve its state between updates.

#### Correct usage:

- The `key` value must be unique among sibling elements.

- Stable identifiers work best (for example, a database `id`).

- It is not recommended to use the array index as a `key`, because this can lead
  to errors when the order of elements changes.

```jsx
const items = ['Apple', 'Banana', 'Cherry'];
return (

    {items.map((item, index) => (
      {item} // Unique key for each element
    ))}

);
```

</details>

<details>
<summary>12. How is data passed between components in React?</summary>

#### React

In React, data is passed between components according to the hierarchy as
follows:

#### Passing data down (from parent to child)

Props are used to pass data down. The parent component passes values or
functions to the child component through attributes.

**Example:**

```jsx
function ParentComponent() {
  const data = 'Hello from Parent';

  return;
}

function ChildComponent({ message }) {
  return { message };
}
```

`message` passes the `data` value to the child component `ChildComponent`.

In the child component, props are accessed through the function parameter or
through `this.props` in a class component.

#### Passing data up (from child to parent)

Data is passed up using callback functions. The parent component passes a
function to the child, and the child calls it with the required data.

**Example:**

```jsx
function ParentComponent() {
  const handleData = childData => {
    console.log('Data from child:', childData);
  };

  return ;
}

function ChildComponent({ sendData }) {
  const data = 'Hello from Child';

  return <button onClick={() => sendData(data)}>Send Data;
}
```

The parent component passes the `handleData` function in the `sendData` prop.

The child component calls `sendData`, passing the `data` value.

#### Alternative approaches for complex applications:

1. **Context (Context API):**

Used to pass data deep through the hierarchy without props.

Suitable for global state, such as a theme or interface language.

```jsx
const MyContext = React.createContext();

function ParentComponent() {
  const data = 'Hello from Context';

  return (

  );
}

function ChildComponent() {
  const contextData = React.useContext(MyContext);

  return {contextData};
}
```

2. **State managers (Redux, Zustand, MobX):** For passing data in large
   applications through a single global state.

3. **Custom Hooks:** Used to share logic between components.

</details>

<details>
<summary>13. Why does React use `className` instead of the `class` attribute?</summary>

#### React

React uses `className` instead of `class` because `class` is a reserved keyword
in JavaScript.

#### Reasons:

1. **Avoiding conflicts**: `class` is used to define classes in JavaScript
   (`class MyComponent {}`), which could cause syntax errors.

2. **JSX compatibility**: JSX is a syntax extension of JavaScript, so using
   `className` helps avoid ambiguity.

3. **Direct mapping** in `document.createElement`: React transforms JSX into
   `React.createElement` calls, and `className` is used to set classes on DOM
   elements.

#### Example:

```jsx
// Correct variant in React

Hello;

// Incorrect variant (syntax error)

Hello;
```

This is a React standard that ensures stability and consistency in code.

</details>

<details>
<summary>14. What naming rules and exceptions exist for React components?</summary>

#### React

In React, there are several important rules and exceptions regarding component
names:

1. **Capital letters for components:** Component names must start with a capital
   letter. This is required so React can distinguish components from standard
   HTML elements.

For example:

- Correct: `<MyComponent />`
- Incorrect: `<myComponent />`

2. **CamelCase:** It is recommended to use CamelCase for component names. This
   means that each new word in the component name starts with a capital letter:

- `MyComponent`
- `UserProfile`

3. **Names should not match HTML elements:** Do not use component names that
   match standard HTML element tags such as `div`, `span`, `button`, and so on.
   This can cause conflicts and unexpected behavior:

- Correct: `<CustomButton />`
- Incorrect: `<button />` (although this is an HTML element, in React it will be
  treated as a standard HTML tag)

4. **Avoid special characters:** Do not use special characters in component
   names (for example, spaces, hyphens, underscores, and so on), because this
   can lead to syntax errors:

- Correct: `MyComponent`
- Incorrect: `my_component`, `my-component`

5. **Functional components vs. classes:** If you use classes for components,
   they must also have names that start with a capital letter:

- `class MyComponent extends React.Component {}`

Following these rules helps ensure correct behavior and clarity in the code.

</details>

<details>
<summary>15. How do you write comments in React?</summary>

#### React

In React, comments are written the same way as in JavaScript, but there are some
nuances when it comes to JSX.

1. **Comments in JavaScript (outside JSX)**

```javascript
// Single-line comment

/*
Multi-line comment
*/
```

2. **Comments inside JSX**

- In JSX, you need to use special syntax because JSX is part of JavaScript.

- Comments in JSX must be written inside curly braces `{}`:

```jsx
function MyComponent() {
  return (

      {/_ This is a comment inside JSX _/}
      Hello, world!

  );
}
```

- Comments in JSX must be wrapped in `{/* comment */}`, otherwise they cause
  errors.

- They can only be used inside JSX expressions.

3. **Comments in functions and methods**

- For comments inside functions or methods, you can use standard JavaScript
  comments:

```jsx
function MyComponent() {
  // This is where we render the component
  return Hello, world!;
}
```

#### Summary:

- In JSX, use `{/* comment */}`.

- In regular JavaScript, use `//` for single-line comments and `/* ... */` for
  multi-line comments.

</details>

<details>
<summary>16. What is the Virtual DOM in React?</summary>

#### React

The **Virtual DOM** is a virtual representation of the real DOM that React uses
to update the interface efficiently.

#### How it works in React:

1. **Rendering to the Virtual DOM:** When the state or props of components
   change, React updates the Virtual DOM.

2. **Diffing:** React compares the new Virtual DOM with the old version,
   determining the minimal set of changes.

3. **Updating the real DOM:** The detected changes are applied to the real DOM,
   minimizing the number of manipulations.

#### Main advantage:

Optimization of DOM updates, which significantly improves application
performance.

</details>

<details>
<summary>17. What is the `key` prop, and what is the advantage of using it in arrays of elements?</summary>

#### React

In React, the `key` prop is used to identify each element in lists or arrays in
order to help React efficiently manage renders when list items change or are
updated. This is important for optimizing the rendering process, especially when
the list changes (items are added, removed, or modified).

#### Key points about `key`:

1. **Uniqueness:** Each element in a list must have a unique `key`. This allows
   React to track which elements are changing, being added, or being removed,
   and also to preserve their state between renders.

2. **Rendering optimization:** Using `key` allows React to minimize the number
   of rerenders by making only the necessary changes to the DOM. Without `key`,
   React has a harder time tracking changes, which can lead to a full rerender
   of the list even if only one item changed.

3. **Nature of `key`:** The `key` prop is not passed into the component, so it
   cannot be used to display values in the UI. It is an internal property used
   by React only for tracking elements.

#### Example of using `key` in a list:

```jsx
const items = ['apple', 'banana', 'cherry'];

function FruitList() {
  return (

      {items.map((item, index) => (
        {item} // Important: use a unique key
      ))}

  );
}
```

#### The importance of `key` uniqueness:

- **Incorrect usage:** If non-unique values are used as keys (for example, the
  same index), React will not be able to correctly track changes, and this will
  lead to rendering errors.

- **Ideal key:** Usually, if there is a unique identifier for an element (for
  example, an id), it should be used as the key instead of the array index.

```jsx
const items = [
  { id: 1, name: 'apple' },
  { id: 2, name: 'banana' },
  { id: 3, name: 'cherry' },
];

function FruitList() {
  return (

      {items.map(item => (
        {item.name} // It is better to use unique ids
      ))}

  );
}
```

#### Advantages of using `key`:

- Improves rendering performance.

- Allows React to optimally update only the changed elements instead of the
  entire list.

- Ensures correct handling of element state when items are moved, removed, or
  updated.

Thus, using `key` is important for working efficiently with arrays of elements
in React.

</details>

<details>
<summary>18. What is conditional rendering in React?</summary>

#### React

Conditional rendering in React is the process in which a component renders
different content depending on certain conditions. This makes it possible to
dynamically change what the component displays based on state, props, or other
factors.

#### Main approaches to conditional rendering:

1. **The `if` operator:** You can use the standard `if` operator to decide what
   to render.

```jsx
function Greeting(props) {
  if (props.isLoggedIn) {
    return Welcome back!;
  }
  return Please sign up.;
}
```

2. **Ternary operator:** The ternary operator is often used for shorter
   conditional expressions.

```jsx
function Greeting(props) {
  return {props.isLoggedIn ? 'Welcome back!' : 'Please sign up.'};
}
```

3. **Logical AND (`&&`) for rendering:** You can use the logical `&&` operator
   to render an element only if the expression to its left is truthy.

```jsx
function Notifications(props) {
  return (

      {props.unreadMessages.length > 0 && (
        You have {props.unreadMessages.length} unread messages.
      )}

  );
}
```

This works as follows: if `props.unreadMessages.length` is greater than `0`, the
message will be displayed; otherwise, nothing will be rendered.

4. **Using `return` with a conditional operator:** You can use `return` for
   conditional rendering based on different conditions, as in the example with
   `if` or the ternary operator.

#### Advantages of conditional rendering:

- Allows content to change dynamically depending on state or props.

- Improves flexibility and the ability to display different content for
  different users or situations.

#### Example:

```jsx
function UserStatus(props) {
  return (

      {props.isLoggedIn ? (
        Log Out
      ) : (
        Log In
      )}

  );
}
```

Here the button changes depending on whether the user is logged in.

</details>

<details>
<summary>19. What are Fragments in React?</summary>

#### React

Fragments in React are a way to group multiple elements without adding extra
elements to the DOM. They allow you to return several elements from a component
without a wrapper such as `div`, which helps avoid unnecessary elements that
could break styles or document structure.

#### How are Fragments used?

1. **Without Fragments (with a wrapper):**

```jsx
function MyComponent() {
  return (

      Title
      Some text

  );
}
```

In this example, a single `div` is returned that wraps `h1` and `p`.

2. **With Fragments (without a wrapper):**

```jsx
function MyComponent() {
  return <>Title Some text</>;
}
```

Now `h1` and `p` are rendered without an additional container, which helps keep
the DOM clean.

#### Advantages:

- **Clean DOM:** You can avoid unnecessary wrappers in the DOM.

- **Convenient for rendering multiple elements:** You can return several
  elements from one component without needing extra wrapper elements.

#### Syntax:

- You can use empty tags `<>` and `</>`, which are shorthand for
  `<React.Fragment></React.Fragment>`.

- You can also use `React.Fragment` if you need to add keys (for example, when
  rendering lists):

```jsx
{
  item.name;
}
{
  item.description;
}
```

#### When to use:

- When you need to render multiple elements without an additional wrapper in the
  DOM.

- When you want to preserve the component structure without affecting styles or
  layout.

Fragments are very useful for reducing unnecessary DOM elements and improving
performance.

</details>

<details>
<summary>20. What is Reconciliation?</summary>

#### React

**Reconciliation** is the process React uses to update the DOM in the most
efficient way. When a component's state or props change, React calculates the
minimal changes that need to be made to the real DOM in order to synchronize it
with the state of the virtual DOM.

#### How does reconciliation work?

1. **Comparing the old and new virtual DOM:**

- React keeps a copy of the previous virtual DOM.
- When state or props change, a new virtual DOM is created.
- React compares the new virtual DOM with the previous copy (the diffing
  algorithm).

2. **Detecting differences (diffing):**

- React identifies which parts of the tree have changed (new elements, changes
  in attributes, or element removal).
- For this, it uses an algorithm optimized for tree-like structures.

3. **Updating the real DOM:**

- React applies changes only to the parts of the DOM that need updating,
  avoiding a full rerender.

#### Main principles of reconciliation:

- **Preserving nodes of the same level:** If nodes have the same type (for
  example, `<div>` remains `<div>`), React changes only the attributes and child
  elements.
- **Reusing components:** If the component remains the same, React reuses the
  existing component instance.
- **Keys for lists:** If a list of elements is rendered from an array, React
  uses keys (the `key` prop) to compare and preserve nodes.

#### Example:

```jsx
function App({ isVisible }) {
  return isVisible ? Hello : Goodbye;
}
```

- If `isVisible` changes from `true` to `false`, React will remove `<h1>` and
  replace it with `<p>`.

#### The importance of keys (the `key` prop) for lists:

Keys help React correctly determine changes in lists. For example:

```jsx

  {items.map(item => (
    {item.text}
  ))}

```

Without unique keys, React will not be able to accurately determine which list
elements have changed.

#### Advantages of reconciliation:

- Reduces the number of DOM operations.
- Improves application performance.
- Provides smooth UI updates.

</details>

<details>
<summary>21. How do you update a component's state?</summary>

#### React

In React, a component's state is updated using the `setState` method in class
components or `useState` in functional components.

#### Class components:

State is updated through `this.setState()`.

#### Example:

```jsx
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        Count: {this.state.count}
        Increment

    );
  }
}
```

#### Functional components:

State is updated through the function returned by `useState`.

#### Example:

```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  const increment = () => {
    setCount(count + 1);
  };

  return (

      Count: {count}
      Increment

  );
}
```

#### Notes:

1. **Asynchronicity:** `setState` and `useState` work asynchronously. To update
   state based on the previous value, use the functional approach:

```jsx
this.setState(prevState => ({ count: prevState.count + 1 }));
setCount(prevCount => prevCount + 1);
```

2. **Do not update state directly:** Modifying state without using `setState` or
   `useState` does not trigger a rerender.

</details>

<details>
<summary>22. What are inline conditional expressions?</summary>

#### React

**Inline conditional expressions** in JavaScript (including React) are
mechanisms that allow conditions to be embedded directly into JSX for
conditionally rendering elements or components. This makes code more compact and
easier to understand.

#### Main methods:

1. **Conditional operator (ternary operator):** This is one of the most common
   ways to conditionally render elements in JSX. It has the following syntax:

```jsx
condition ? expression_if_true : expression_if_false;
```

**Example:**

```jsx
const isLoggedIn = true;

function App() {
  return {isLoggedIn ? Welcome, User! : Please log in};
}
```

2. **Logical AND operator (`&&`):** This method allows a component or element to
   be displayed only when the condition is `true`. If the condition is not met,
   nothing is rendered.

**Example:**

```jsx
const isUserAdmin = true;

function App() {
  return {isUserAdmin && You have admin privileges};
}
```

In this case, `<p>You have admin privileges</p>` will be displayed only if
`isUserAdmin` is `true`.

3. **`if` before returning JSX:** You can also use regular `if` statements
   before returning JSX when the condition is more complex or when you need to
   perform several conditional actions.

**Example:**

```jsx
function App() {
  let content;
  if (isLoggedIn) {
    content = Welcome back!;
  } else {
    content = Please sign in.;
  }

  return {content};
}
```

**Advantages:**

- Inline conditional expressions allow you to write cleaner and more compact
  code.

- They improve readability and reduce the need for extra conditional structures.

#### Important:

- In React, you cannot use `if` statements directly inside JSX. However, you can
  use them before returning JSX.

</details>

<details>
<summary>23. What is the difference between event handling in HTML and React?</summary>

#### React

#### Difference between event handling in HTML and React:

| Criterion                  | HTML                                                             | React                                                                       |
| -------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------------------------- |
| **Event binding**          | Specified as an attribute: `<button onclick="handler()">`.       | Uses camelCase: `<button onClick={handler}>`.                               |
| **Function type**          | Reference to a global function or a string with JavaScript code. | Bound to a component function (usually a method or arrow function).         |
| **Adding event listeners** | Handlers are added manually via `addEventListener`.              | React automatically manages binding through the virtual DOM.                |
| **`this` context**         | Context must be set manually if used in classes.                 | React preserves the correct context automatically in functional components. |
| **Default behavior**       | `return false` must be called explicitly to stop behavior.       | `event.preventDefault()` is used to stop default behavior.                  |
| **Compatibility**          | Handles only real DOM events.                                    | Uses `SyntheticEvent`, which is a wrapper over native events.               |
| **Cross-browser support**  | Browser differences must be handled manually.                    | React provides cross-browser compatibility through `SyntheticEvent`.        |
| **Context binding**        | Often requires using `bind`.                                     | `bind` is needed in class components, but not in functional ones.           |

#### Example in HTML:

```html
Click me
```

#### Example in React:

```jsx
function handleClick() {
  alert('Clicked!');
}

function App() {
  return Click me;
}
```

#### SyntheticEvent in React:

React uses a wrapper over native events that normalizes behavior across
different browsers and improves performance.

</details>

<details>
<summary>24. What are synthetic events in React?</summary>

#### React

**Synthetic events** in React are wrappers around native DOM events that provide
a consistent interface for handling events across different browsers. React
creates a `SyntheticEvent` for each event, which allows events to be handled in
a unified way, ensuring cross-browser compatibility and improving performance.

#### Main characteristics:

1. **Cross-browser compatibility:** `SyntheticEvent` abstracts browser-specific
   event behavior and provides consistent behavior.

2. **Optimization:** `SyntheticEvent` uses object pooling, which helps reduce
   the cost of creating new event objects.

3. **Single use:** After the event is handled, the `SyntheticEvent` object is
   "returned" to the pool and cannot be used afterward. For asynchronous
   operations, the event should be stored in a separate variable.

4. **Interface:** `SyntheticEvent` has the same methods as standard native
   events (for example, `preventDefault()` and `stopPropagation()`).

#### Example:

```jsx
function handleClick(event) {
  // SyntheticEvent provides access to the preventDefault() method
  event.preventDefault();
  console.log('Button clicked!');
}

function App() {
  return Click me;
}
```

In this example, `event` is a `SyntheticEvent` that works similarly to a native
event, but with improved capabilities.

</details>

<details>
<summary>25. How do you handle events in React?</summary>

#### React

In React, event handling works similarly to standard JavaScript, but with some
differences. Events in React are synthetic, which means they provide an
abstraction over real browser events and ensure cross-browser compatibility.

#### Main principles of event handling in React:

1. **Synthetic events:** All events in React are wrapped in a **SyntheticEvent**
   object, which is a cross-browser implementation of standard DOM events. This
   allows events to be handled uniformly in all browsers.

2. **Using camelCase for events:** In React, events are written in camelCase
   instead of lowercase (for example, `onClick` instead of `onclick`).

3. **Passing functions as event handlers:** Events in React are handled using
   functions passed through component attributes.

#### Example of handling a `click` event:

```jsx
import React, { Component } from 'react';

class MyButton extends Component {
  handleClick = () => {
    alert('Button clicked!');
  };

  render() {
    return Click Me;
  }
}

export default MyButton;
```

#### Example with a functional component:

```jsx
import React, { useState } from 'react';

function MyButton() {
  const [count, setCount] = useState(0);

  const handleClick = () => {
    setCount(count + 1);
  };

  return Clicked {count} times;
}

export default MyButton;
```

#### Event handling features:

1. **No need to use `addEventListener`:** In React, there is no need to manually
   add or remove event handlers. This is managed automatically by the React
   library.

2. **Preserving context in class component methods:** If class component methods
   are used as event handlers, the `this` context must be bound either with
   arrow functions or manually in the constructor.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
    // Method binding
    this.handleClick = this.handleClick.bind(this);
  }

  handleClick() {
    this.setState({ count: this.state.count + 1 });
  }

  render() {
    return (

        Clicked {this.state.count} times

    );
  }
}
```

3. **Passing parameters to a handler function:** If you need to pass additional
   arguments to an event handler, you can use arrow functions or parameterized
   functions.

```jsx
function MyButton({ label }) {
  const handleClick = (event, label) => {
    console.log(label);
  };

  return <button onClick={event => handleClick(event, label)}>{label};
}
```

#### Event handling in the DOM:

All events in React work according to the principle of event delegation, where
one event handler is registered for the entire component tree and routed through
React `SyntheticEvent`.

</details>

<details>
<summary>26. What are Pointer Events?</summary>

#### React

#### Pointer Events in React

**Pointer Events** are an API that unifies mouse, touch, and stylus events into
a single event handling system.

#### Main Pointer Events

| **Event**           | **Description**                                                          |
| ------------------- | ------------------------------------------------------------------------ |
| **onPointerDown**   | Fires when pressing with a finger, mouse, or stylus.                     |
| **onPointerUp**     | Fires when releasing the mouse button, finger, or stylus.                |
| **onPointerMove**   | Fires when the pointer moves over an element.                            |
| **onPointerEnter**  | Fires when the pointer enters an element's boundaries.                   |
| **onPointerLeave**  | Fires when the pointer leaves an element's boundaries.                   |
| **onPointerCancel** | Fires when the browser cancels the event (for example, on focus change). |

#### Example in React

```jsx
const PointerExample = () => {
  const handlePointerDown = () => console.log('Pointer pressed');

  return (

      Click here

  );
};
```

This code will log `"Pointer pressed"` to the console when pressed with any
device (mouse, touch, or stylus).

</details>

<details>
<summary>27. When should you use a class component instead of a functional component?</summary>

#### React

Class components used to be used when one or more of these features were needed:

1. **Working with state:** Previously, functional components did not support
   local state, so classes were used for this purpose. Today, hooks (`useState`,
   `useReducer`) allow functional components to work with state.

2. **Lifecycle methods:** Classes provided access to methods such as
   `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount` for
   managing a component at different stages of its existence. Today, this is
   handled with the `useEffect` hook.

3. **Handling complex logic:** If logic required several methods and access to
   properties through `this`, classes seemed like a logical choice. The modern
   approach is hooks, which allow logic to be encapsulated.

#### When classes are no longer needed:

Starting with React 16.8, functional components with hooks replaced the need for
class components. Therefore, in new projects, preference should be given to
functional components. Classes are used mainly for maintaining legacy code.

</details>

<details>
<summary>28. What are stateless components?</summary>

#### React

Stateless components are components that do not store or manage any internal
state. They only receive data through props and display it as UI. Usually, these
components are functional.

#### Features:

1. **No state:** They do not use `this.state` and do not change their internal
   state.

2. **Rendering only:** They simply receive props and display them as UI
   elements.

3. **Simplicity and predictability:** They are easier to test and maintain,
   since there is no need to track state changes.

#### Example:

```jsx
// Stateless component
function Greeting(props) {
  return Hello, {props.name}!;
}

// Usage:
;
```

#### Advantages:

- **Simplicity:** Easier to understand and maintain.

- **Performance optimization:** Since these components have no state, React can
  update them more efficiently.

#### When to use:

- When a component simply displays data and does not need to change.

</details>

<details>
<summary>29. What are stateful components?</summary>

#### React

**Stateful components** are components that store and manage their internal
state. They use state to store data that can change over time, and these changes
affect the rendering of the component.

#### Features:

1. **State:** They use `this.state` to store and manage data that can change.

2. **Methods for updating state:** They use the `this.setState()` method to
   update state.

3. **Lifecycle:** They have access to component lifecycle methods such as
   `componentDidMount()`, `shouldComponentUpdate()`, `componentDidUpdate()`, and
   so on.

#### Example:

```jsx
// Stateful component
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      count: 0,
    };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        {this.state.count}
        Increment

    );
  }
}
```

#### Advantages:

- **Dynamic components:** They can change their content and appearance based on
  state changes.

- **Interactivity:** They are suitable for building interactive interfaces where
  state needs to be updated in response to user interaction.

#### When to use:

When a component needs to manage internal state, for example, to store form
input, a counter, selections, and so on.

</details>

<details>
<summary>30. What are Pure Components?</summary>

#### React

**Pure Components** are special React class components that automatically
optimize rendering. They implement a shallow comparison of props and state to
prevent unnecessary updates if the values of props or state have not changed.

#### How do you create a Pure Component?

A Pure Component is created by extending `React.PureComponent`.

```jsx
import React, { PureComponent } from 'react';

class MyComponent extends PureComponent {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Usage:
;
```

#### How does `PureComponent` work?

- It performs a shallow comparison of props and state in the
  `shouldComponentUpdate` method.

- If props and state have not changed, the component does not rerender.

#### When should you use `PureComponent`?

- When props and state are simple structures (primitive values or shallow
  objects).

- To improve performance in components that update frequently.

#### Limitations:

1. **Deep comparison:** `PureComponent` does not account for changes inside
   nested objects or arrays. For example, if you update an object but the
   reference to it remains unchanged, the component will not update.

```jsx
this.setState({ data: { ...this.state.data, key: 'new value' } }); // Workaround
```

2. **Does not work with functional components:** The alternative is to use
   `React.memo` to optimize functional components.

```jsx
const MyComponent = React.memo(function MyComponent(props) {
  return Hello, {props.name}!;
});
```

</details>

<details>
<summary>31. What are Higher-Order Components (HOCs)?</summary>

#### React

A **Higher-Order Component** is a function that takes a component as an input
argument and returns a new component, extending its functionality.

#### HOC syntax:

```jsx
const EnhancedComponent = higherOrderComponent(WrappedComponent);
```

#### HOC features:

1. **Takes a component as an argument.**
2. **Returns a new component with additional props or behavior.**
3. **Allows logic to be reused across different components.**

#### Example:

An HOC for adding state to a component:

```jsx
import React, { useState } from 'react';

// HOC: adds state logic
function withCounter(WrappedComponent) {
  return function EnhancedComponent(props) {
    const [count, setCount] = useState(0);

    const increment = () => setCount(count + 1);

    return ;
  };
}

// Component to be enhanced
function Button({ count, increment }) {
  return Clicked {count} times;
}

// HOC usage
const EnhancedButton = withCounter(Button);

export default EnhancedButton;
```

#### Real-world HOC use cases:

1. **Authentication:** Wrapping components to check access rights.

2. **Data handling:** Connecting to APIs or processing state.

3. **Logging:** Adding logging for component actions.

#### HOC limitations:

- It can create deep nesting in the component tree if too many HOCs are used.

- It can reduce readability because of the extra component wrapping.

HOCs are a powerful tool for reusing logic, but in modern applications they are
often replaced by React Hooks.

</details>

<details>
<summary>32. What is the `children` prop?</summary>

#### React

#### What is the `children` prop?

`children` is a special prop in React that is used to pass nested elements or
components into a wrapper component.

#### How does it work?

When you pass child content between the opening and closing tags of a component,
that content is automatically passed as `props.children`.

#### Example:

- **Wrapper component:**

```jsx
function Wrapper({ children }) {
  return { children };
}
```

- **Usage:**

```jsx
function App() {
  return (

      Hello, World!
      This is a paragraph inside the wrapper.

  );
}
```

- **Result:**

```html
Hello, World! This is a paragraph inside the wrapper.
```

#### Key features of `children`:

1. **Flexibility:** You can pass any type of data: text, JSX, components, or
   arrays of elements.

2. **Reusability:** A wrapper component can dynamically render different
   content.

3. **Structured composition:** Helps create components with a nested structure.

#### Using `children` with function props:

Sometimes `children` is used as a function for dynamically passing data:

```jsx
function List({ items, children }) {
  return {items.map(item => children(item))};
}

function App() {
  return (
    <List items={['Apple', 'Banana', 'Cherry']}>
      {item => {item}}

  );
}
```

#### Result:

```html
Apple Banana Cherry
```

`children` is a powerful tool for creating universal and reusable components in
React.

</details>

<details>
<summary>33. What is a Portal?</summary>

#### React

A **Portal** in React is a way to render child elements into a DOM node that
exists outside the DOM hierarchy of the parent component.

#### How it works:

React provides portals through the `ReactDOM.createPortal` method, which takes
two arguments:

1. **The React element** to render.

2. **The target DOM node** where the element should be inserted.

#### Syntax:

```jsx
ReactDOM.createPortal(child, container);
```

- **`child`** is the React element to render.

- **`container`** is the DOM node where the element will be inserted.

#### Example:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';

function Modal({ children }) {
  return ReactDOM.createPortal(
    {children},
    document.getElementById('modal-root') // Target node
  );
}

function App() {
  return (

      Main content

        This is modal content


  );
}
```

#### Where portals are used:

- Modals.

- Tooltips.

- Context menus.

#### Features:

1. **Event hierarchy:** Although the element is rendered outside the DOM
   hierarchy, event handling still follows the React component hierarchy. For
   example, `onClick` events will bubble up to parent React components.

2. **Flexibility:** Portals let you insert elements into places that do not fit
   into the current DOM structure.

#### Advantages:

- Easy management of "floating" elements.
- Preserves React context even outside the main DOM hierarchy.

</details>

<details>

<summary>34. How do Portals work in React, and what are their advantages and main UI use cases?</summary>

#### React

**Portals** in React allow child elements to be rendered into another part of
the DOM rather than the component's default render location. This is useful for
placing elements that should exist outside the usual DOM hierarchy, such as
modals, tooltips, or floating elements.

#### Main advantages of portals:

- They make it possible to render elements in another place in the DOM without
  breaking the React component structure.

- They are useful when elements need to be rendered over other content (for
  example, modals or pop-up menus).

#### How portals work:

- A portal lets you send content to any place in the DOM, even outside the root
  React container.

#### Portal example:

```jsx
import ReactDOM from 'react-dom';

const Modal = () => {
  return ReactDOM.createPortal(
    <div className="modal">
      <h1>This is a modal window</h1>
    </div>,
    document.getElementById('modal-root') // The DOM node where the portal is rendered
  );
};

const App = () => {
  return (
    <div>
      <h1>Main page</h1>
      <Modal />
    </div>
  );
};
```

#### Key points:

- `ReactDOM.createPortal()` is used to create a portal. The first argument is
  the content to render, and the second argument is the DOM element into which
  that content is inserted.

- Portals can be used for modals, tooltips, pop-up menus, and other elements
  that need to be displayed outside the main component tree.

#### Features:

- Although elements rendered through portals are outside the main React
  component hierarchy, they still have access to the context, state, and props
  of their parents.

- Portals are useful when elements need to be positioned "above" other content
  or at another level of the DOM hierarchy (for example, a modal that should not
  be constrained by a parent container).

Portals let you preserve component logic and structure without breaking DOM
rules, which helps create clean and convenient UI components.

</details>

<details>
<summary>35. What are the component lifecycle methods in React?</summary>

#### React

Component lifecycle methods in React are used to manage different stages of a
component's life: creation, updating, and removal.

#### Main lifecycle phases:

1. **Mounting:** When a component is added to the DOM.

`constructor()`: Initializes state and binds methods.

`static getDerivedStateFromProps(props, state)`: Updates state before render
(rarely used).

`render()`: Renders JSX into the virtual DOM.

`componentDidMount()`: Called immediately after the component is added to the
DOM. Used for API requests and library initialization.

2. **Updating:** When props or state change.

`static getDerivedStateFromProps(props, state)`: Called before each render.

`shouldComponentUpdate(nextProps, nextState)`: Controls whether the component
should rerender. By default, it returns `true`.

`render()`: Runs to update the virtual DOM.

`getSnapshotBeforeUpdate(prevProps, prevState)`: Gets a snapshot before changes
(for example, the scroll position).

`componentDidUpdate(prevProps, prevState, snapshot)`: Called after an update.
Used for repeated requests or DOM work.

3. **Unmounting:** When a component is removed from the DOM.

`componentWillUnmount()`: Used for cleaning up resources (for example, timers or
subscriptions).

4. **Error handling:** When a component throws an error.

`static getDerivedStateFromError(error)`: Lets you update state after an error.

`componentDidCatch(error, info)`: Logs errors.

#### Method table:

| Phase              | Method                       | Description                               |
| ------------------ | ---------------------------- | ----------------------------------------- |
| **Mounting**       | `constructor()`              | State initialization and setup.           |
|                    | `getDerivedStateFromProps()` | Updates state before render.              |
|                    | `render()`                   | Renders JSX into the virtual DOM.         |
|                    | `componentDidMount()`        | Runs after adding to the DOM.             |
| **Updating**       | `getDerivedStateFromProps()` | Updates state before render.              |
|                    | `shouldComponentUpdate()`    | Determines whether rerendering is needed. |
|                    | `render()`                   | Updates the virtual DOM.                  |
|                    | `getSnapshotBeforeUpdate()`  | Gets a snapshot of state before update.   |
|                    | `componentDidUpdate()`       | Runs after updating.                      |
| **Unmounting**     | `componentWillUnmount()`     | Cleans up resources before removal.       |
| **Error handling** | `getDerivedStateFromError()` | Updates state on error.                   |
|                    | `componentDidCatch()`        | Logs errors.                              |

#### Modern approach:

In functional components, **hooks** are used instead of lifecycle methods:

- `useEffect` replaces `componentDidMount`, `componentDidUpdate`, and
  `componentWillUnmount`.

- `useState` is used for state management.

</details>

<details>
<summary>36. What does the `shouldComponentUpdate` method do?</summary>

#### React

- `shouldComponentUpdate` is a lifecycle method in class components that
  determines whether a component should rerender.

#### How it works:

- By default, it returns `true`, which means the component rerenders whenever
  `state` or `props` changes.

- If it returns `false`, React will not rerender the component even if `props`
  or `state` changed.

#### Example:

```jsx
class MyComponent extends React.Component {
  shouldComponentUpdate(nextProps, nextState) {
    return nextProps.value !== this.props.value; // Rerender only when value changes
  }

  render() {
    return <div>{this.props.value}</div>;
  }
}
```

#### Alternative in functional components:

- Use `React.memo()` for memoization.

- `useMemo()` and `useCallback()` help optimize rerenders.

</details>

<details>
<summary>37. How do you run code before removing a component from the tree?</summary>

#### React

To run code before removing a component from the tree in React, the following
approaches are used:

1. **Class components:** `componentWillUnmount`

For class components, there is a `componentWillUnmount` lifecycle method that is
called before the component is removed.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Component will be removed');
  }

  render() {
    return <div>My component</div>;
  }
}
```

2. **Functional components:** `useEffect` with cleanup

In functional components, cleanup can be done in `useEffect` by returning a
function that will run before the component is removed.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Component will be removed');
    };
  }, []);

  return <div>My component</div>;
}
```

3. **Handling before page close (`beforeunload`)**

If you need to run code before closing the tab or reloading the page:

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('Page is closing');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Summary

- `componentWillUnmount` is for class components.

- `useEffect` with `return` is for functional components.

- `beforeunload` is for cases where you need to react to leaving the page.

</details>

<details>
<summary>38. Why are Fragments better than container `div`s?</summary>

#### React

Fragments (`<React.Fragment>` or `<>...</>`) are better than container `<div>`
elements in React for several reasons:

1. **Reducing unnecessary HTML**

- Fragments do not add an extra element to the DOM, which reduces the number of
  nested tags and improves performance.

```jsx
<>
  <h1>Title</h1>
  <p>Text</p>
</>
```

- Result in the DOM:

```html
<h1>Title</h1>
<p>Text</p>
```

- Unlike `<div>`, which would add unnecessary nesting:

```html
<div>
  <h1>Title</h1>
  <p>Text</p>
</div>
```

2. **No styling side effects**

- An extra `<div>` can affect CSS styles and cause unwanted layout changes.
  Fragments avoid this.

3. **Better compatibility with tables**

- You cannot place a `<div>` directly inside a `<table>`, but you can use
  Fragments:

```jsx
<>
  <tr>
    <td>Row 1</td>
  </tr>
  <tr>
    <td>Row 2</td>
  </tr>
</>
```

- This works correctly, whereas a `<div>` would cause an error.

4. **Performance optimization**

- Fewer unnecessary nodes in the DOM means faster rendering and lower memory
  usage.

</details>

<details>
<summary>39. What are Hooks in React?</summary>

#### React

**React Hooks** are functions that let you use state and other React features
without writing classes.

#### Main types of hooks:

1. **useState** lets you add state to functional components.

```jsx
const [state, setState] = useState(initialState);
```

2. **useEffect** lets you perform side effects (for example, API requests or
   subscriptions) in functional components.

```jsx
useEffect(() => {
  // effect code
}, [dependencies]); // dependencies
```

3. **useContext** gives access to context values without needing to use a
   Consumer component.

```jsx
const value = useContext(MyContext);
```

4. **useRef** lets you create references to DOM elements or store values between
   renders without changing state.

```jsx
const myRef = useRef(initialValue);
```

5. **useReducer** is an alternative to `useState`, useful for managing more
   complex state through reducers, similar to Redux.

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

6. **useMemo** optimizes value calculations to avoid unnecessary recomputation.

```jsx
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b]);
```

7. **useCallback** returns a memoized version of a function so it is not
   recreated on every render.

```jsx
const memoizedCallback = useCallback(() => {
  // function;
}, [dependencies]);
```

#### Main advantages:

- **Functional components:** Instead of class components, you can use functional
  components with hooks.

- **Improved readability:** Logic can be split into several hooks, which reduces
  the amount of code and increases modularity.

- **Logic reuse:** Hooks allow logic to be reused across different components
  without creating complex hierarchies.

</details>

<details>
<summary>40. What are the advantages of Hooks in React?</summary>

#### React

| **Advantage**                   | **Description**                                                              |
| ------------------------------- | ---------------------------------------------------------------------------- |
| **Less code**                   | Hooks let you avoid classes and reduce the amount of code.                   |
| **Better readability**          | Code with hooks is easier to understand and maintain.                        |
| **Logic reuse**                 | Custom Hooks let you reuse logic between components.                         |
| **Simplified state management** | Using `useState` and `useReducer` makes state management simpler.            |
| **Flexibility with effects**    | `useEffect` lets you perform side effects without class lifecycle methods.   |
| **Easier migration**            | It simplifies the transition from class components to functional components. |

</details>

<details>
<summary>41. What are the disadvantages of Hooks in React?</summary>

#### React

| **Disadvantage**                     | **Description**                                                                               |
| ------------------------------------ | --------------------------------------------------------------------------------------------- |
| **Increased number of rerenders**    | Incorrect use of hooks, especially `useEffect`, can cause unnecessary rerenders.              |
| **More complex logic comprehension** | Component logic may be spread across several `useEffect` calls, which makes debugging harder. |
| **No explicit lifecycle**            | Unlike class components, hooks do not have clearly expressed lifecycle methods.               |
| **Possible optimization issues**     | Incorrect use of `useCallback` and `useMemo` can lead to inefficient behavior.                |
| **Complexity in large projects**     | In large applications, hooks can make state and side-effect management more difficult.        |

</details>

<details>
<summary>42. What are the rules and limitations of using Hooks in React?</summary>

#### React

| **Rule**                       | **Description**                                                                                                                |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| **Use only in functions**      | Hooks can only be called in functional components or custom hooks.                                                             |
| **Preserve call order**        | Hooks cannot be called conditionally (`if`, `for`, `while`), otherwise the call order breaks.                                  |
| **Call only at the top level** | Hooks cannot be called inside nested functions or event handlers.                                                              |
| **Custom hook naming**         | Custom hooks must start with `use` (for example, `useAuth`).                                                                   |
| **Follow dependency rules**    | In `useEffect`, `useMemo`, and `useCallback`, dependencies (`[]`) must be specified correctly to avoid unpredictable behavior. |

</details>

<details>
<summary>43. What is `useReducer()`?</summary>

#### React

`useReducer()` is a React hook used for state management in functional
components. It is an alternative to `useState()` that is suitable for complex
state update logic, especially when changes depend on the previous state.

#### Syntax:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` is a function that takes `state` and `action` and returns a new
  state.

- `initialState` is the initial state.

- `dispatch` is the function used to call the reducer with a specific `action`.

#### Example:

```jsx
import { useReducer } from 'react';

const initialState = { count: 0 };

function reducer(state, action) {
  switch (action.type) {
    case 'increment':
      return { count: state.count + 1 };
    case 'decrement':
      return { count: state.count - 1 };
    default:
      return state;
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, initialState);

  return (
    <div>
      <p>Count: {state.count}</p>
      <button onClick={() => dispatch({ type: 'increment' })}>+</button>
      <button onClick={() => dispatch({ type: 'decrement' })}>-</button>
    </div>
  );
}
```

#### When to use:

- When state has complex logic or dependencies.

- When you need to standardize state updates through `dispatch`.

- For scalability, for example, when used in global state.

</details>

<details>
<summary>44. Tell us about `useCallback()`, `useMemo()`, `useImperativeHandle()`, and `useLayoutEffect()`.</summary>

#### React

#### `useCallback()`

Memoizes a function so that it is not recreated on every render. Useful for
passing callbacks to child components.

- **Example:**

```jsx
import { useCallback } from 'react';

function MyComponent({ onClick }) {
  return <button onClick={onClick}>Click</button>;
}

function Parent() {
  const handleClick = useCallback(() => {
    console.log('Click');
  }, []); // The function is created once

  return <MyComponent onClick={handleClick} />;
}
```

#### `useMemo()`

Memoizes calculations so they are not recomputed on every render if the
dependencies have not changed.

#### Example:

```jsx
import { useMemo } from 'react';

function ExpensiveCalculation({ num }) {
  const result = useMemo(() => {
    console.log('Calculating...');
    return num * 2;
  }, [num]); // Runs only when num changes

  return <div>Result: {result}</div>;
}
```

#### `useImperativeHandle()`

Lets you control the behavior of a ref in a child component. It is used together
with `forwardRef()`.

#### Example:

```jsx
import { useRef, useImperativeHandle, forwardRef } from 'react';

const CustomInput = forwardRef((props, ref) => {
  const inputRef = useRef();

  useImperativeHandle(ref, () => ({
    focus: () => inputRef.current.focus(),
    clear: () => (inputRef.current.value = ''),
  }));

  return <input ref={inputRef} {...props} />;
});

function Parent() {
  const inputRef = useRef();

  return (
    <div>
      <CustomInput ref={inputRef} />
      <button onClick={() => inputRef.current.focus()}>Focus</button>
      <button onClick={() => inputRef.current.clear()}>Clear</button>
    </div>
  );
}
```

#### `useLayoutEffect()`

Works like `useEffect()`, but runs synchronously after DOM changes. It is useful
for measuring or manipulating the DOM before the browser paints the page.

- **Example:**

```jsx
import { useLayoutEffect, useRef } from 'react';

function LayoutEffectExample() {
  const divRef = useRef();

  useLayoutEffect(() => {
    console.log('Element width:', divRef.current.offsetWidth);
  }, []);

  return (
    <div ref={divRef} style={{ width: '200px', height: '100px' }}>
      Element
    </div>
  );
}
```

#### When should each hook be used?

- `useCallback()` for memoizing functions.

- `useMemo()` for memoizing calculations.

- `useImperativeHandle()` for controlling a child component's ref.

- `useLayoutEffect()` when something needs to be done before DOM changes are
  painted (for example, measuring).

</details>

<details>
<summary>45. How do you implement a one-time operation during the initial render?</summary>

#### React

To perform an operation only once during the initial render in functional
components, use `useEffect` with an empty dependency array (`[]`):

#### Example:

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    console.log('This will run only once after the component mounts');
  }, []);

  return <div>Component</div>;
}
```

#### Explanation:

- `useEffect(() => { /* code */ }, [])`: an empty dependency array means the
  effect runs only once after the first render, similar to `componentDidMount`
  in class components.

#### Additionally (for example, subscription/unsubscription):

```jsx
useEffect(() => {
  const interval = setInterval(() => {
    console.log('One-time effect is running');
  }, 1000);

  return () => clearInterval(interval); // Cleanup on unmount
}, []);
```

This approach is useful for initializing API requests, subscriptions, timers,
and so on.

</details>

<details>
<summary>46. What is Context?</summary>

#### React

**Context** in React is a mechanism for passing data through the component tree
without needing to pass those data through props at every level.

#### How Context works:

1. **`React.createContext()`** is used to create a context.

```jsx
const MyContext = React.createContext(defaultValue);
```

2. **Provider** is the component that provides the context value. It wraps part
   of the component tree and passes the value down through `value`.

```jsx
<MyContext.Provider value={}>
  <YourComponent />
</MyContext.Provider>
```

3. **Consumer** is the component that consumes the context value. It usually
   uses a function as a child element that receives the context value.

```jsx
<MyContext.Consumer>
{value => }
</MyContext.Consumer>
```

4. **`useContext`** is a hook that allows access to a context value without
   needing to use `Consumer`.

```jsx
const value = useContext(MyContext);
```

#### When to use:

- When there is a need to pass data between components at different levels of
  the hierarchy (for example, theme, language, or user).

- When you do not want to pass props through several component levels, which can
  complicate the code.

#### Example:

```jsx
// Creating context
const ThemeContext = React.createContext('light');

// Component that provides the context value
function App() {
  return (
    <ThemeContext.Provider value="dark">
      <ThemedComponent />
    </ThemeContext.Provider>
  );
}

// Component that consumes the context value
function ThemedComponent() {
  const theme = useContext(ThemeContext);
  return <div>The current theme is {theme}</div>;
}
```

#### Advantages:

- Convenience in passing global values.

- Improves application scalability by reducing the number of passed props.

</details>

<details>
<summary>47. How does React Context work for sharing data between components?</summary>

#### React

The **React Context** mechanism allows data to be passed between components
without needing to pass it through props at every level. This is useful for
global data such as theme settings, user authentication, or language.

#### Main steps for working with Context:

1. **Creating context:** `React.createContext()` is used to create a context. It
   returns two components:

- `Provider`, the component that passes the context value.

- `Consumer`, the component that receives the context value.

```jsx
const MyContext = React.createContext();
```

2. **Providing context:** Use `Provider` to wrap the components that need the
   context. The value is passed through the `value` prop.

```jsx
const App = () => {
  const [user, setUser] = useState('John Doe');

  return (
    <MyContext.Provider value={user}>
      <Child />
    </MyContext.Provider>
  );
};
```

3. **Consuming context:** Use `Consumer` or the `useContext` hook to access the
   context value.

- **Consumer:**

```jsx
const Child = () => (
  <MyContext.Consumer>{user => <div>{user}</div>}</MyContext.Consumer>
);
```

- **`useContext` hook (recommended in functional components):**

```jsx
const Child = () => {
  const user = useContext(MyContext);
  return <div>{user}</div>;
};
```

- **Changing context:** To change the context value, you can use functions
  passed through `useState` or other state management methods.

```jsx
const App = () => {
  const [user, setUser] = useState('John Doe');

  return (
    <MyContext.Provider value={user}>
      <button onClick={() => setUser('Jane Doe')}>Change User</button>
      <Child />
    </MyContext.Provider>
  );
};
```

#### Key points:

- Context helps avoid `prop drilling` (passing props through many components).

- If the context value changes, all components that consume this context will
  rerender.

- **`useContext`** is a more convenient and modern way to get a context value
  compared with `Consumer`.

Context is a powerful tool, but it should be used only for global data. For
local state, regular state is usually a better choice.

</details>

<details>
<summary>48. What is Prop Drilling, and how can it be avoided?</summary>

#### React

**Prop Drilling** is the process of passing props through several levels of
nested components, even if they are needed only in a deeply nested child
component. This makes the code harder to maintain and less readable.

#### Example of Prop Drilling:

```jsx
const Parent = () => {
  const user = { name: 'John' };
  return <Child user={user} />;
};

const Child = ({ user }) => {
  return <GrandChild user={user} />;
};

const GrandChild = ({ user }) => {
  return <p>Name: {user.name}</p>;
};
```

Here, `user` is passed through `Child` even though it does not need it. This is
**prop drilling**.

#### How to avoid Prop Drilling?

| **Method**                                               | **Description**                                                   |
| -------------------------------------------------------- | ----------------------------------------------------------------- |
| **Context API**                                          | Allows data to be passed directly to the components that need it. |
| **External state tools (Redux, Zustand, Jotai, Recoil)** | Used to manage global state without passing props.                |
| **Render Props components**                              | Allow functions to be passed instead of props.                    |
| **Custom Hooks**                                         | Move logic into separate functions for access to shared data.     |

#### Example of using Context API instead of Prop Drilling

```jsx
import { createContext, useContext } from 'react';

const UserContext = createContext();

const Parent = () => {
  const user = { name: 'John' };
  return (
    <UserContext.Provider value={user}>
      <GrandChild />
    </UserContext.Provider>
  );
};

const GrandChild = () => {
  const user = useContext(UserContext);
  return <p>Name: {user.name}</p>;
};
```

Here, `user` is available directly in `GrandChild` without unnecessary passing
through `Child`.

</details>

<details>
<summary>49. What is Redux?</summary>

#### React

**Redux** is a library for state management in JavaScript applications,
especially popular with React. It is based on the concept of a global store,
where the entire application state is kept, and it allows that state to be
managed through predictable changes.

#### Main principles of Redux:

1. **Single source of truth:** All state is stored in one global `store`, which
   simplifies tracking changes.
2. **State is read-only:** State cannot be changed directly, only through an
   `action`.
3. **Changes happen through pure functions:** State is changed using reducer
   functions, which take the current state and an `action`, and return a new
   state.

#### Main elements of Redux:

- **Store:** the single state container.
- **Actions:** objects that describe the intent to change state.
- **Reducers:** pure functions that define how state changes.
- **Dispatch:** the method used to send an `action`.
- **Selectors:** functions for getting needed data from the `store`.

Redux is suitable for large applications with complicated data flows, but for
simple projects it is often unnecessary.

</details>

<details>
<summary>50. What other state management libraries for React do you know besides Redux?</summary>

#### React

Besides Redux, there are many libraries for state management in React:

1. **React Context API:** a built-in React mechanism for passing state without
   prop drilling. It works well for small and medium-sized applications.

2. **Zustand:** simpler and lighter than Redux, with no need for reducers or
   actions. It uses an imperative approach and works through hooks.

3. **Recoil:** a library from Facebook that works with atoms and selectors,
   allowing a flexible global state system to be built.

4. **Jotai:** similar to Recoil but simpler. It uses atoms to store state and
   allows declarative state management.

5. **MobX:** a reactive approach to state management that works through
   observables. Convenient for working with objects and complex structures.

6. **Effector:** more declarative and efficient than Redux. It is built on a
   reactive approach and makes data flow management easier.

7. **XState:** a library for working with state machines, well suited for
   complex business logic.

Each of them has its own advantages, and the choice depends on project
complexity and performance requirements.

</details>

<details>
<summary>51. What is Redux Thunk?</summary>

#### React

**Redux Thunk** is middleware for Redux that allows you to perform asynchronous
operations (for example, API requests) before dispatching changes to the
`store`.

#### How it works:

Normally, Redux allows only objects (`actions`) to be passed to `dispatch`.
Redux Thunk extends this capability by allowing functions to be passed. This
makes it possible to:

1. Perform asynchronous actions before changing state.

2. Access `dispatch` and `getState` inside the `thunk`.

#### Example:

```jsx
const fetchData = () => {
  return async dispatch => {
    dispatch({ type: 'FETCH_START' });

    try {
      const response = await fetch('https://api.example.com/data');
      const data = await response.json();
      dispatch({ type: 'FETCH_SUCCESS', payload: data });
    } catch (error) {
      dispatch({ type: 'FETCH_ERROR', error });
    }
  };
};
```

Then we call this `thunk`:

```jsx
dispatch(fetchData());
```

#### When to use:

- For API requests.
- For delays or complex logic before updating the store.
- When you need to perform several dispatches within a single action.

If the application has complex asynchronous logic, it is better to consider
**Redux Saga** or **RTK Query** as alternatives.

</details>

<details>
<summary>52. How does Redux Saga work?</summary>

#### React

**Redux Saga** is middleware for Redux that uses generators (`function*`) to
manage asynchronous requests in an application.

#### How it works:

1. **Listens to actions** (`takeEvery`, `takeLatest`) and reacts to them.

2. **Performs side effects** (API requests, timers, and so on).

3. **Dispatches new actions** (`put`) to the store.

#### Example:

1. **Saga for fetching data from an API:**

```jsx
import { call, put, takeEvery } from 'redux-saga/effects';

function* fetchData() {
  try {
    const response = yield call(fetch, 'https://api.example.com/data');
    const data = yield response.json();
    yield put({ type: 'FETCH_SUCCESS', payload: data });
  } catch (error) {
    yield put({ type: 'FETCH_ERROR', error });
  }
}
```

2. **Action watcher:**

```jsx
function* watchFetchData() {
  yield takeEvery('FETCH_REQUEST', fetchData);
}
```

3. **Running the saga in the `store`:**

```jsx
import createSagaMiddleware from 'redux-saga';
const sagaMiddleware = createSagaMiddleware();
const store = createStore(reducer, applyMiddleware(sagaMiddleware));
sagaMiddleware.run(watchFetchData);
```

#### Advantages of Redux Saga:

- Handles complex asynchronous logic.
- Built-in cancellation handling (`takeLatest`).
- Powerful operators (`call`, `put`, `select`, `delay`).

**Redux Thunk** is simpler, but for complex scenarios **Saga** is often a better
fit.

</details>

<details>
<summary>53. What is React Fiber?</summary>

#### React

**React Fiber** is the new rendering architecture in React, introduced in
version 16. It was designed to improve performance, support asynchronous
rendering, and provide more flexible management of UI updates.

#### Key features of React Fiber:

1. **Improved performance:** Fiber allows React to keep the state of rendering
   work, which makes it possible to pause and resume rendering when needed. This
   is important for large applications where complex calculations can slow down
   rendering.

2. **Asynchronous rendering:** React Fiber supports asynchronous rendering,
   which allows rendering to happen in parts and improves application
   responsiveness, especially in complex interfaces. This makes it possible to
   render without blocking the main thread.

3. **Update prioritization:** Fiber allows different update types to have
   different priorities (for example, animation rendering can be high priority,
   while state update rendering can be low priority). This lets React manage
   complex updates more efficiently.

4. **Splitting rendering into subtasks:** In older versions of React, all
   changes were processed in one step. Fiber breaks rendering into smaller
   subtasks, which allows React to do work gradually and handle other important
   operations (such as event handling) between steps.

5. **Improved support for animations and transitions:** Thanks to asynchronous
   rendering, React can manage animations more effectively, making transitions
   between states smoother and more responsive.

#### How does React Fiber work?

In older versions of React, the entire rendering process was synchronous from
start to finish. That meant heavy calculations blocked UI rendering. In React
Fiber, rendering is split into small tasks that can be executed asynchronously.
If needed, React can pause one task and continue it later without blocking other
operations (for example, UI updates or event handling).

#### Fiber allows React to:

- Split rendering work to improve performance.

- Enable asynchronous UI updates.

- Better manage priorities and heavy computations, which is especially important
  for complex interfaces and applications.

#### Advantages:

- Improved application responsiveness.

- The ability to handle heavy operations without causing visible delays for the
  user.

- Better animation and transition management.

**React Fiber** is an internal upgrade that changed how React handles rendering,
improving the overall performance of applications.

</details>

<details>
<summary>54. What is Lifting State Up in React?</summary>

#### React

**Lifting State Up** is a React approach where state is moved to the nearest
common ancestor of the components that need to share it. This makes it possible
to organize a single source of truth for managing data between components.

#### Main idea:

1. **Components that need to share data should not each have their own separate
   state.**

2. **State is moved to a parent component, which passes the data to child
   components through props.**

#### How it works:

1. **The parent component stores the state.**
2. **It passes the state and state update functions to its child components
   through `props`.**

3. **Child components notify the parent about changes using the passed
   functions.**

#### Example:

```jsx
import React, { useState } from 'react';

function TemperatureInput({ temperature, onTemperatureChange }) {
  return (
    <fieldset>
      <legend>Enter temperature in Celsius:</legend>
      <input
        type="number"
        value={temperature}
        onChange={e => onTemperatureChange(e.target.value)}
      />
    </fieldset>
  );
}

function BoilingVerdict({ celsius }) {
  return celsius >= 100 ? (
    <p>The water will boil.</p>
  ) : (
    <p>The water won't boil.</p>
  );
}

function Calculator() {
  const [temperature, setTemperature] = useState('');

  return (
    <div>
      <TemperatureInput
        temperature={temperature}
        onTemperatureChange={setTemperature}
      />
      <BoilingVerdict celsius={parseFloat(temperature)} />
    </div>
  );
}

export default Calculator;
```

#### Advantages:

1. **Provides a single source of truth for state.**

2. **Makes synchronization of data between components easier.**

3. **Makes components more predictable and reusable.**

</details>

<details>
<summary>55. What are Controlled Components?</summary>

#### React

#### Controlled Components in React

Controlled components are components in which **React controls the form state**
through `state`. The values of form fields (for example, `<input>`,
`<textarea>`, and `<select>`) are bound to component state, and changes are
handled through events.

#### How it works:

1. **The component stores the form value in its `state`.**

2. **Changes to form field values are handled through the `onChange` event.**

3. **The form value is updated using `setState`.**

#### Example:

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [inputValue, setInputValue] = useState('');

  const handleChange = event => {
    setInputValue(event.target.value); // Update state
  };

  const handleSubmit = event => {
    event.preventDefault();
    console.log('Submitted value:', inputValue);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Enter text:
        <input
          type="text"
          value={inputValue} // The value is controlled by state
          onChange={handleChange} // Handle changes
        />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}

export default ControlledForm;
```

#### Main advantages:

1. **Single source of truth:** The form value is synchronized with the component
   state.

2. **Flexibility:** It is easy to validate and modify form data.

3. **Transparency:** The form state is clear and predictable.

#### Differences from uncontrolled components:

- In controlled components, the form value is controlled by React through
  `state`.

- In uncontrolled components, the value is stored in the DOM itself, and it is
  accessed through `ref`.

#### Uncontrolled example for comparison:

```jsx
function UncontrolledForm() {
  const inputRef = React.useRef();

  const handleSubmit = event => {
    event.preventDefault();
    console.log('Submitted value:', inputRef.current.value);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Enter text:
        <input type="text" ref={inputRef} />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}
```

Controlled components provide better control and predictability when working
with forms.

</details>

<details>
<summary>56. What are Uncontrolled Components?</summary>

#### React

#### Uncontrolled Components in React

Uncontrolled components are components that store their state in the DOM rather
than in the internal state of a React component. The values of such components
are accessed using **refs**.

#### Main characteristics:

1. **State is managed by the DOM:** field values are stored and updated directly
   in the DOM.

2. **Less integration with React:** they do not use `useState` or other React
   mechanisms to store state.

3. **Use of refs:** a `ref` is used to access form field values.

#### Example of an uncontrolled component:

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const inputRef = useRef(null);

  const handleSubmit = event => {
    event.preventDefault();
    alert(`Entered value: ${inputRef.current.value}`);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Name:
        <input type="text" ref={inputRef} />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}

export default UncontrolledForm;
```

#### When to use uncontrolled components:

- If minimal React integration with the DOM is needed.

- If form values are handled by third-party libraries.

- If a simple form without complex logic is needed.

#### Advantages:

- Simplicity of implementation for simple forms.

- Less code for state management.

#### Disadvantages:

- Less control over values.

- Harder to implement validation or data synchronization.

- A less React-oriented approach.

</details>

<details>
<summary>57. How do you create a form in React?</summary>

#### React

#### Creating a form in React

Forms in React are created using `<form>` elements and corresponding controls
such as `<input>`, `<textarea>`, and `<select>`. Form reactivity is provided by
controlled or uncontrolled components.

#### Controlled form (Controlled Component)

Controlled components use state to track the values of form fields.

#### Example:

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [name, setName] = useState('');
  const [email, setEmail] = useState('');

  const handleSubmit = e => {
    e.preventDefault();
    console.log('Submitted:', { name, email });
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Name:
        <input
          type="text"
          value={name}
          onChange={e => setName(e.target.value)}
        />
      </label>
      <br />
      <label>
        Email:
        <input
          type="email"
          value={email}
          onChange={e => setEmail(e.target.value)}
        />
      </label>
      <br />
      <button type="submit">Submit</button>
    </form>
  );
}

export default ControlledForm;
```

#### Features:

- Each field is controlled through `state`.

- It is easy to synchronize and process form data.

#### Uncontrolled form (Uncontrolled Component)

Uncontrolled components use a ref (`ref`) for direct access to DOM elements.

#### Example:

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const nameRef = useRef();
  const emailRef = useRef();

  const handleSubmit = e => {
    e.preventDefault();
    console.log('Submitted:', {
      name: nameRef.current.value,
      email: emailRef.current.value,
    });
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Name:
        <input type="text" ref={nameRef} />
      </label>
      <br />
      <label>
        Email:
        <input type="email" ref={emailRef} />
      </label>
      <br />
      <button type="submit">Submit</button>
    </form>
  );
}

export default UncontrolledForm;
```

#### Features:

- Values are accessed through a ref.

- Suitable for simple forms.

#### Main points:

1. **Controlled form:**

- Uses `state`.

- Better suited for complex forms that require validation or synchronization.

2. **Uncontrolled form:**

- Uses `ref`.

- A simple approach without complex state management logic.

The choice of approach depends on the complexity of the form and the needs of
interaction with its fields.

</details>

<details>
<summary>58. How do you apply props validation in React?</summary>

#### React

**PropTypes** are used for props validation in React.

1. **Installing PropTypes (if not installed)**

```sh
npm install prop-types
```

2. **Using PropTypes in a functional component:**

```jsx
import React from 'react';
import PropTypes from 'prop-types';

function UserCard({ name, age, isAdmin }) {
  return (
    <div>
      <h2>{name}</h2>
      <p>Age: {age}</p>
      {isAdmin && <p>Admin Access</p>}
    </div>
  );
}

// Defining PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Default values
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

3. **Using it in a class component:**

```jsx
import React from 'react';
import PropTypes from 'prop-types';

class UserCard extends React.Component {
  render() {
    const { name, age, isAdmin } = this.props;
    return (
      <div>
        <h2>{name}</h2>
        <p>Age: {age}</p>
        {isAdmin && <p>Admin Access</p>}
      </div>
    );
  }
}

// Defining PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Default values
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

#### Available PropTypes:

- `PropTypes.string`
- `PropTypes.number`
- `PropTypes.bool`
- `PropTypes.array`
- `PropTypes.object`
- `PropTypes.func`
- `PropTypes.node` (JSX or text)
- `PropTypes.element` (React element)
- `PropTypes.oneOf(['value1', 'value2'])` (a list of allowed values)
- `PropTypes.shape({ key: PropTypes.type })` (an object with a defined
  structure)

#### Summary:

PropTypes help avoid errors by checking prop types, but in TypeScript this is
done at the language level itself.

</details>

<details>
<summary>59. How is React Router different from regular routing?</summary>

#### React

#### Difference between React Router and regular routing:

| Criterion            | React Router                                     | Regular routing (Server-Side Routing)            |
| -------------------- | ------------------------------------------------ | ------------------------------------------------ |
| **Routing type**     | Client-side (SPA)                                | Server-side (MPA)                                |
| **Page transitions** | Without page reload (JS updates the URL)         | Page reload on each navigation                   |
| **Speed**            | Faster because it does not re-request the server | Slower due to new HTTP requests                  |
| **SEO**              | Worse without SSR (but Next.js solves this)      | Better because content is loaded from the server |
| **Data handling**    | Dynamic component rendering                      | HTML loading from the server                     |
| **Setup**            | Requires React Router                            | Uses standard server capabilities                |

</details>

<details>
<summary>60. How do you pass props in React Router?</summary>

#### React

To pass props to components when using **React Router**, there are several
approaches:

1. **Using the `Route` component to pass props:** You can pass props through the
   `Route` component using `render` or `children`.

**Example:**

```jsx
import { Route } from 'react-router-dom';

<Route path="/profile" render={props => <Profile {...props} user="John" />} />;
```

Here we pass additional props to the `Profile` component.

2. **Using `useNavigate()` to pass data through navigation (via `state`):** When
   navigating to a new page, you can pass props through `state`.

**Example:**

```jsx
import { useNavigate } from 'react-router-dom';

function Home() {
  const navigate = useNavigate();

  function goToProfile() {
    navigate('/profile', { state: { user: 'John' } });
  }

  return <button onClick={goToProfile}>Go to Profile</button>;
}
```

**Receiving props in a component:**

```jsx
import { useLocation } from 'react-router-dom';

function Profile() {
  const location = useLocation();
  const user = location.state?.user;

  return <div>Welcome, {user}</div>;
}
```

3. **Using `useParams()` to access route parameters:** If you need to pass
   parameters through the URL, you can use `useParams()`.

**Example:**

```jsx
import { useParams } from 'react-router-dom';

function Profile() {
  const { id } = useParams();

  return <div>User ID: {id}</div>;
}
```

#### Summary:

- `render` or `children` are suitable for passing props directly.

- `useNavigate()` and `state` allow data to be passed between pages.

- `useParams()` is convenient for dynamic parameters in the URL.

</details>

<details>
<summary>61. What are the ways to style React components?</summary>

#### React

#### Ways to use styles in React components:

1. **Inline styles:** Styles are passed directly as an object through the
   `style` attribute.

```jsx
function InlineStyle() {
  const style = {
    color: 'blue',
    fontSize: '20px',
  };

  return <h1 style={style}>Hello, React!</h1>;
}
```

2. **CSS files:** Using regular CSS files that are imported into the component.

```jsx
import './styles.css';

function CSSFile() {
  return <h1 className="heading">Hello, React!</h1>;
}
```

```css
/* styles.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

3. **CSS Modules:** Create locally isolated styles for each component.

```jsx
import styles from './styles.module.css';

function CSSModule() {
  return <h1 className={styles.heading}>Hello, React!</h1>;
}
```

```css
/* styles.module.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

4. **Styled Components:** Using the `styled-components` library to write styles
   in JavaScript.

```bash
npm install styled-components
```

```jsx
import styled from 'styled-components';

const Heading = styled.h1`
  color: blue;
  font-size: 20px;
`;

function StyledComponent() {
  return <Heading>Hello, React!</Heading>;
}
```

5. **Emotion:** An alternative styling library similar to `styled-components`.

```bash
npm install @emotion/react @emotion/styled
```

```jsx
/**_ @jsxImportSource @emotion/react */
import { css } from '@emotion/react';

const style = css`
  color: blue;
  font-size: 20px;
`;

function EmotionStyle() {
  return <h1 css={style}>Hello, React!</h1>;
}
```

6. **CSS-in-JS:** Creating dynamic styles in regular JavaScript files.

```jsx
function CSSInJS({ isBlue }) {
  const style = {
    color: isBlue ? 'blue' : 'red',
    fontSize: '20px',
  };

  return <h1 style={style}>Hello, React!</h1>;
}
```

7. **Tailwind CSS:** A utility-class framework for styling components.

```jsx
function TailwindExample() {
  return <h1 className="text-blue-500 text-2xl">Hello, React!</h1>;
}
```

**Tailwind CSS setup:** add the dependencies and configure it.

8. **Sass/SCSS:** Extended CSS with support for variables, mixins, and nesting.

```bash
npm install sass
```

```jsx
import './styles.scss';

function SCSSExample() {
  return <h1 className="heading">Hello, React!</h1>;
}
```

```scss
/* styles.scss */
.heading {
  color: blue;
  font-size: 20px;
}
```

#### The choice depends on:

- Project scale.

- The need for style isolation.

- Team preferences.

</details>

<details>
<summary>62. What is the advantage of CSS Modules?</summary>

#### React

**Advantages of CSS Modules:**

1. **Local scope:** Styles are applied only to the component, not globally. This
   prevents class conflicts and ensures that styles do not affect other parts of
   the application.

2. **Unique class names:** CSS Modules automatically generate unique class
   names, which eliminates the risk of style collisions with other components.

3. **Easier maintenance:** There are fewer problems when scaling the project,
   because each component has its own styles, making the code more organized and
   easier to understand.

4. **Isolation:** Each component has full style isolation, which simplifies
   refactoring and changing styles without affecting other components.

5. **Easier integration with JavaScript:** You can use dynamic styles through
   JavaScript by changing classes depending on component state.

This helps maintain order in large applications and reduces the likelihood of
style-related errors.

</details>

<details>
<summary>63. What approaches do you know for optimizing the performance of React applications?</summary>

#### React

#### Approaches to optimizing React application performance:

1. **Component memoization:**

- Use `React.memo` to memoize functional components that do not depend on
  frequent prop updates.
- Use `PureComponent` for class components.

2. **Memoization of values and functions:**

- `useMemo` for computing values that depend on specific dependencies.
- `useCallback` for memoizing functions passed to child components.

3. **Optimizing list rendering:**

Always use a unique key for items in lists. Avoid rerendering components
unnecessarily.

4. **Dynamic component loading:**

- Use `React.lazy` to load components on demand.
- Combined with `Suspense`, this helps optimize application loading.

5. **Rerender control:**

- Use `shouldComponentUpdate` or `React.memo` to reduce unnecessary renders.
- Use `React.Fragment` instead of extra wrapper elements.

6. **Code splitting:**

- Implement `React.lazy` and dynamic imports so module code is loaded only when
  needed.

7. **State management:**

- Avoid storing global state for components where it is not needed.
- Move heavy state operations into context or specialized libraries (Redux,
  Zustand).

8. **List virtualization:**

- Use libraries such as `react-window` or `react-virtualized` to render only
  visible list items.

9. **Image optimization:**

- Use lazy loading for images.
- Compress and optimize images before using them.

10. **Reducing the number of components in the DOM:**

- Avoid excessive component nesting.
- Remove unnecessary DOM elements during page transitions.

11. **Data caching:**

- Use caching libraries such as `SWR` or `React Query` to manage data and reduce
  server requests.

12. **Using a production build:**

- Make sure the application is built in production mode (`npm run build`).
- Use tools such as `Webpack` to minify and optimize code.

13. **Application profiling:**

- Use `React DevTools` to analyze performance.
- Identify bottlenecks using the `Profiler` tab.

14. **CSS and style optimization:**

- Use CSS-in-JS solutions (for example, `styled-components`) only where
  necessary.
- Minify styles using `PostCSS` or other tools.

These approaches help reduce delays, improve rendering speed, and raise the
overall performance of the application.

</details>

<details>
<summary>64. What is the difference between `memo` and `useMemo`?</summary>

#### React

#### Difference between `memo` and `useMemo`

| Criterion               | memo                                                         | useMemo                                                |
| ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------ |
| **What is it?**         | A higher-order function (HOC)                                | A hook                                                 |
| **Purpose**             | Prevents rerendering a component if props have not changed   | Caches a computation result between renders            |
| **Where is it used?**   | Wraps a component                                            | Inside a component                                     |
| **Usage example**       | `export default memo(MyComponent);`                          | `const value = useMemo(() => compute(), [deps]);`      |
| **What does it cache?** | The whole component                                          | The function result                                    |
| **When to use it?**     | If a component rerenders with the same props without changes | If a computation is expensive and depends on variables |

#### When to use?

- `memo` when a component receives the same props and does not need to rerender.

- `useMemo` when you need to store a computation result so it is not
  recalculated every time.

</details>

<details>
<summary>65. Why do you need to pass a function to `setState()`?</summary>

#### React

Passing a function to `setState()` is necessary when the new state depends on
the previous state. This guarantees a correct update because `setState()` works
asynchronously and may batch calls.

#### Example with a problem:

```jsx
function Counter() {
  const [count, setCount] = useState(0);

  function increment() {
    setCount(count + 1);
    setCount(count + 1);
  }

  return <button onClick={increment}>{count}</button>;
}
```

Here, `count + 1` is calculated twice from the same old `count`, so the button
will increase the value by only 1 instead of 2.

#### Correct approach:

```jsx
function Counter() {
  const [count, setCount] = useState(0);

  function increment() {
    setCount(prevCount => prevCount + 1);
    setCount(prevCount => prevCount + 1);
  }

  return <button onClick={increment}>{count}</button>;
}
```

Here, `setCount()` receives the current `prevCount` value, so the increment
works correctly and increases the value by 2.

</details>

<details>
<summary>66. How are refs used in React to interact with DOM elements?</summary>

#### React

Refs in React are used to gain direct access to DOM elements or components,
bypassing the standard props and state mechanism.

1. **Creating refs:** Use `React.createRef()` to create a ref.

```jsx
const myRef = React.createRef();
```

2. **Attaching a ref to an element:** The ref is passed to a DOM element through
   the `ref` attribute.

```jsx
<input ref={myRef} />
```

3. **Interacting with the DOM:** The ref provides access to the DOM element
   through `.current`. For example, to set focus:

```jsx
myRef.current.focus();
```

4. **Limitation:** Refs should not be used for state management. They are
   intended only for DOM interaction when necessary (for example, for focus,
   text selection, or animations).

5. **Functional components:** In React 16.8 and later, `useRef` is used for
   functional components.

```jsx
const inputRef = useRef();
inputRef.current.focus();
```

</details>

<details>
<summary>67. How do you use InnerHTML in React?</summary>

#### React

- In React, the `dangerouslySetInnerHTML` attribute is used to insert HTML
  content into the DOM. This makes it possible to insert HTML directly into a
  component, but this approach can be dangerous, which is why it is called
  "dangerously". It allows raw HTML to be embedded, which can lead to XSS
  attacks if the data is not sanitized.

#### Example of using `dangerouslySetInnerHTML`:

```jsx
const MyComponent = () => {
  const htmlContent = '<p>This is <strong>HTML</strong> content.</p>';

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
};
```

#### Explanation:

- `dangerouslySetInnerHTML` takes an object in which the `__html` key contains
  an HTML string.

- This allows HTML to be embedded inside a component, but it is unsafe if the
  content comes from untrusted sources.

#### When to use:

- If you are sure the data is safe (for example, from your own servers).

- When you need to embed dynamic HTML content, such as pages or articles with
  HTML markup.

#### Warning:

- Security: Never use `dangerouslySetInnerHTML` to insert data received from a
  user or external sources without first sanitizing it from malicious scripts.

- To sanitize content, use libraries such as DOMPurify to avoid XSS attacks.

**Example of sanitizing data before insertion:**

```jsx
import DOMPurify from 'dompurify';

const MyComponent = () => {
  const dirtyHtml = "<img src=x onerror=alert('XSS')>";
  const cleanHtml = DOMPurify.sanitize(dirtyHtml);

  return <div dangerouslySetInnerHTML={{ __html: cleanHtml }} />;
};
```

Therefore, `dangerouslySetInnerHTML` should be used carefully and only when you
are confident in the safety of the content.

</details>

<details>
<summary>68. What is ReactDOMServer?</summary>

#### React

**`ReactDOMServer`** is a library included with React that is used to render
React components on the server, that is, for server-side rendering (SSR). It
allows HTML to be generated on the server and sent to the client, which can
improve performance and SEO.

#### Main methods:

1. **`ReactDOMServer.renderToString()`:** Renders React elements into an HTML
   string. This is the main method for generating static HTML for the initial
   page load.

```jsx
import ReactDOMServer from 'react-dom/server';
const html = ReactDOMServer.renderToString(<App />);
```

2. **`ReactDOMServer.renderToStaticMarkup()`:** Renders HTML without any extra
   React-related attributes, such as `data-reactroot`. This is suitable for
   creating fully static pages.

```jsx
const html = ReactDOMServer.renderToStaticMarkup(<App />);
```

3. **`ReactDOMServer.hydrate()`:** Used on the client side to "hydrate"
   server-rendered HTML, that is, to attach React interactivity to existing
   HTML.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

#### Usage:

- **SSR (Server-Side Rendering):** This is an approach in which React components
  are rendered on the server rather than in the browser, allowing a fully
  generated HTML page to be sent to the client.

- **SEO:** Since the server immediately sends HTML content, search engines can
  index pages without needing to execute JavaScript.

Thus, `ReactDOMServer` allows you to create pre-rendered pages, which improves
loading speed and can be useful for SEO.

</details>

<details>
<summary>69. What is the `react-dom` package used for?</summary>

#### React

The `react-dom` package is used for interaction between React and the real DOM
in web applications. Main functions:

1. **`ReactDOM.render()`:** Used to render a component into the real DOM. This
   is the main method that connects React with HTML elements.

```jsx
ReactDOM.render(<App />, document.getElementById('root'));
```

2. **`ReactDOM.hydrate()`:** Used to hydrate server-rendered HTML (for example,
   for SSR). This allows React to take control of already existing HTML.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

3. **`ReactDOM.createPortal()`:** Allows child elements to be rendered in
   another place in the DOM, outside the normal component hierarchy. This is
   often used for modals, tooltips, and floating elements.

```jsx
ReactDOM.createPortal(<Modal />, document.getElementById('modal-root'));
```

4. **`ReactDOM.unmountComponentAtNode()`:** Removes a React component from the
   DOM.

```jsx
ReactDOM.unmountComponentAtNode(document.getElementById('root'));
```

5. **`ReactDOM.findDOMNode()`:** Gives access to the real DOM element of a
   component (rarely used because there are more modern approaches through
   refs).

- This package is necessary for working with the real DOM, but in most cases,
  after the initial setup, you do not need to call these methods manually,
  because they are used automatically by build and rendering tools.

</details>

<details>
<summary>70. How do you use `React.lazy` and `React.Suspense` for code splitting?</summary>

#### React

`React.lazy` and `React.Suspense` are used for **dynamic component loading** in
React, which enables **code splitting**. This means that parts of the code are
loaded only when needed, thereby improving the performance of your application.

#### How it works:

1. **`React.lazy()`** allows a component to be loaded lazily.

2. **`React.Suspense`** is used to wrap a part of the code that has not yet
   loaded and allows fallback content (for example, a loader) to be shown while
   the components load.

#### Example:

1. **Dynamic component loading:** First, create a component that will be loaded
   dynamically.

```jsx
// Dynamically loaded component
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Wrapper with `React.Suspense`:** Now use `React.Suspense` to show a loader
   while the component is loading.

```jsx
function App() {
  return (
    <div>
      <h1>My application</h1>

      {/* Wrapper for dynamically loaded components */}
      <React.Suspense fallback={<div>Loading...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Description:**

- `React.lazy()` takes a function that dynamically imports a module.

- `React.Suspense` wraps the component that uses `React.lazy()` and shows
  fallback content (in this case, the text "Loading...") until the component
  finishes loading.

#### Advantages:

- Improves performance by loading components only when needed.

- Reduces the initial bundle size because parts of the application are loaded on
  demand.

This approach is especially useful in large applications, where code can be
split into parts to reduce page load time.

</details>

<details>
<summary>71. What are the best security practices in React?</summary>

#### React

#### Best security practices in React:

1. **Preventing XSS (Cross-Site Scripting):**

- Always sanitize data coming from users before displaying it in a component.
- Use JSX (React escapes input automatically, but you should avoid using
  `dangerouslySetInnerHTML` where possible).
- If you need to use `dangerouslySetInnerHTML`, make sure the content is
  safely sanitized.

2. **Avoid code injection:**

- Never pass unvalidated data into `eval()`, `setTimeout()`, `setInterval()`,
  or other functions that execute code.
- For dynamic imports, use built-in controlled functionality (for example,
  `React.lazy()`).

3. **Secure API access:**

- Use HTTPS to protect data transmitted over the network.
- Use authentication and authorization, as well as secure cookies (`HttpOnly`,
  `Secure`).

4. **Protection against CSRF (Cross-Site Request Forgery):**

- Use CSRF tokens to validate all requests that change data on the server.
- Use the `SameSite` flag for cookies to restrict access to the same domain.

5. **Access control:**

- Check whether the user has permission to perform the requested action before
  sending a request to the server.
- Do not trust client-side checks. All server-side checks must be final.

6. **Protection for editable input fields:**

- For forms and fields that accept user input, set restrictions on allowed
  values.

7. **Updating dependencies:**

- Regularly check and update dependencies to detect potential
  vulnerabilities. Use `npm audit` or other tools for this.

8. **Secret management:**

- Do not store secrets (API keys, passwords, and so on) in client-side code.
  They should be kept on the server or in environments such as environment
  variables.

9. **Using Content Security Policy (CSP):**

- Use CSP to prevent unwanted scripts from executing on your site.

10. **Protection against Clickjacking:**

- Use `X-Frame-Options` or `Content-Security-Policy` headers to prevent your
  site from being embedded in an `<iframe>` on other websites.

Following these practices will help reduce security risks in React
applications.

</details>

<details>
<summary>72. How do you handle errors in React using Error Boundary?</summary>

#### React

**Error Boundaries** in React allow you to catch errors in components during
rendering, in lifecycle methods, and in constructors, and handle them without
crashing the entire application.

#### Key points:

- An Error Boundary is a component that wraps other components and can catch
  errors that occur in their code.

- **Error Boundaries** catch only errors that happen in their descendants.
  They do not catch errors in the Error Boundary itself.

#### How to implement an Error Boundary:

1. **Creating an Error Boundary:** To create an Error Boundary, you need to
   implement two methods:

- `static getDerivedStateFromError(error)` updates state when an error occurs.

- `componentDidCatch(error, info)` lets you log errors (for example, send them
  to the server).

```jsx
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false, error: null };
  }

  static getDerivedStateFromError(error) {
    // Update state to show fallback UI
    return { hasError: true, error };
  }

  componentDidCatch(error, info) {
    // Error logging logic (for example, to a server)
    console.error('Error caught:', error, info);
  }

  render() {
    if (this.state.hasError) {
      // Show fallback UI when an error occurs
      return <h1>Something went wrong.</h1>;
    }

    return this.props.children;
  }
}
```

2. **Using Error Boundary:** Wrap components that may throw errors in
   `ErrorBoundary`.

```jsx
const App = () => {
  return (
    <ErrorBoundary>
      <MyComponent />
    </ErrorBoundary>
  );
};
```

3. **Fallback interface:** When an error occurs, Error Boundary can show
   fallback UI (for example, an error message, a retry button, or even actions
   for application recovery).

#### Important points:

- Error Boundary does not catch errors in event handlers (for example,
  `onClick`), asynchronous code, timers, or network requests. For those cases,
  use `try...catch` or other mechanisms.

- If the error occurs in the Error Boundary itself, it will not be caught.

**Error Boundaries** are useful for application stability because they allow
errors to be intercepted and handled without stopping the whole app.

</details>

<details>
<summary>73. What is Inheritance Inversion?</summary>

#### React

- **Inheritance Inversion** is a situation in which a class that should be the
  base class actually depends on its descendants or loses control over the
  logic that should belong in the inheritance hierarchy.

#### Problems with inheritance inversion

- Violation of the Liskov Substitution Principle (LSP).

- It becomes difficult to change or extend the base class without affecting
  all its descendants.

- Complexity increases because of interdependencies.

#### Example of poor practice

```js
class Parent {
  method() {
    throw new Error('The method must be implemented in the child');
  }
}

class Child extends Parent {
  method() {
    return 'Implementation in the child';
  }
}
```

Here the base class has no logic of its own and forces children to implement
behavior, which is a sign of inheritance inversion.

#### Alternative: Composition instead of inheritance

```js
class Behavior {
  method() {
    return 'Implementation without inversion';
  }
}

class Parent {
  constructor() {
    this.behavior = new Behavior();
  }

  method() {
    return this.behavior.method();
  }
}
```

This approach removes the parent class's dependency on descendants, making the
code more flexible.

</details>

<details>
<summary>74. What is Polling, and how do you implement it in React?</summary>

#### React

**Polling** is the periodic sending of requests to a server to get updated
data. It is useful when the server does not support WebSockets or
Server-Sent Events, and the client needs to receive new information without
reloading the page.

#### Implementing Polling in React

Polling can be implemented with `setInterval`, `setTimeout`, or by using React
hooks (`useEffect`).

1. **Using `setInterval`**

```jsx
import { useState, useEffect } from 'react';

const PollingComponent = () => {
  const [data, setData] = useState(null);

  useEffect(() => {
    const fetchData = async () => {
      const response = await fetch('https://api.example.com/data');
      const result = await response.json();
      setData(result);
    };

    fetchData(); // Run immediately on load

    const interval = setInterval(fetchData, 5000); // Poll every 5 sec.

    return () => clearInterval(interval); // Cleanup on unmount
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Loading...'}</div>;
};
```

- `fetchData()` gets data from the server.
- `setInterval` starts polling every 5 seconds.
- `clearInterval` stops polling on unmount.

2. **Using `setTimeout` for a dynamic interval**

If the server has request limits, it is better to use `setTimeout` to avoid
request overlap.

```jsx
const PollingComponent = () => {
  const [data, setData] = useState(null);

  useEffect(() => {
    let isMounted = true;

    const fetchData = async () => {
      try {
        const response = await fetch('https://api.example.com/data');
        const result = await response.json();
        if (isMounted) setData(result);
      } catch (error) {
        console.error('Request error', error);
      } finally {
        if (isMounted) setTimeout(fetchData, 5000);
      }
    };

    fetchData();

    return () => {
      isMounted = false; // Prevents state updates after unmount
    };
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Loading...'}</div>;
};
```

Here, `setTimeout` is called only after the previous request has finished,
which helps avoid overlapping requests.

#### Summary

- `setInterval` is suitable for constant polling, but it can create request
  overlap.
- `setTimeout` gives more control and is better suited for adaptive polling.
- Under heavy load, consider WebSockets or Server-Sent Events.

</details>

<details>
<summary>75. How do you implement two-way data binding in React?</summary>

#### React

In React, two-way data binding is implemented through **controlled
components**, where component state (`state`) is synchronized with an input
field (`input`).

#### Example

```jsx
import { useState } from 'react';

const TwoWayBinding = () => {
  const [value, setValue] = useState('');

  return (
    <div>
      <input
        type="text"
        value={value}
        onChange={e => setValue(e.target.value)}
      />
      <p>Entered value: {value}</p>
    </div>
  );
};

export default TwoWayBinding;
```

#### How does it work?

1. **`value`** stores the current state of the entered value.

2. **`onChange`** updates the state when the `input` changes.

3. **The updated `value`** is displayed in the UI, providing two-way binding.

This approach allows you to control user input, validate it, and process it
before updating state.

</details>

<details>
<summary>76. What is Reverse Data Flow in React?</summary>

#### React

Reverse Data Flow in React means passing state changes from a child component
to a parent component. It is the opposite of the normal data flow, where the
parent passes props to the child.

#### In React, reverse data flow is usually implemented through:

1. **Callback functions:**

- The child component calls a callback passed to it through props in order to
  notify the parent component about changes or trigger some action.

- For example, when a value changes in the child component, it can call a
  function from the parent component that updates state.

2. **Example:**

```jsx
function Parent() {
  const [value, setValue] = useState('');

  const handleChange = newValue => {
    setValue(newValue);
  };

  return <Child onValueChange={handleChange} />;
}

function Child({ onValueChange }) {
  return <input type="text" onChange={e => onValueChange(e.target.value)} />;
}
```

- In this example, the child component passes the value to the parent through
  the `onValueChange` function, implementing reverse data flow.

</details>

<details>
<summary>77. What is state mutation and how can it be prevented?</summary>

#### React

State mutation is the direct modification of an object or array that stores
state without creating a copy. In React, this leads to unpredictable results
because React does not know that the state changed and will not rerender the
component.

#### To prevent state mutation, you should:

1. **Create copies of data** before changing it. For example, for arrays and
   objects:

- For arrays: `setItems([...items, newItem])`
- For objects: `setUser({ ...user, name: 'John' })`

2. **Use non-mutating methods**, such as `map()`, `filter()`, and `reduce()`
   for arrays, or `Object.assign()` for objects.

This allows React to correctly track changes and rerender components.

 </details>

<details>
<summary>78. What is React Strict Mode? What are its advantages?</summary>

#### React

**Strict Mode** is a special React tool for detecting potential problems in
code. It does not affect production behavior, but it helps improve code
quality during development.

It is enabled by wrapping components in `<React.StrictMode>`:

```jsx
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);
```

#### Advantages of Strict Mode

| **Feature**                                       | **Description**                                                                                             |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Detects unsafe lifecycle methods**              | Warns about deprecated methods (`componentWillMount`, `componentWillReceiveProps`, `componentWillUpdate`). |
| **Calls functions twice during development**      | Helps find side effects in `useEffect` and other hooks.                                                    |
| **Warns about deprecated APIs**                   | Points out old contexts (`contextType`) and unsafe patterns.                                               |
| **Detects unexpected behavior**                   | For example, calls `useEffect` twice to verify proper effect cleanup.                                      |

#### Should you use it?

Yes, if you want to catch problems during development. It can be a bit
annoying because of double rendering, but it helps uncover hidden bugs in the
code.

</details>

<details>
<summary>79. What are the recommended ways to check static types?</summary>

#### React

1. **TypeScript:** The most popular and complete approach to static typing in
   JavaScript/React. TypeScript adds strict types to your code, allowing type
   checks at compile time.

2. **PropTypes:** A built-in mechanism for checking prop types in React
   components. It is used for runtime validation. It does not provide static
   typing at compile time, but it allows prop checking while the application
   runs.

```jsx
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
};
```

3. **Flow:** Another mechanism for static typing in JavaScript. Flow is less
   popular than TypeScript, but it also allows types to be added and checked
   at compile time.

4. **ESLint with typing plugins:** You can use ESLint with plugins for type
   checking (for example, `eslint-plugin-flowtype` or
   `eslint-plugin-typescript`), but this does not provide the same depth of
   typing as TypeScript.

I recommend using **TypeScript**, because it integrates well with React and
other tools and provides full static typing at compile time.

</details>

<details>
<summary>80. How do you implement animation in React?</summary>

#### React

1. **CSS animations:** The simplest way is to use standard CSS animations or
   transitions.

```jsx

<div className="my-element">Hello</div>

<style jsx>{`
  .my-element {
    animation: fadeIn 1s ease-in-out;
  }

  @keyframes fadeIn {
    0% { opacity: 0; }
    100% { opacity: 1; }
  }
`}</style>
```

2. **React Transition Group:** For more complex animated transitions between
   components. This package allows you to control animation when components
   are added or removed.

```jsx

import { CSSTransition } from 'react-transition-group';

<CSSTransition in={isVisible} timeout={300} classNames="fade" unmountOnExit>
  <div>Content</div>
</CSSTransition>

<style jsx>{`
  .fade-enter {
    opacity: 0;
  }
  .fade-enter-active {
    opacity: 1;
    transition: opacity 300ms;
  }
  .fade-exit {
    opacity: 1;
  }
  .fade-exit-active {
    opacity: 0;
    transition: opacity 300ms;
  }
`}</style>
```

3. **Framer Motion:** A powerful animation library that allows you to create
   complex animations in React.

```jsx
import { motion } from 'framer-motion';

<motion.div
  animate={{ opacity: 1 }}
  initial={{ opacity: 0 }}
  transition={{ duration: 1 }}
>
  Hello
</motion.div>;
```

4. **React Spring:** For physics-based animations that allow you to create
   animations with realistic motion.

```jsx
import { useSpring, animated } from 'react-spring';

const props = useSpring({ opacity: 1, from: { opacity: 0 } });

<animated.div style={props}>Hello</animated.div>;
```

5. **Inline styles and JavaScript:** You can use `setState` and change styles
   based on component state.

```jsx
const [opacity, setOpacity] = useState(0);

useEffect(() => {
  setOpacity(1);
}, []);

return <div style={{ opacity }}>Hello</div>;
```

For more complex animation effects, it is recommended to use **Framer Motion**
or **React Spring**, because these libraries provide more features and make
complex animations easier to manage.

</details>

<details>
<summary>81. What are the most popular animation packages in React?</summary>

#### React

#### Popular animation packages in React:

1. **Framer Motion** is one of the most popular animation packages for React.
   It is easy to use, supports animations and transitions, works with
   drag-and-drop, and has a powerful API for creating complex animations.

2. **React Spring** is a library for creating physics-based animations. It
   uses an animation approach based on physical properties such as spring and
   friction. It is well suited for complex animations and interactions.

3. **GSAP (GreenSock Animation Platform)** is a powerful animation library
   that works not only with React but also with other frameworks. It is known
   for its speed and ability to create highly complex animations.

4. **React Transition Group** is a core library for transition animations in
   React. It allows you to create enter, exit, and state-change animations
   for components, giving flexibility in defining transitions.

5. **Lottie for React** lets you easily embed animations created in After
   Effects in JSON format. It is suitable for complex animations such as
   icons or interactive elements.

</details>

<details>
<summary>82. React DevTools: How do you use it for debugging?</summary>

#### React

1. **Installing React DevTools**

- If you use `Chrome` or `Firefox`, just install the `React Developer Tools`
  extension:
  - Chrome Web Store
  - Firefox Add-ons

- If you are debugging `Electron`, `React Native`, or another non-standard
  environment, install:

```sh
npm install -g react-devtools
react-devtools
```

2. **Main tabs and their usage**

- ⚛ **Components** → view component structure, state, and props.
- ⚡ **Profiler** → analyze performance and detect unnecessary renders.

3. **Debugging props and state**

- Open the Components tab.
- Select a component to see its `props`, `state`, and `context`.
- You can edit `state` and `props` directly in DevTools to test behavior
  changes.

4. **Detecting unnecessary renders**

- In the Profiler tab, click "Record", perform an interaction, then click
  "Stop".
- Check the color coding:
  - **Red** → expensive render.
  - **Yellow** → medium cost.
  - **Blue** → lightweight render.
- Optimize components with `React.memo()`, `useMemo()`, and `useCallback()`.

5. **Tools for debugging Context API**

- If you use React Context, you can inspect its values in DevTools.
- Select the component that uses `useContext()` and find the Context tab.

6. **Debugging rendering in Strict Mode**

- If `React DevTools` shows that a component renders twice, check
  `StrictMode` in `index.js`:

```jsx
<React.StrictMode>
  <App />
</React.StrictMode>
```

- It does not cause bugs; it only helps identify potential issues.

7. **Inspecting hooks**

- DevTools lets you see the state of hooks (`useState`, `useEffect`,
  `useReducer`).
- In the Components tab, select a component to see its `useState` values.

#### Summary:

**React DevTools** is a powerful tool for debugging state, props,
performance, and context. Use Profiler for optimization and Components to
track changes in state and props.

</details>

<details>
<summary>83. What are the most popular linters for React?</summary>

#### React

#### The most popular linters for React:

1. **ESLint** is the most common linter for `JavaScript`, supporting `React`
   through the `eslint-plugin-react` plugin. It checks code style, detects
   errors, and can work together with tools such as `Prettier` for formatting.

2. **Prettier** is a tool for automatic code formatting, often used together
   with `ESLint` to ensure a consistent code style.

3. **TSLint** is a linter for `TypeScript` that can also be used with
   `React`, although it is now largely being replaced by `ESLint` due to
   better flexibility and support.

These tools help maintain a high level of code quality and prevent errors in
large projects.

</details>

<details>
<summary>84. What is Next.js?</summary>

#### React

**Next.js** is a React framework that provides ready-made solutions for
server-side rendering (SSR), static generation (SSG), API routes, routing,
performance optimization, and SEO.

#### Main features:

- **Hybrid rendering:** support for SSR, SSG, and ISR (incremental
  regeneration).
- **Automatic routing:** files in `pages/` automatically become routes.
- **API routes:** creation of server endpoints in `pages/api/*` files.
- **Performance optimization:** automatic code splitting and bundle reduction.
- **App Router support:** a new approach based on React Server Components and
  `app/` instead of `pages/`.
- **Built-in support for Tailwind, TypeScript, ESLint, and other
  technologies**.

It is used to build high-performance web applications, blogs, e-commerce
solutions, and complex interfaces.

</details>

<details>
<summary>85. What are the main differences between Next.js and React?</summary>

#### React

#### Main differences between Next.js and React:

| **Criterion**                       | **React**                              | **Next.js**                                                              |
| ----------------------------------- | -------------------------------------- | ------------------------------------------------------------------------ |
| **Type**                            | A library for building UI              | A framework based on React                                               |
| **Rendering**                       | Client-side only (CSR)                 | Supports CSR, SSR, SSG, ISR                                              |
| **Routing**                         | Implemented manually via React Router  | File-based routing (`pages/` or `app/`)                                  |
| **SEO**                             | Poor support due to CSR                | Good SEO support (SSR, SSG)                                              |
| **API routes**                      | None                                   | Built-in ability to create API endpoints (`pages/api/`)                  |
| **Caching**                         | No built-in mechanisms                 | ISR allows pages to update without full regeneration                     |
| **Performance optimization**        | Uses third-party solutions             | Built-in optimizations (code splitting, automatic image loading)         |
| **Server Components support**       | Depends on configuration               | Built-in support for React Server Components (`app/`)                    |

#### Summary:

- **React** is suitable for SPAs that render on the client.

- **Next.js** is better suited for SEO-optimized projects, hybrid rendering,
  and high-performance web applications.

</details>

<details>
<summary>86. What is React Helmet Async used for?</summary>

#### React

**React Helmet Async** is an optimized version of **React Helmet** used for
dynamically updating the `<head>` (meta tags, titles, Open Graph tags, and so
on) in React applications.

#### Why is it needed?

1. **SEO optimization:** It allows you to change page titles, meta
   descriptions, and keywords.

2. **Dynamic `<head>`:** You can change tags for each page without reloading.

3. **SSR support (Server-Side Rendering):** Unlike regular React Helmet, this
   version works correctly in SSR applications without asynchronous issues.

#### Example:

```jsx
import { Helmet } from 'react-helmet-async';

function MyComponent() {
  return (
    <Helmet>
      <title>Home Page</title>
      <meta name="description" content="This is the description for the home page" />
    </Helmet>
  );
}
```

#### SSR (Next.js, Express):

```jsx
import { HelmetProvider, Helmet } from 'react-helmet-async';

const helmetContext = {};
const html = renderToString(
  <HelmetProvider context={helmetContext}>
    <App />
  </HelmetProvider>
);
const { helmet } = helmetContext;

const finalHtml = `

  <html>
    <head>
      ${helmet.title.toString()}
      ${helmet.meta.toString()}
    </head>
    <body>${html}</body>
  </html>
`;
```

#### Why is it better than `react-helmet`?

- Supports SSR without asynchronous errors.
- Lighter and faster.
- Does not create problems in `StrictMode`.

#### Summary:

If you need SEO in React + SSR, it is worth using `react-helmet-async`.

</details>

<details>
<summary>87. What is a Distributed Component?</summary>

#### React

A **Distributed Component** is a concept where a component is split into
several independent parts that can render or execute logic separately, but
work together.

#### Implementation examples:

1. **Code Splitting**

- Components are loaded only when needed, reducing the initial bundle size.

```jsx
import { lazy, Suspense } from 'react';

const LazyComponent = lazy(() => import('./LazyComponent'));

function App() {
  return (
    <Suspense fallback={<div>Loading...</div>}>
      <LazyComponent />
    </Suspense>
  );
}
```

2. **Container-Presentational Pattern**

- Separates logic (container) from presentation (presentational component).

```jsx
function DataContainer({ children }) {
  const [data, setData] = useState(null);

  useEffect(() => {
    fetch('/api/data')
      .then(res => res.json())
      .then(setData);
  }, []);

  return children(data);
}

function Presentational({ data }) {
  return <div>{data ? JSON.stringify(data) : 'Loading...'}</div>;
}

function App() {
  return (
    <DataContainer>{data => <Presentational data={data} />}</DataContainer>
  );
}
```

3. **Micro Frontends**

- Using separate autonomous components in different parts of an application.
- For example, different teams build separate parts of a large project
  (`React`, `Vue`, `Angular`) and integrate them together.

#### When to use:

- For performance optimization (lazy loading).

- To simplify code maintenance (separating logic).

- For scalable applications (micro frontends).

</details>

<details>
<summary>88. What is a Switching Component?</summary>

#### React

A **Switching Component** in React is a pattern in which a component
dynamically renders one of its child components based on a certain condition.
It is used when different components need to be displayed depending on state,
route, or received data.

#### Example 1: Switching based on state

```jsx
const SwitchingComponent = ({ type }) => {
  switch (type) {
    case 'success':
      return <SuccessMessage />;
    case 'error':
      return <ErrorMessage />;
    default:
      return <DefaultMessage />;
  }
};
```

```jsx
const App = () => {
  return <SwitchingComponent type="success" />;
};
```

- `type` determines which component will be displayed.

#### Example 2: Using with React Router

```jsx
import { Route, Routes } from 'react-router-dom';

const App = () => {
  return (
    <Routes>
      <Route path="/" element={<Home />} />
      <Route path="/about" element={<About />} />
      <Route path="\*" element={<NotFound />} />
    </Routes>
  );
};
```

- Here, `Routes` acts as a switching component for rendering the appropriate
  component depending on the URL.

#### Example 3: Conditional rendering through an object

```jsx
const components = {
  success: SuccessMessage,
  error: ErrorMessage,
  default: DefaultMessage,
};

const SwitchingComponent = ({ type }) => {
  const Component = components[type] || components.default;
  return <Component />;
};
```

- This is a cleaner version without `switch`.

Switching components simplify logic and make code more readable when
different components need to be rendered conditionally.

</details>

<details>
<summary>89. What is Reselect and how does it work?</summary>

#### React

**Reselect** is a library for creating efficient selectors in Redux. It helps
optimize state data retrieval and avoid unnecessary component renders through
memoization.

#### How does Reselect work?

Reselect uses **memoization** to reuse calculation results if the input data
has not changed.

1. **It accepts input selectors** that retrieve data from state.

2. **It computes a value** based on the retrieved data.

3. **It caches the result** so that calculations are not performed when the
   input values are the same.

#### Example:

```jsx
import { createSelector } from 'reselect';

// Input selector gets all users
const selectUsers = state => state.users;

// Input selector gets the active filter
const selectFilter = state => state.filter;

// Memoized selector filters users
export const selectFilteredUsers = createSelector(
  [selectUsers, selectFilter],
  (users, filter) => users.filter(user => user.role === filter)
);
```

- Without Reselect, the component would check the entire `users` array on
  every render.
- With Reselect, the selector runs only when `users` or `filter` changes.

#### Advantages of Reselect:

- Reduces the number of unnecessary `mapStateToProps` calls.
- Avoids unnecessary component renders.
- Combines easily with Redux.
- Improves performance.

</details>

<details>
<summary>90. What data types can `render` return?</summary>

#### React

The `render()` method in React can return:

1. **JSX or a React element**

```jsx
render() {
return <div>Hello, World!</div>;
}
```

2. **An array of elements (fragmented rendering)**

```jsx
render() {
return [
<li key="1">Item 1</li>,
<li key="2">Item 2</li>
];
}
```

3. **Fragments (`React.Fragment`)**

```jsx
render() {
return (
<>
<h1>Title</h1>
<p>Description</p>
</>
);
}
```

4. **`null` (render nothing)**

```jsx
render() {
return null;
}
```

5. **Boolean values (ignored)**

```jsx
render() {
return false; // Nothing will be displayed
}
```

6. **Text values (rendered as text)**

```jsx
render() {
return "Hello, World!";
}
```

7. **Portals (rendering into a DOM element outside the parent component)**

```jsx
import { createPortal } from 'react-dom';

render() {
return createPortal(<div>Modal</div>, document.getElementById('modal-root'));
}
```

#### Summary:

The main option is JSX or React elements, but you can also return arrays,
fragments, `null`, text, or render through portals.

</details>

<details>
<summary>91. How does React handle or restrict the use of props of a certain type?</summary>

#### React

React restricts the use of props of a certain type with `PropTypes` or
`TypeScript`.

1. **Using PropTypes (built-in type checking)**

```jsx
import PropTypes from 'prop-types';

const MyComponent = ({ name, age, isActive }) => {
  return (
    <div>
      <h1>{name}</h1>
      <p>Age: {age}</p>
      <p>{isActive ? 'Active' : 'Inactive'}</p>
    </div>
  );
};

// Prop type definitions
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isActive: PropTypes.bool,
};
```

- `PropTypes.string.isRequired` means `name` is a required prop.
- `PropTypes.number` means `age` must be a number.
- `PropTypes.bool` means `isActive` must be a boolean value.

If incorrect types are passed, React will show a warning in the console
(development mode only).

2. **Using TypeScript (strict compile-time checking)**

```tsx
type MyComponentProps = {
  name: string;
  age?: number;
  isActive: boolean;
};

const MyComponent: React.FC<MyComponentProps> = ({ name, age, isActive }) => {
  return (
    <div>
      <h1>{name}</h1>
      <p>Age: {age}</p>
      <p>{isActive ? 'Active' : 'Inactive'}</p>
    </div>
  );
};
```

- `name: string` is a required string prop.
- `age?: number` is an optional numeric prop.
- `isActive: boolean` is a required boolean prop.

TypeScript reports an error before the code runs if incorrect props are
passed.

#### What should you choose?

| **Method**     | **Advantages**                          | **Disadvantages**                         |
| -------------- | --------------------------------------- | ----------------------------------------- |
| **PropTypes**  | Simple, works in JavaScript             | Checks only at runtime, weaker safety     |
| **TypeScript** | Strict typing, catches errors earlier   | Requires compilation, more complex syntax |

If the project uses **TypeScript**, **PropTypes** are usually not needed. If
it uses **JavaScript**, **PropTypes** provide basic validation.

</details>

<details>
<summary>92. What is the difference between rendering and mounting?</summary>

#### React

Difference between rendering and mounting in React

| **Process**               | **Description**                                                                                                                                                                                     |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Mounting**              | A component is created and added to the DOM for the first time. `constructor`, `render`, `componentDidMount` (in classes), or `useEffect` with an empty dependency array (in functional components) are called. |
| **Rendering**             | A call to `render()` or a repeated call of a functional component to update content. It happens when `state`, `props`, or `forceUpdate()` changes.                                                  |

#### Mounting example

```jsx
useEffect(() => {
  console.log('Component mounted');
}, []); // Runs once on mount
```

#### Rendering example

```jsx
const [count, setCount] = useState(0);

useEffect(() => {
  console.log('Component rendered');
}); // Runs on every render

return <button onClick={() => setCount(count + 1)}>+</button>;
```

Here, rendering happens every time `count` changes.

</details>

<details>
<summary>93. What is reactive data flow in React?</summary>

#### React

**Reactive Data Flow** in React means that changes in a component's state or
props automatically lead to UI updates without the need to manually trigger a
rerender.

#### Main principles:

1. **One-way data flow:** React passes data from top to bottom (from parent
   components to child components).

2. **Declarative approach:** You describe what should be rendered, and React
   handles the updates itself.

3. **Automatic updates:** If `state` or `props` change, React rerenders only
   the changed parts.

#### Example of a reactive update:

```jsx
import { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Counter: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increase</button>
    </div>
  );
}
```

#### How does it work?

- `useState` creates the `count` state.

- On click, `setCount(count + 1)` updates the state.

- React automatically rerenders the component with the new data.

#### Is React fully reactive?

- No. Unlike "reactive" frameworks such as Svelte or Solid.js, React does not
  update the DOM when a variable changes directly. It uses the Virtual DOM
  and triggers rerenders when `state` or `props` change.

#### Summary:

- Reactive data flow in React means that the UI updates automatically when
  state changes, but it does so using the Virtual DOM and batched updates for
  optimization.

</details>

<details>
<summary>94. Is React reactive?</summary>

#### React

React is not a purely reactive library like Vue or Svelte. However, React has
some characteristics that make it similar to reactive frameworks:

1. **Automatic UI updates:** React updates the UI automatically when a
   component's state or props change, which resembles reactive approaches.
   This happens through rendering and change comparison.

2. **Functional components and hooks:** Using hooks such as `useState` and
   `useEffect` creates a reactive effect where changes in state or props lead
   to component rerenders.

3. **Partial reactivity:** React rerenders only the components whose state or
   props changed. This is a reactive approach, but unlike other frameworks,
   React does not handle dependencies or values through automatic observers.

So, React has some reactive principles, but it is not a fully reactive
framework.

</details>

<details>
<summary>95. What options for implementing drag-and-drop in React do you know?</summary>

#### React

Drag-and-drop in React can be implemented in several ways:

- **Using the HTML5 API** (`onDragStart`, `onDrop`)

- **Libraries** (`react-dnd`, `dnd-kit`)

1. **Using the native Drag-and-Drop API**

```jsx
import { useState } from 'react';

function DragAndDrop() {
  const [items, setItems] = useState(['Item 1', 'Item 2', 'Item 3']);

  const onDragStart = (e, index) => {
    e.dataTransfer.setData('text/plain', index);
  };

  const onDrop = (e, targetIndex) => {
    const sourceIndex = e.dataTransfer.getData('text/plain');
    const newItems = [...items];
    const [movedItem] = newItems.splice(sourceIndex, 1);
    newItems.splice(targetIndex, 0, movedItem);
    setItems(newItems);
  };

  return (
    <ul>
      {items.map((item, index) => (
        <li
          key={index}
          draggable
          onDragStart={e => onDragStart(e, index)}
          onDragOver={e => e.preventDefault()}
          onDrop={e => onDrop(e, index)}
          style={{ padding: '10px', border: '1px solid black', margin: '5px' }}
        >
          {item}
        </li>
      ))}
    </ul>
  );
}

export default DragAndDrop;
```

- Simple and does not require third-party libraries.
- Limited control and does not support complex cases.

2. **Using `react-dnd` (a more powerful option)**

```bash
   npm install react-dnd react-dnd-html5-backend
```

```jsx
import { DndProvider, useDrag, useDrop } from 'react-dnd';
import { HTML5Backend } from 'react-dnd-html5-backend';
import { useState } from 'react';

const ItemType = 'ITEM';

function DraggableItem({ item, index, moveItem }) {
  const [{ isDragging }, drag] = useDrag({
    type: ItemType,
    item: { index },
    collect: monitor => ({
      isDragging: monitor.isDragging(),
    }),
  });

  const [, drop] = useDrop({
    accept: ItemType,
    hover: draggedItem => {
      if (draggedItem.index !== index) {
        moveItem(draggedItem.index, index);
        draggedItem.index = index;
      }
    },
  });

  return (
    <div
      ref={node => drag(drop(node))}
      style={{
        padding: '10px',
        margin: '5px',
        border: '1px solid black',
        backgroundColor: isDragging ? 'lightgray' : 'white',
      }}
    >
      {item}
    </div>
  );
}

function DragAndDrop() {
  const [items, setItems] = useState(['Item 1', 'Item 2', 'Item 3']);

  const moveItem = (from, to) => {
    const updatedItems = [...items];
    const [movedItem] = updatedItems.splice(from, 1);
    updatedItems.splice(to, 0, movedItem);
    setItems(updatedItems);
  };

  return (
    <DndProvider backend={HTML5Backend}>
      {items.map((item, index) => (
        <DraggableItem
          key={index}
          item={item}
          index={index}
          moveItem={moveItem}
        />
      ))}
    </DndProvider>
  );
}

export default DragAndDrop;
```

- Flexible and supports complex cases.
- Easier to work with nested elements.
- Adds an extra dependency.

3. **Using `dnd-kit` (a simple and modern option)**

```bash
   npm install @dnd-kit/core @dnd-kit/sortable
```

```jsx
import { DndContext, closestCenter } from '@dnd-kit/core';
import { SortableContext, useSortable, arrayMove } from '@dnd-kit/sortable';
import { useState } from 'react';

function SortableItem({ id }) {
  const { attributes, listeners, setNodeRef, transform, transition } =
    useSortable({ id });

  return (
    <div
      ref={setNodeRef}
      {...attributes}
      {...listeners}
      style={{
        padding: '10px',
        margin: '5px',
        border: '1px solid black',
        backgroundColor: 'white',
        transform: transform ? `translateY(${transform.y}px)` : undefined,
        transition,
      }}
    >
      {id}
    </div>
  );
}

function DragAndDrop() {
  const [items, setItems] = useState(['Item 1', 'Item 2', 'Item 3']);

  const onDragEnd = ({ active, over }) => {
    if (active.id !== over.id) {
      setItems(items => {
        const oldIndex = items.indexOf(active.id);
        const newIndex = items.indexOf(over.id);
        return arrayMove(items, oldIndex, newIndex);
      });
    }
  };

  return (
    <DndContext collisionDetection={closestCenter} onDragEnd={onDragEnd}>
      <SortableContext items={items}>
        {items.map(id => (
          <SortableItem key={id} id={id} />
        ))}
      </SortableContext>
    </DndContext>
  );
}

export default DragAndDrop;
```

- Modern API, lighter than `react-dnd`.
- Easy to use.
- Supports sorting (`sortable`).

#### Summary:

- If you need something simple → **HTML5 Drag-and-Drop API**.

- If you need flexible control → **react-dnd**.

- If you want a modern, lightweight option → **dnd-kit**.

</details>

<details>
<summary>96. How do you render HTML code in a React component?</summary>

#### React

Use `dangerouslySetInnerHTML`, but be careful: it can lead to XSS attacks if
you insert unsanitized data.

#### Example:

```jsx
function MyComponent() {
  const htmlContent = "<p style='color: red;'>This is HTML code</p>";

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
}
```

If you work with dynamic data, be sure to sanitize it before inserting it.

</details>

<details>
<summary>97. How do you conditionally add a class in React?</summary>

#### React

In React, conditional class assignment to elements is usually done through the
`className` attribute and by using the ternary operator or helper functions to
determine conditions.

#### Main approaches:

1. **Ternary operator**

```jsx
function MyComponent({ isActive }) {
  return (
    <div className={isActive ? 'active-class' : 'inactive-class'}>Hello</div>
  );
}
```

- If `isActive` equals `true`, the `active-class` class will be added to the
  element.
- Otherwise, `inactive-class` will be added.

2. **Template strings**

```jsx
function MyComponent({ isHighlighted }) {
  return (
    <div className={`base-class ${isHighlighted ? 'highlighted-class' : ''}`}>
      Hello
    </div>
  );
}
```

- `base-class` is always added.
- If `isHighlighted` equals `true`, `highlighted-class` is added as well.

3. **The `clsx` library**

- `clsx` helps work with classes in a cleaner way.

```bash
npm install clsx
```

```jsx
import clsx from 'clsx';

function MyComponent({ isActive, isDisabled }) {
  return (
    <div
      className={clsx('base-class', {
        'active-class': isActive,
        'disabled-class': isDisabled,
      })}
    >
      Hello
    </div>
  );
}
```

- `clsx` allows you to easily add multiple classes based on conditions.

4. **The `classnames` library**

- Similar to `clsx`, but with more features.

```bash
npm install classnames
```

```jsx
import classNames from 'classnames';

function MyComponent({ isActive, isDisabled }) {
  return (
    <div
      className={classNames('base-class', {
        'active-class': isActive,
        'disabled-class': isDisabled,
      })}
    >
      Hello
    </div>
  );
}
```

5. **Moving the logic into a separate function**

```jsx
function getClassName(isActive, isDisabled) {
  let className = 'base-class';
  if (isActive) className += ' active-class';
  if (isDisabled) className += ' disabled-class';
  return className;
}

function MyComponent({ isActive, isDisabled }) {
  return <div className={getClassName(isActive, isDisabled)}>Hello</div>;
}
```

- The class selection logic becomes more readable and can be reused.

#### Summary:

- For simple cases, the ternary operator or template strings work well.

- For complex conditions, it is better to use `clsx` or `classnames`, which
  provide convenience and readability.

</details>

<details>
<summary>98. How do you run code before removing a component from the tree?</summary>

#### React

To run code before removing a component from the tree in React, the following
approaches are used:

1. **Class components:** `componentWillUnmount`

- For class components, there is the `componentWillUnmount` lifecycle method,
  which is called before the component is removed.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Component will be removed');
  }

  render() {
    return <div>My component</div>;
  }
}
```

2. **Functional components:** `useEffect` with cleanup

- In functional components, cleanup can be done in `useEffect` by returning a
  function that runs before the component is removed.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Component will be removed');
    };
  }, []);

  return <div>My component</div>;
}
```

3. **Handling before page close (`beforeunload`)**

- If you need to run code before closing the tab or reloading the page:

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('Page is closing');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Summary

- `componentWillUnmount` is for class components.

- `useEffect` with `return` is for functional components.

- `beforeunload` is for cases where you need to react to leaving the page.

</details>

<details>
<summary>99. What is `useReducer()`?</summary>

#### React

- `useReducer()` is a React hook used for state management in functional
  components. It is an alternative to `useState()` that is suitable for
  complex state update logic, especially when changes depend on the previous
  state.

#### Syntax:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` is a function that takes `state` and `action` and returns a new
  state.

- `initialState` is the initial state.

- `dispatch` is the function used to call the reducer with a specific
  `action`.

#### Example:

```jsx
import { useReducer } from 'react';

const initialState = { count: 0 };

function reducer(state, action) {
  switch (action.type) {
    case 'increment':
      return { count: state.count + 1 };
    case 'decrement':
      return { count: state.count - 1 };
    default:
      return state;
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, initialState);

  return (
    <div>
      <p>Count: {state.count}</p>
      <button onClick={() => dispatch({ type: 'increment' })}>+</button>
      <button onClick={() => dispatch({ type: 'decrement' })}>-</button>
    </div>
  );
}
```

#### When to use:

- When state has complex logic or dependencies.

- When you need to standardize state updates through `dispatch`.

- For scalability, for example, when used in global state.

</details>

<details>
<summary>100. How do you use `React.lazy` and `React.Suspense` for code splitting?</summary>

#### React

`React.lazy` and `React.Suspense` are used for **dynamic component loading** in
React, which enables **code splitting**. This means that parts of the code are
loaded only when they are needed, thereby improving your application's
performance.

#### How it works:

1. `React.lazy()` allows a component to be loaded lazily.

2. `React.Suspense` is used to wrap a part of the code that has not yet loaded
   and allows fallback content (for example, a loader) to be shown while the
   components are loading.

#### Example:

1. **Dynamic component loading:**

- First, create a component that will be loaded dynamically.

```jsx
// Dynamically loaded component
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Wrapper with `React.Suspense`:**

- Now use `React.Suspense` to show a loader while the component is loading.

```jsx
function App() {
  return (
    <div>
      <h1>My application</h1>

      {/* Wrapper for dynamically loaded components */}
      <React.Suspense fallback={<div>Loading...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Description:**

- `React.lazy()` takes a function that dynamically imports a module.

- `React.Suspense` wraps the component that uses `React.lazy()` and shows
  fallback content (in this case, the text "Loading...") until the component
  finishes loading.

#### Advantages:

- Improves performance by loading components only when needed.

- Reduces the initial bundle size because parts of the application are loaded
  on demand.

This approach is especially useful in large applications, where code can be
split into parts to reduce page load time.

</details>

<details>
<summary>101. What approaches are used to perform HTTP requests in React?</summary>

#### React

#### Approaches to making HTTP requests in React

React does not have a built-in API for making HTTP requests, but you can use
third-party libraries or standard JavaScript tools. Here are the main
approaches:

1. **Using the Fetch API**

- A standard tool for making HTTP requests in JavaScript.

**Example:**

```jsx
import React, { useEffect, useState } from 'react';

function FetchExample() {
  const [data, setData] = useState([]);
  const [error, setError] = useState(null);

  useEffect(() => {
    fetch('https://jsonplaceholder.typicode.com/posts')
      .then(response => {
        if (!response.ok) {
          throw new Error('Network response was not ok');
        }
        return response.json();
      })
      .then(data => setData(data))
      .catch(error => setError(error.message));
  }, []);

  return (
    <div>
      {error ? (
        <p>Error: {error}</p>
      ) : (
        <ul>
          {data.map(post => (
            <li key={post.id}>{post.title}</li>
          ))}
        </ul>
      )}
    </div>
  );
}

export default FetchExample;
```

2. **Using Axios**

- A library for making HTTP requests with simpler syntax and built-in support
  for interceptors.

**Example:**

```jsx
import React, { useEffect, useState } from 'react';
import axios from 'axios';

function AxiosExample() {
  const [data, setData] = useState([]);
  const [error, setError] = useState(null);

  useEffect(() => {
    axios
      .get('https://jsonplaceholder.typicode.com/posts')
      .then(response => setData(response.data))
      .catch(error => setError(error.message));
  }, []);

  return (
    <div>
      {error ? (
        <p>Error: {error}</p>
      ) : (
        <ul>
          {data.map(post => (
            <li key={post.id}>{post.title}</li>
          ))}
        </ul>
      )}
    </div>
  );
}

export default AxiosExample;
```

3. **React Query (TanStack Query)**

- A library for managing the state of data obtained through HTTP requests. It
  supports caching, retries, and data refreshes.

**Example:**

```jsx
import React from 'react';
import { useQuery } from 'react-query';
import axios from 'axios';

function ReactQueryExample() {
  const { data, error, isLoading } = useQuery('posts', async () => {
    const response = await axios.get(
      'https://jsonplaceholder.typicode.com/posts'
    );
    return response.data;
  });

  if (isLoading) return <p>Loading...</p>;
  if (error) return <p>Error: {error.message}</p>;

  return (
    <ul>
      {data.map(post => (
        <li key={post.id}>{post.title}</li>
      ))}
    </ul>
  );
}

export default ReactQueryExample;
```

4. **GraphQL (Apollo Client)**

- Apollo Client is used to work with GraphQL APIs.

**Example:**

```jsx
import React from 'react';
import { useQuery, gql } from '@apollo/client';

const GET_POSTS = gql`
  query GetPosts {
    posts {
      id
      title
    }
  }
`;

function ApolloExample() {
  const { loading, error, data } = useQuery(GET_POSTS);

  if (loading) return <p>Loading...</p>;
  if (error) return <p>Error: {error.message}</p>;

  return (
    <ul>
      {data.posts.map(post => (
        <li key={post.id}>{post.title}</li>
      ))}
    </ul>
  );
}

export default ApolloExample;
```

5. **Custom Hooks**

- You can create your own hooks to reuse request logic.

**Example:**

```jsx
import { useState, useEffect } from 'react';

function useFetch(url) {
  const [data, setData] = useState(null);
  const [error, setError] = useState(null);
  const [loading, setLoading] = useState(true);

  useEffect(() => {
    fetch(url)
      .then(response => response.json())
      .then(data => {
        setData(data);
        setLoading(false);
      })
      .catch(error => {
        setError(error.message);
        setLoading(false);
      });
  }, [url]);

  return { data, error, loading };
}

export default useFetch;
```

#### The choice of approach depends on your needs:

- **Fetch API:** for simple requests.

- **Axios:** if more flexibility is needed (interceptors, timeouts).

- **React Query:** for data cache management.

- **GraphQL/Apollo Client:** if the API is built with GraphQL.

- **Custom Hooks:** for reusing request logic.

</details>

<details>
<summary>102. What is the difference between `createElement` and `cloneElement`?</summary>

#### React

| **Method**            | **Description**                                                                              | **Main use case**                                                                       |
| --------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| `React.createElement` | Creates a new React element. Takes the element type, props, and child elements as arguments. | Used to create React elements from scratch, usually during JSX rendering.               |
| `React.cloneElement`  | Clones an existing React element, allowing its props or children to be changed.              | Used to create modified copies of already existing React elements.                      |

#### Examples:

`React.createElement`

```jsx
const element = React.createElement(
  'div',
  { className: 'example' },
  'Hello, React!'
);
```

Result: `<div class="example">Hello, React!</div>` is created.

`React.cloneElement`

```jsx
const originalElement = <button className="primary">Click</button>;

const clonedElement = React.cloneElement(originalElement, {
  className: 'secondary',
});
```

Result: a clone of `<button class="secondary">Click</button>` with a changed class.

#### Difference:

- `createElement`: creates a completely new element.

- `cloneElement`: works from an already existing element, allowing its props
  or content to be changed.

</details>

<details>
<summary>103. Does the `lazy` function support named exports?</summary>

#### React

- No, the `React.lazy` function does not support named exports. It works only
  with default exports. If you have a module with a named export and want to
  use it with `React.lazy`, you need to create a wrapper that exports the
  required component as default.

#### Wrapper example:

```jsx
// Named export
export const MyComponent = () => {
  return <div>Hello, World!</div>;
};

// Using React.lazy
const LazyComponent = React.lazy(() =>
  import('./MyComponent').then(module => ({ default: module.MyComponent }))
);

export default LazyComponent;
```

- Here we explicitly specify that `module.MyComponent` should be used as the
  default export.

</details>

<details>
<summary>104. What are the advantages of React?</summary>

#### React

#### Advantages of React

1. **High performance**

- Using the **Virtual DOM** minimizes updates to the real **DOM**, making
  rendering faster.

2. **Component-based approach**

- An application is built from **reusable components**, which simplifies
  development and maintenance.

3. **Unidirectional Data Flow**

- Data flows down the component hierarchy, which makes state changes easier to
  track.

4. **Hooks support**

- `useState`, `useEffect`, `useMemo`, and others allow state and effects to
  be managed in functional components without classes.

5. **Server-side rendering (SSR) and static generation (SSG)**

- With Next.js, SEO can be optimized and application performance improved.

6. **Flexibility and ecosystem**

- React can be used together with **Redux**, **Zustand**, **MobX**,
  **React Query**, and others.

- It supports **React Native** for building mobile applications.

7. **Advanced debugging capabilities**

- **React DevTools** allows you to inspect component structure, state, and
  props in real time.

8. **Active community and Facebook support**

- A wide selection of libraries and ready-made solutions, and rapid framework
  evolution.

React is a flexible, high-performance, and modern tool for web application
development.

</details>

<details>
<summary>105. What are the limitations of React?</summary>

#### React

1. **A large number of rerenders:** If components are not optimized properly,
   this can lead to excessive rerenders that hurt performance.

2. **The need to manage state:** Without proper state management, an
   application can become difficult to maintain.

3. **One-way data flow:** Data flows in only one direction, which can make it
   harder to pass data through multiple component levels.

4. **Reactivity:** React updates the DOM through the Virtual DOM, but this can
   be inefficient for very large, highly dynamic applications.

5. **Dependence on JavaScript:** Support is poor without JavaScript on the
   client side.

6. **Learning curve for beginners:** Although React concepts are fairly
   simple, properly mastering hooks, context, and optimization can be hard.

7. **Third-party tools:** Although many tools exist, integrating them can be
   complicated in large projects.

</details>

<details>
<summary>106. What was the `registerServiceWorker()` method used for in React?</summary>

#### React

`registerServiceWorker()` was used to register a Service Worker in Create
React App (before being removed from CRA in version 4).

#### Purpose:

- Caching resources for offline mode

- Speeding up application loading

- Background updating of resources

#### Example of usage (before CRA 4):

```javascript
import { register } from './serviceWorker';

register();
```

- After its removal from CRA, a Service Worker must be configured manually via
  `navigator.serviceWorker.register()`.

- In **React 19**, there is no built-in `registerServiceWorker()`, because it
  was removed earlier from the CRA tooling. If you need a Service Worker,
  register it manually.

Summary: in modern React setups, this method is no longer relevant, and a
Service Worker needs to be configured manually.

</details>

<details>
<summary>107. What are synthetic events (`SyntheticEvent`) in React?</summary>

#### React

- **SyntheticEvent** in React is a wrapper over native browser events that
  provides cross-browser compatibility and improves performance.

#### Features of SyntheticEvent:

- It works the same in all browsers.

- It uses event pooling, which helps avoid retaining unnecessary objects in
  memory.

- All events are normalized and have the same properties regardless of the
  browser.

#### Example:

```jsx
function MyComponent() {
  const handleClick = event => {
    console.log(event.type); // "click"
    console.log(event.nativeEvent); // Original browser event
  };

  return <button onClick={handleClick}>Click</button>;
}
```

#### Main methods:

- `event.preventDefault()` prevents default behavior.

- `event.stopPropagation()` stops event bubbling.

- `event.persist()` disables pooling so the event is not reset.

</details>

<details>
<summary>108. What are the performance optimization techniques in React?</summary>

#### React

#### React performance optimization techniques:

1. **Component memoization**

- Use `React.memo()` to prevent unnecessary rerenders.
- Use `useMemo()` to cache calculations.
- Use `useCallback()` to keep functions stable.

2. **Rerender optimization**

- Avoid unnecessary state (`useState`) and props.
- Use `shouldComponentUpdate` and `React.PureComponent` in class components.
- Optimize context (`Context API`) by not passing unnecessary values.
- Use selectors (`Reselect`, `Zustand`, `Jotai`) to minimize updates.

3. **List virtualization**

- Use `react-window` or `react-virtualized` to display only visible items.

4. **Caching and debouncing**

- Use `useMemo()` and `useCallback()` for heavy calculations.
- Use debouncing (`lodash.debounce`) or throttling (`lodash.throttle`) for
  user input.

5. **Lazy loading**

- Use `React.lazy()` + `Suspense` for code splitting.
- Use dynamic module imports (`import()`).

6. **Avoiding unnecessary effects in `useEffect`**

- Pass dependencies correctly.
- Use `useRef` to store values without rerendering.

7. **Image optimization**

- Use `next/image` in Next.js.
- Optimize sizes and formats (`WebP`, `AVIF`).

8. **React Router optimization**

- Use `React.lazy()` for pages.
- Avoid unnecessary rerenders through proper state updates.

9. **State splitting**

- Use local state where global state is not needed.
- Move global changes into `Redux`, `Zustand`, or `Recoil`.

10. **Using Web Workers**

- For heavy calculations, so the main thread is not blocked.

</details>

<details>
<summary>109. Is it possible to use `async/await` in React?</summary>

#### React

- Yes, `async/await` can be used in React, but there are some points worth
  noting:

1. **Usage in components:** `async/await` cannot be used directly in the
   component body in place of rendering logic or in methods like `render()`.
   However, you can use it in event handlers or inside hooks such as
   `useEffect`.

2. **Tools for asynchronous requests:**

- Use `async/await` inside functions called from hooks, for example:

```jsx
useEffect(() => {
  const fetchData = async () => {
    const response = await fetch('https://api.example.com');
    const data = await response.json();
    setData(data);
  };
  fetchData();
}, []);
```

3. **Error handling:** do not forget to use `try/catch` to handle errors in
   asynchronous requests:

```jsx
const fetchData = async () => {
  try {
    const response = await fetch('https://api.example.com');
    const data = await response.json();
    setData(data);
  } catch (error) {
    console.error('Error fetching data:', error);
  }
};
```

Thus, `async/await` can and should be used for asynchronous operations in
React, but it must be organized properly within components.

</details>

<details>
<summary>110. What is the history of React's evolution?</summary>

#### React

Here is a brief history of React's evolution:

1. **2011**

- React was created at Facebook for internal needs. It was developed by
  engineer Jordan Walke to solve the problem of efficient UI updates.

2. **2013**

- Facebook released React as an open-source library. At first, the community
  was skeptical because of JSX, which seemed unusual.

3. **2015**

- React 0.14 was released: React and ReactDOM were separated, which made the
  library more modular.

- Facebook introduced React Native, which made it possible to build native
  mobile applications with React.

4. **2016**

- React 15 was released. Major updates focused on performance improvements
  through a new rendering engine.

5. **2017**

- React 16 (Fiber) was released. Fiber became the new architecture that
  provided improved performance and support for asynchronous rendering.

- Support for portals and **Error Boundaries** was added.

6. **2018**

- Facebook introduced React Hooks, which allowed state and lifecycle methods
  to be used in functional components. This became a major shift in the way
  components were built.

7. **2019**

- React 16.8 was released with official support for hooks.

- Concurrent Mode was improved experimentally.

8. **2020**

- React 17 was released. The main goal was to simplify gradual React upgrades
  in large projects.

- Support for modern tools and new JSX capabilities was added.

9. **2022**

- React 18 was released. The main additions were Concurrent Rendering and the
  new `useTransition` and `useDeferredValue` APIs, which improve performance
  in dynamic applications.

10. **2024**

- React 19 was released.

- Server rendering (RSC) was improved.

- Support for the new `use` function was added.

- The form system, rendering errors, and JSX syntax without `import React`
  were improved.

- React Compiler was updated for automatic performance optimization.

#### Main changes during the evolution:

- From class components to functional components with hooks.

- Support for server-side rendering (SSR).

- Concurrent Mode for smoother UI updates.

- React integration with mobile development through React Native.

React has remained popular thanks to its high performance, ease of use, and
ongoing support from Facebook.

</details>

<details>
<summary>111. What new features were added in React 19?</summary>

#### React

React 19 introduced a number of significant updates aimed at improving
performance and developer experience. Here are the key additions:

1. **New rendering system:** Asynchronous rendering was introduced, allowing
   React to manage UI updates more efficiently and improve user interaction.

2. **React Compiler:** A new compiler automatically optimizes rerenders,
   reducing unnecessary updates and improving application performance.

3. **Actions API:** This is a new approach for managing state and data
   mutations on the server, simplifying side effect handling and data
   requests.

4. **Improved Suspense mechanics:** This gives developers finer control over
   asynchronous data loading, making hydration and fallback state management
   easier.

5. **The `use` hook:** A new hook that simplifies working with asynchronous
   data and improves support for server components.

6. **Native support for meta tags:** `meta`, `title`, `link`, and other tags
   are now supported without additional libraries, making SEO and resource
   management easier.

- These changes make React 19 a more powerful and convenient tool for
  developers, improving both application performance and the development
  experience.

</details>

<details>
<summary>112. What do React developers recommend using after Create React App became deprecated?</summary>

#### React

After support for Create React App ended in February 2025, developers were
advised to use modern frameworks to build new React applications. These
frameworks support client-side rendering (CSR) and single-page applications
(SPAs), which can be deployed to a CDN or static hosting services without
requiring a server.

#### Recommended frameworks:

1. **Next.js:** Offers powerful capabilities such as server-side rendering and
   static site generation, providing high performance and SEO optimization.

2. **React Router:** Makes it possible to build SPAs with dynamic routing,
   allowing navigation in the application to be managed easily.

3. **Expo:** Simplifies React Native development by providing tools for
   building cross-platform mobile applications with JavaScript and React.

</details>

<details>
<summary>113. How does the `useDeferredValue` hook work in React?</summary>

#### React

`useDeferredValue` is a React hook that appeared in React 18 as part of
Concurrent features. It allows updates of certain values (state or props) to
be deferred, lowering their priority and giving React a chance to update the
UI with more important work first.

This is very useful when a value changes frequently and updating the UI on
every change takes a lot of resources.

##### What is `useDeferredValue` used for?

- To avoid delays and lag in complex applications where UI responsiveness is
  important.
- To improve user interaction, especially when a lot of data changes (search,
  filtering, rendering large lists).
- To ensure smooth animations and transitions between states.

##### How does it work?

The `useDeferredValue` hook takes a value and returns a deferred version of
it:

```jsx
const deferredValue = useDeferredValue(value);
```

- React immediately updates critical (high-priority) changes.
- The deferred value (`deferredValue`) is updated asynchronously after React
  handles more urgent tasks.
- If updates to the main value happen too quickly, React may skip some
  intermediate values and jump straight to the latest one.

##### Example of use:

Imagine a component with a search field and a large list that needs to be
filtered as text is entered.

###### Without `useDeferredValue`:

```jsx
import { useState, useMemo } from 'react';

function SearchList({ items }) {
  const [query, setQuery] = useState('');

  const filteredItems = useMemo(() => {
    return items.filter(item => item.includes(query));
  }, [items, query]);

  return (
    <>
      <input
        value={query}
        onChange={e => setQuery(e.target.value)}
        placeholder="Search..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

This can cause lag if the list is very large, because React recalculates the
filtered results immediately on every keystroke.

###### With `useDeferredValue`:

```jsx
import { useState, useDeferredValue, useMemo } from 'react';

function SearchList({ items }) {
  const [query, setQuery] = useState('');
  const deferredQuery = useDeferredValue(query);

  const filteredItems = useMemo(() => {
    return items.filter(item => item.includes(deferredQuery));
  }, [items, deferredQuery]);

  return (
    <>
      <input
        value={query}
        onChange={e => setQuery(e.target.value)}
        placeholder="Search..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

In this version:

- User input stays immediate and smooth.
- List filtering is performed asynchronously (after the user pauses typing or
  when the rate of changes drops).
- As a result, the interface remains responsive.

##### How it behaves:

- `useDeferredValue` does not set a specific delay time (unlike debounce). It
  lets React automatically determine the update timing depending on UI load.
- The value returned by `useDeferredValue` may "lag behind" the main state,
  which should be taken into account in application logic.

##### Advantages of using it:

- Reduces CPU load during active interactions.
- Provides stable FPS and a smoother UI.
- Makes UX more comfortable and predictable, especially in large and complex
  applications.

##### When is `useDeferredValue` best used?

- Lists with a large number of items.
- Forms with active filtering and autocomplete.
- Any case where frequent UI updates can create an unpleasant user
  experience.

</details>
