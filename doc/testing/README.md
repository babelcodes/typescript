# TypeScript - Testing

## Introduction

See https://github.com/babelcodes/testing [`SOON`] for a common presentation of software testing.


## Framework

### Criteria

There is a lot of unit testing frameworks in JavaScript... To help the choice, there is some mandatory features to consider:

- **Watch** mode to ran automated test cases whenever the code change... That feature can be replaced with the `nodemon` library.
- **Partial or focus** mode to be able, used with the previous feature, to automated run only wanted tests when you change the code. It is very useful with using TDD to be run at the beginning only the tests you are creating. But this feature should come with an option to fail if only some tests are focused : that option should be activated in the CI/CD pipelines to prevent any forgetting.
- As I use TDD for developing, no need for an option to report the test coverage.. More over, when you put in place a limit for test coverage, e.g. "At least 80% of test coverage (on the new code)" you often see anti-patterns appear.
- _Mocking_ it is also a must have, but I am one of those who think that an extending use of Mocks it's a bad smell, especially in JavaScript when you can do many things by yourself.
  - [Sinon.JS - Standalone test fakes, spies, stubs and mocks for JavaScript. (sinonjs.org)](https://sinonjs.org/)

### List

- [What Is the Best Unit Testing Framework for JavaScript? (testim.io)](https://www.testim.io/blog/best-unit-testing-framework-for-javascript/)

### Choice: Jest

- [jestjs.io](https://jestjs.io/)
- [Jest Testing: A Helpful Introductory Tutorial - Testim.io](https://www.testim.io/blog/jest-testing-a-helpful-introductory-tutorial/)

## Code

- [TypeScript Unit Testing 101: A Developer's Guide (testim.io)](https://www.testim.io/blog/typescript-unit-testing-101/)

See also
- [Unit Testing in TypeScript | Refraction](https://refraction.dev/blog/unit-testing-in-typescript)
- [Unit testing JavaScript and TypeScript - Visual Studio (Windows) | Microsoft Learn](https://learn.microsoft.com/en-us/visualstudio/javascript/unit-testing-javascript-with-visual-studio?view=vs-2022&tabs=jest)

