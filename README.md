# Overview
This repository is template used to create Express APIs with TypeScript.

# Features
## Server Configuration
Properly defined and type checked server config that can be configured using
[nconf](https://www.npmjs.com/package/nconf) in TypeScript or via environment variables.

## Powerful logger
A powerful logger based on [bunyan](https://www.npmjs.com/package/bunyan) that is customizable using the server config.

## Endpoint Not Found controller
This server includes a controller that catches every request made to unknown endpoints and returns a custom 404
response message.

## Ping controller
Simple controller used to ping the server.

## Internal Server Error middleware
A middleware that catches errors thrown in the controllers and returns a custom 500 error response message.

## Log middleware
A middleware that logs incoming requests.

## Parameter validator middleware
A middleware that validates incoming requests params using custom defined validators and
[express-validator](https://www.npmjs.com/package/express-validator).

## Async Wrapper
A wrapper function that can be used to wrap async controller handlers in order to properly catch errors thrown in them.

## Tests
Integration tests that run on your real app using [supertest](https://www.npmjs.com/package/supertest).
