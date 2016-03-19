## Question #1

> Help me understand promises, please.

Miguel, that's not a question!


> Do you recommend class or createClass in React?

* [pure components](https://github.com/ericelliott/react-pure-component-starter) for most things
* [react-stamp](https://github.com/stampit-org/react-stamp) for components that need lifecycle methods

## Question #2

> I am passing props from parent to pure component, can I do something like "shouldComponentUpdate" because I don't want it to re-render. Or do I have to do that somehow in the parent component?

A: `react-redux` `connect()` does it for you.

* [react-redux](https://github.com/reactjs/react-redux)
