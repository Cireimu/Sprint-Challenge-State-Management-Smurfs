1. What problem does the context API help solve?

    Context API helps solve the problem that after a while once your program or project becomes very large scale when we pass state from parents to children it can be very slow or troublesomes. Context API helps solve this problem by storing the data on the context object.

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    Actions contain information that we can then pass to our reducer as an argument.

    Reducers are functions that let us manage state and take two arguments and then return the new state from those arguments.

    The store is a state tree that can't be changed directly, to change the information from the store you have to change copies of the information with actions and reducers.

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

    The difference between Application and Component state is that Application state is immutable where as Component is mutable. It is usually better to use Application state in bigger projects and Component state in smaller scale projects.

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

    Redux-thunk is a middleware for Redux that allows us to perform asynchronous operations with Reducers in Redux. It changes our action-creators to allow us to make API calls from our action-creators.

1. What is your favorite state management system you've learned and this sprint? Please explain why!

    At the moment I still like passing state through props since that's what I'm am most used to, but I can already see the many positives that come from using Redux and have a feeling that once I get the hang of it I won't want to go back.