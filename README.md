# React higher order component

Demonstration using a higher order component to redirect user if he is not authenticated.


**src/components/require_authentication.js** is the HOC in this example. It wraps **src/components/resources.js** in
**src/index.js**. It adds functionality to the **Resources component** to kick the user back to the index page if he is
not authenticated.
