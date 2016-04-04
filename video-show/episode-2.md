## Question

> Do you hate classical inheritance only when it comes to JS, or also C++,? I want to start learning C++ to delve into VR.

A: In some languages, class is much harder to avoid than in JS, but in any language, favor object composition over class inheritance.

## Question

> Do you recommend class or createClass in React?

A. Try pure components & react-stamp.

* [pure components](https://github.com/ericelliott/react-pure-component-starter) for most things
* [react-stamp](https://github.com/stampit-org/react-stamp) for components that need lifecycle methods

## Question

> I am passing props from parent to pure component, can I do something like "shouldComponentUpdate" because I don't want it to re-render. Or do I have to do that somehow in the parent component?

A: `react-redux` `connect()` does it for you.

* [react-redux](https://github.com/reactjs/react-redux)
