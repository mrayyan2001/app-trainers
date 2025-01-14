# Front End Roadmap

## HTML

HTML, or Hypertext Markup Language, is the foundation of web development
used for structuring web pages. It defines the structure and content of web
documents through elements like headings, paragraphs, links, images, and lists.

### Essential Concepts

- Basic Tags: `<html>`, `<head>`, `<body>`, `<title>`
- Text Formatting: `<h1>` to `<h6>`, `<p>`, `<br>`, `<hr>`, `<strong>`, `<em>`
- Lists: `<ul>`, `<ol>`, `<li>`
- Links: `<a>`, href, target
- Images: `<img>`, src, alt, width, height
- Tables: `<table>`, `<tr>`, `<td>`, `<th>`, colspan, rowspan
- Forms: `<form>`, `<input>`, `<textarea>`, `<button>`, `<select>`, `<option>`, `<label>`
- Semantic Elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Meta Tags: `<meta>`, charset, name, content, viewport
- Multimedia: `<audio>`, `<video>`, controls, `<source>`

## CSS

CSS, or Cascading Style Sheets, is used to style and layout web pages. It allows
you to control the visual presentation of HTML elements, including colors, fonts,
spacing, and positioning, creating responsive designs that adapt to various screen
sizes.

### Essential Concepts

- Selectors: element, class, id, attribute, pseudo-class, pseudo-element
- Box Model: margin, border, padding, content
- Positioning: static, relative, absolute, fixed, sticky
- Display: block, inline, inline-block, none, flex, grid
- Flexbox: justify-content, align-items, flex-direction, flex-wrap
- Grid: grid-template-columns, grid-template-rows, gap, grid-area
- Typography: font-family, font-size, font-weight, line-height, text-align, text decoration
- Colors: color, background-color, opacity, rgba, hex, hsl
- Units: px, em, rem, %, vh, vw
- Transitions and Animations: transition, transform, animation
- Responsive Design: media queries, @media, max-width, min-width

## JavaScript

JavaScript is a programming language that adds interactivity and dynamic
behavior to web pages. It handles tasks like user interactions, form validation,
animations, and fetching data from servers, making web pages more engaging
and functional.

Essential Concepts

- Variables: declarations (var, let, const), scope (block, functional, global), hoisting
- Data Types: primitive types (strings, number, boolean, undefined, null,
  Symbol), Object, typeof operator
- Type Casting: explicit casting, implicit casting, type conversion vs coercion
- Operators: assignment, comparison, arithmetic, bitwise, logical, conditional
- Equality Comparisons: ==, ===, Object.is
- Control Flow: if, else, switch
- Loops: for, for…in, for…of, while, do...while, break, continue
- Functions: function declaration, function expression, arrow functions, parameters, return values
- Arrays: creation, methods (push, pop, shift, unshift, map, filter, reduce)
- Objects: creation, properties, methods, this keyword
- Classes
- Data Structures: Map, WeakMap, Set, WeakSet, JSON
- Error Handling: try, catch, finally, throw, Error objects
- Asynchronous JavaScript: Promises, async/await, callbacks, callback hell
- DOM Manipulation: document.getElementById, document.querySelector, addEventListener, innerHTML, style
- Events: click, submit, load, change, focus, blur, event propagation (bubbling and capturing)
- Working with APIs: fetch
- Browser Storage: local storage, web storage
- Modules: CommonJS, ECMAScript Modules

## Git

Git is a version control system that tracks changes in code, allowing multiple
developers to collaborate efficiently. It helps manage and maintain different
versions of code, facilitates branching and merging, and stores the project history.

### Essential Concepts

- Setup and Configuration: init, clone, config
- Staging: status, add, rm, mv, commit, reset
- Inspect and Compare: log, diff, show
- Branching: branch, checkout, merge
- Remote Repositories: remote, fetch, pull, push
- Temporary Commits: stash
- GitHub: fork, pull request, code review

## TypeScript

TypeScript is a superset of JavaScript that adds static typing and other features,
making code more robust and maintainable. It helps catch errors early during
development and is widely used in large-scale applications.

### Essential Concepts

- Basics Types: string, number, boolean, array, tuple, enum, any, void, null, undefined, never, unknown
- Type Assertion: as keyword, <> syntax
- Interfaces: defining, extending, optional properties, readonly properties, dynamic keys
- Classes: properties, methods, constructors, inheritance, access modifiers (public, private, protected)
- Functions: type annotations, optional and default parameters, rest parameters
- Generics: generic functions, generic classes
- Modules: import, export, namespaces
- Utility types: Partial, Pick, Omit, Readonly, Record, Exclude, etc

## Frameworks React, Angular, Vue

### React

React is a popular JavaScript library for building user interfaces, particularly
single-page applications. It allows developers to create reusable UI components,
manage application state efficiently, and handle dynamic data changes.

#### Essential Concepts

- Basics: components, props, state, JSX
- Rendering: conditional rendering, rendering lists
- Hooks: useState, useEffect, useReducer, useRef, custom hooks
- Styling: using vanilla CSS, CSS modules, CSS-in-JS
- Forms: react-hook-forms, zod
- Data Fetching: fetch API, axios
- State Management: lifting state up, Context API, React Query, Redux
- Routing: React Router

### Angular

### Vue

## SASS

SASS (Syntactically Awesome Stylesheets) is a CSS preprocessor that extends
CSS with features like variables, nested rules, and mixins. It simplifies writing and
managing CSS for large projects, improving efficiency and maintainability.

### Essential Concepts

- Variables: defining, using, scope
- Loops: for loops, each loops, while loops
- Nesting: rules, selectors
- Mixins: creating, including, parameters, default values
- Inheritance: @extend
- Functions: built-in functions, custom functions
- Feature checks: feature-exists
- Other features: conditionals, lists, maps, interpolation

## Tailwind CSS

Tailwind is a utility-first CSS framework that provides a set of predefined classes
for rapid UI development. It enables developers to build custom designs directly in
the HTML by applying utility classes, ensuring consistency and speed.

### Essential Concepts

- Utility-first CSS principles, benefits
- Configuration: tailwind.config.js, customizing themes
- Applying Styles: utility classes for layout, flexbox, grid, sizing, spacing, borders, typography, colors, backgrounds, transitions, animations, transforms
- Responsive Design: responsive utilities, breakpoints
- Plugins: adding and configuring plugins

## Automated Testing

Jest and Vitest are testing frameworks for JavaScript applications that enable
developers to write tests for their code. They help ensure code reliability and
correctness by automating the testing process, identifying bugs, and verifying
functionality.

### Essential Concepts

- Basics: setting up, writing test cases
- Matchers: common matchers (toBe, toEqual, toContain, toBeTruthy, toBeFalsy, toBeNull, toBeUndefined, toBeDefined, toMatch, toMatchObject, toHaveProperty, toHaveLength)
- Mocks: mocking functions, modules, timers
- Testing Asynchronous Code: async/await, promises
- Code Coverage: collecting and reporting coverage
- Testing React Components with React Testing Library: queries (get, query, find), matchers (toBeChecked, toBeDisabled, toBeInTheDocument, toHaveAttribute, toHaveTextContent), firing events with user-event
- Mocking APIs with Mock Service Worker MSW

## Next.js

Next.js is a meta framework built on top of React, enhancing its capabilities with
features like server-side rendering SSR and static site generation SSG. It
simplifies building and optimizing modern web applications with improved
performance and SEO.

### Essential Concepts

- Basics: client and server components, client and server rendering, static and dynamic rendering, static generation SSG
- Styling: global styles, CSS modules, Tailwind
- Routing: pages, layouts, dynamic routes, linking and navigation, error handling, loading UI and streaming
- Data Fetching: fetch API, caching
- Building APIs: route handlers
- Database Integration: Prisma
- Authentication: NextAuth.js
- Optimizations: image optimization, lazy loading, automatic code splitting

## React Native

React Native is a framework for building cross-platform mobile applications using
React. It allows developers to write code once and deploy it to both iOS and
Android platforms, leveraging native components for a seamless user experience.

### Essential Concepts

- Basics: View, Text, Image, Touchables, Button, Alert, platform-specific code
- Layouts: dimensions, detecting orientation, Flexbox, absolute and relative
- Styling: StyleSheet, borders, shadows, padding, styling text, icons, platformspecific styles
- Input Components: TextInput, Switch, Picker, custom pickers
- Navigation: React Navigation, stack navigator, tab navigator, drawer navigator
- Native Modules: linking native code, using third-party libraries
- Offline Support: detecting network status, caching, AsyncStorage
- Authentication: auth providers
- Notifications: push notification services
- Distribution: optimizing assets, building, error reporting, environment management
