# context_hooks_learning
Following the Net Ninja's React Context & Hooks Tutorial & taking notes.... https://www.youtube.com/watch?v=6RhOzQciVwI&list=PL4cUxeGkcC9hNokByJilPg5g9m2APUePI

Notes:

What is the Context API?
The Context API gives us a way to share state up and down a component tree quiet easily. We can do this without the context API using props, but that gets quite messy, especially when our application/component tree gets bigger. The Context API aims to solve this issue. It's going to do that by giving us an essential place to store data, or state, and then share it between components without having to pass it down as props. It will clean things up a little and make working with shared data much easier.

If you're familiar with Redux, this concept might be familiar... having a central place where data is stored and can be accessed without continually needing to pass down props (several components deep sometimes!). The Context API is a different appoach to this. It is an alternative to Redux. When we use the Context API alongside hooks, it behaves very similar to Redux.

![alt text](context1.png)