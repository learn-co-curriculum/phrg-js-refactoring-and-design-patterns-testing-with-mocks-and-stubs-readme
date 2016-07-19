# Mocks and Stubs

## Objectives

1. Define a stub
2. Define a mock
3. Explain when to use mocks and stubs
4. Explain when you might want to avoid mocks and stubs

## Outline

We can start by relating stubs to spies — they're identical, except stubs replace functionality (where spies just wrap it).

We can talk about all of this with reference to [Sinon.js](http://sinonjs.org/), if that's helpful.

Then we can move onto mocks, and explain how they're basically stubs that test related functionality — they're like mocking an entire class.

Finally, we want to encourage students to test their implementations as closely as possible. This means relying on pure functions that don't need to be stubbed or mocked, and using stubs and mocks as sparingly as possible.

## Resources

- [Best Practices for Spies, Stubs, and Mocks in Sinon.js](https://semaphoreci.com/community/tutorials/best-practices-for-spies-stubs-and-mocks-in-sinon-js)
