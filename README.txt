#Express Crash Course(https://www.youtube.com/watch?v=L72fhGm1tfE)

Node site:https://nodejs.org/en/
Express site: https://expressjs.com/
Postman site: https://www.postman.com/

Code: https://github.com/bradtraversy/express_crash_course

## What is Express?

Express is a fast, unopinionated and minimalist web framework for Node.js.

Express is a "server-side" or "back-end" framework. It is not comparable to client-side frameworks like React, Angular & Vue. It can be used in combination with those frameworks to build full stack applications.(alternatives: https://www.decipherzone.com/blog-detail/top-10-best-backend-frameworks-for-web-development-in-2020)


Why use Express?
-Make building web applications with Node.js MUCH easier
-Used for both server rendered apps as well as API/Microserices
-Extremely light, fast, and free
-full control of request and response
-by far the most popular Node frameworks
-great to use with client side frameworks as it's all JavaScript

What to know first
-JavaScript Fundamentals(Objects, Arrays, Conditionals, etc.)
-Basic Node.js & NPM

May help to learn these first
-HTTP Status Codes
-JSON
-High Order Arrays Methods - forEach, map, filter
-Arrow Functions

Express Middleware

Middleware functions are functions that have access to the request and response object. Express has built in middleware but middleware:

  -Execute any code
  -Make changes to the request/response Objects
  -End response cycle
  -Call next middleware in the stack
