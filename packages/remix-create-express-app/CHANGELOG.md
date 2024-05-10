# CHANGELOG

## v0.3.7

- 🐛 Handle data requests with search params [#14]

## v0.3.6

- ✨ Add new ServerContext API

## v0.3.5

- ✨ Add redirect support from middleware

## v0.3.4

- 🔨 Make createExpressApp args optional

## v0.3.3

- 🔨 Middleware function must return a response or throw
- 🐛 Add `params` object to middleware function call [#7]
- 🐛 Ignore headers that start with `:` from http2 [#10]

## v0.3.2

- 🐛 Fix import of production build on Windows [#9]
- ✨ Create default app similar to Remix App Server if no configure provided
- ✨ Pass the Remix ServerBuild to the getLoadContext function

## v0.3.1

- 🐛 Fix package build: "Cannot find module" ESM is hard! [#4]

## v0.3.0

- ✨ Add Remix Middleware support

## v0.2.0

- 🚨 Breaking Change: split package into two separate packages
- ✨ Add support for custom servers and express module
- ✨ Add support for custom request handlers

## v0.1.1

- 🐛 Cannot find build/server/remix.js [#1]

## v0.1.0

- 🎉 Initial commit
