# React-ContextApiDemo
Demo App for UseContext() aka Context API <br/>

a way of storing the data and make it available to components without having it pass it through props
- we can avoid props-drilling, passing data from components to components
- components which are just mediators passing components between main component and then sub-child components


- We will create a context, store the user in the context and wrap dashboard and Sidebar and Nav bar inside that context everything wrapped under <DashboardContext.provider>
    

- we created a dashboard context, now we need a provider to this context, so we use a provider to assign the user to this context and then a receiver where we want to use the value of the user, and to do that we use useContext, a react hook

- useUserContext is used to use the value of the User from inside the DashboardContext.
