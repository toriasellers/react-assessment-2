### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
framework that lets us handle client and server-side routing in React applications

- What is a single page application?
a website or web application that dynamically rewrites a current web page with new data from the web server

- What are some differences between client side and server side routing?
Unlike server-side routing, client-side routing involves JavaScript handling the routing process internally. In client-side routing, a request to the server is prevented when a user clicks a link, hence no page refresh even when the URL changes

- What are two ways of handling redirects with React Router? When would you use each?
History API and redirect component

- What are two different ways to handle page-not-found user experiences using React Router? 

To implement a 404 page not found in the react application with React Router, use a wildcard path with an asterisk('*') and add it to the very last path of our routes with <PageNotFound/> as the element. 

- How do you grab URL parameters from within a component using React Router?
Using React Router, when you want to create a Route that uses a URL parameter, you do so by including a : in front of the value you pass to Route 's path prop. Finally, to access the value of the URL parameter from inside of the component that is rendered by React Router, you can use React Router's useParams Hook

- What is context in React? When would you use it?
React context provides data to components no matter how deep they are in the components tree. 

- Describe some differences between class-based components and function
  components in React.
  A functional component is just a plain JavaScript pure function that accepts props as an argument and returns a React element(JSX). A class component requires you to extend from React. 

- What are some of the problems that hooks were designed to solve?
React Hooks were added to solve wrapper hell, huge components, and confusing classes among others that developers faced using class components