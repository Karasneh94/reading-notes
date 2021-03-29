# Node, Express, and APIs

## Node Is Built on Google Chrome’s V8 JavaScript Engine

The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, and since its an open source
a guy named Ryan Dahl took the source-code and enhanced it with features.

Node is a JavaScript runtime which means it lets us run JavaScript on our machiens.

We can run Javascript files using node on our terminal, lets say we have a JavaScript file called app.js and inside of it there is a `console.log('ahmed')`
when we run `node app.js` on terminal , we should see the word 'ahmed' displayed.

npm is a package manager that is bunduled within node, its the world's largest software registry.

## What Is Node.js Used For?

Node.js is primarily used for non-blocking, event-driven servers, due to its single-threaded nature. It's used for traditional web sites and back-end API services.

Node.js was never created to solve the compute scaling problem. It was created to solve the I/O scaling problem.

Why use Node.js? If your use case does not contain CPU intensive operations nor access any blocking resources, you can exploit the benefits of Node.js and enjoy fast and scalable network applications. Welcome to the real-time web.

### “Hello, World!” — Server Version

`const http = require('http'); http.createServer((request, response) => {response.writeHead(200); response.end('Hello, World!');}).listen(3000);`

consider having this code above inside app.js file, running it using node in terminal will display the message (response) Hello, World inside the localhost port 3000
