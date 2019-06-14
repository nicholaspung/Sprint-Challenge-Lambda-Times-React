## Self-Study/Essay Questions

- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

    PropTypes are used to validate the props passed down from component to component. It's important to type check our data in Javascript because of how "free" Javascript is using primitives. Since Javascript will do its best to coerce primitives to being used, and that it won't return an error when the wrong type is used, PropTypes is useful to make sure our data is being passed down in it's correct type, making it less likely there will be an error in production, since PropTypes will catch any incorrect data type.

- [ ] Describe a life-cycle event in React?

    A life-cycle in React are simple set phases in a component's life. There's a birth/mounting, growth/updating, and death/unmounting phase. The birth/mounting phase is when the component is being built up, where the initial state is set, render method is invoked, and componentDidMount gets called as well. The growth/updating phase is where setState can be called to change a component's state data, forcing a re-render and shouldComponentUpdate can be used here to stop a component from calling a render. The death/unmounting phase is where the component is removed from screen and componentWillUnmount is called to clean up anything else.

- [ ] Explain the details of a Higher Order Component?

    A higher order component is used as advanced react patterns for designing some components that share some kind of behavior or data in a way that makes them connected differently than the traditional state -> props pattern. It allows us the capability of reusing component logic. Which is to say a higher order component is a function that receives a component as an argument and returns a new component.

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

    External CSS file: greater control of how elements are rendered
    Inline CSS: able to configure specific elements in that specific instance
    Styled Components (CSS in JS): have one environment to code HTML, CSS, and JS. 