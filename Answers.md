# Answers

1.  What is React JS and what problems does it try and solve?

    React can be used with other frameworks/libraries such as jquery, Angular, Backbone etc. Any app with state that changes a lot will benefit from React.js. as React solves this by giving the developer a virtual DOM to render to instead of the actual DOM and does the minimum number of DOM operations needed to achieve the new state. This achieves a simpler code base which leads to less bugs.

2.  What does it mean to _think_ in react?

    To think in react is to first imagine how we will proceed with building the app - visualizing your data flow.
    a. Breaking the UI into components
    b. build your static page
    c. represent the UI state
    d. Identify where the state will stay
    e. add inverse data flow

3.  Briefly describe some of the differences between a Class/Stateful component and a Functional/Presentational component.

    Stateful components are always class components. They have a state that gets initialized in the constructor. We can update the state using setState to make the application interactive. Presentation components are coupled with the view or how things look. These components accept props from their container counterpart and render them. Everything that has to do with describing the uI should go here. Presentational components are reusable and receibes the data and callbacks exclusively via props and when an event occurs, like a button being pressed, it performs a callback to the container component via props to invoke an event handling method.

4.  Describe state.

    Like props, state holds information anout the component. By default a component has no state so we have to create a state in the component through the class. THen update or change it's status by setState.

5.  Describe props.

    Properties are immutable, meaning we cannot change them. We simply receive them in our components and use them to display data to the user. When we give a component some attribute-looking data in JSX, React builds out an object that we can consume as a parameter inside of a functional component.