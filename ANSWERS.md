## Self-Study/Essay Questions

- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

    PropTypes are used to validate the props passed down from component to component. It's important to type check our data in Javascript because of how "free" Javascript is using primitives. Since Javascript will do its best to coerce primitives to being used, and that it won't return an error when the wrong type is used, PropTypes is useful to make sure our data is being passed down in it's correct type, making it less likely there will be an error in production, since PropTypes will catch any incorrect data type.

- [ ] Describe a life-cycle event in React?
- [ ] Explain the details of a Higher Order Component?
- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

    External CSS file: 
    Inline CSS:
    Styled Components (CSS in JS):