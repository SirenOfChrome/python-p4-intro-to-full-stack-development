# Intro to Full-Stack Development

## Learning Goals

- Use React and Flask together to build beautiful and powerful web applications.
- Organize client and server code so that it is easy to understand and maintain.
- Create websocket connections between clients and servers to improve our
  applications' performance.

***

## Key Vocab

- **Full-Stack Development**: development of a frontend and a backend for an
  application. True full-stack development includes a database, a logic/server
  layer, and a frontend built in JavaScript, HTML, and CSS.
- **Backend**: the layer of a full-stack application that handles business logic
  and other programmatic tasks that users do not or should not see. Can be
  written in many languages, including Python, Java, Ruby, PHP, and more.
- **Frontend**: the layer of a full-stack application that users see and
  interact with. It is always written in the frontend languages: JavaScript,
  HTML, and CSS. (_There are others now, but they are based on these three._)
- **Cross-Origin Resource Sharing (CORS)**: a method for a server to indicate
  any ports (or other identifiers) for servers that can share its resources.
- **Transmission Control Protocol (TCP)**: a protocol that defines how computers
  send data to each other. A connection is formed and stars active until the
  applications on either end have finished sending data to one another.
- **Hypertext Transfer Protocol (HTTP)**: a stateless protocol where
  applications communicate for the length of time that it takes for data to be
  transferred.
- **Websocket**: a protocol that allows clients and servers to communicate with
  one another in both directions. The bidirectional nature of websocket
  communication allows a connected state to be generated and the connection
  maintained until it is terminated by one side. This allows for speedy and
  seamless connections between frontends and backends.

***

## Introduction

Up to this point, we have only built JavaScript applications and Python
applications (sometimes with SQL). There are many real-world use cases for these
types of applications- many websites don't need to interact with a backend, and
many CLIs and APIs don't need to be particularly pretty to get the job done.
That being said, the biggest applications from the biggest companies- Meta,
Amazon, Apple, Netflix, and Google to name a few- need to maintain an appealing
frontend and a powerful backend to continue to compete with each other and the
thousands of new companies that pop up every year. The development of a cohesive
frontend and backend, or **full-stack development**, is important to create
high-performance applications that people want to use.

Now that we're nearing the end of the software engineering curriculum, it's time
for us to start putting everything together. You know how to write basic code in
JavaScript and how to use it to build frontend applications with React. You know
how to write basic code in Python and SQL and how to use them to build APIs with
Flask. Putting React and Flask together will allow you to build almost any
application you can imagine! (_With a little extra research._)

In this module, you will:

- Explore the code from previous Flask-React labs.
- Build a React frontend in parallel with a Flask backend.
- Learn about different protocols for communication over the internet.

Happy coding!

***

## Resources

- [What is full stack development? - GeeksforGeeks](https://www.geeksforgeeks.org/what-is-full-stack-development/)
- [Flask - Pallets](https://flask.palletsprojects.com/en/2.2.x/)
- [Getting Started - React](https://reactjs.org/docs/getting-started.html)
- [Introduction - Socket.IO](https://socket.io/docs/v4/)
