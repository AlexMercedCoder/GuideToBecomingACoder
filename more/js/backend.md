# Backend Javascript

Backend code is the code that doesn't run in the browser but on a web server and is responsible for handling requests to the server and connecting to databases. NodeJS is a Javascript runtime that allows Javascript to run serverside. There are several backend framework in the Node Ecosystem.

- Express
- Koa
- Sails
- NestJS
- FoalTS
- Fastify
- Polka
- Loopback
- Apollo
- SocketIO
- Merver

## Important Backend Concepts

### MVC

Models - Views - Controllers

- Models: How your applications structures and accesses data (databases)
- Views: The visual sent to the users browser (Server-Side Templates vs Client-Side SPA)
- Controllers: How your web server responds to requests (routes and controller functions)

### Authentication

Two Main Types

Session: Usually used with Server-Side rendered sites, a cookie is used to keep track of a "Session" and data can be stored on the server in memory or in the database made available by the cookie.

JWT (JSON Web Token): Authentication is encoded in a token which is decoded on every request to verify Authorization. This enables the same token to be used between multiple micro-services in todays world of micro-service architecture.

