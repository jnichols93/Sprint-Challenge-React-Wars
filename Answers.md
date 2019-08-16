# Answers

1. What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.
React is a library used for building User Interfaces, primarily for single page react applications! The prpose for which react was built was to streamline the Ui building process aswell address search engine failures by allowing react to register to the DOM and output everything as opposed to java script just bashing throught the wall like the proverbial cool aid man and causing a whole bunch of problems.
1. What does it mean to think in react?
its like the eye of the tiger but completely different. Thinking in react is a simple way of saying planning in react when you're building something breaking it into different pieces. thinking abou things like what components might need to be created.
1. Describe state.
Like props, state holds information about the component. However, the kind of information and how it is handled is different. By default, a component has no state.When a component needs to keep track of information between renderings the component then needs state.So we create state in th comonent through class and updateor change its status by setState.
1. Describe props.
Props is how data is sent down the component hierarchy and how children component can access to the state and other data.
1. What are side effects, and how do you sync effects in a React component to state or prop changes?
side effects can include but are not limited too, anything that affects something outside of the scope of the function being executed (api fetching, timers,logging,and dom interaction) in order to sync effect youd simply use an effect hook!