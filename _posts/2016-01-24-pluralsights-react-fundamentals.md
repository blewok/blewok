---
layout: post
title: "Pluralsight's React Fundamentals"
date: 2016-01-24
---

### JSX
Can be client side and server side.

JSX attributes are component props.

`htmlFor` and `className`.

`style={{any:thing}}`.

Unescaped HTML: `dangerouslySetInnerHTML={{__html="blah"}}`

### Components

`React.createClass` + `render` is minimal component.

`getInitialState` - does what it says.

`this.setState()` merges current state with new state.

`this.props` - immutable properties. `propTypes` for validation, use `React.PropTypes`.

`getDefaultProps`

`mixins` to use mixins.

### Forms
`ref` attribute to name element for later values extraction. `this.refs.-ref-name-` for accessing ref.

`getDOMNode().value`.

Form elements in react can be controlled or uncontrolled.

html5 push state to route.
There are multiple routing libraries available for JS.

`console.dir(anything)`
