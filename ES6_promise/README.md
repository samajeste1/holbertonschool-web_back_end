# ES6 Promises

This project focuses on ES6 Promises and asynchronous JavaScript programming.

## Learning Objectives

- Promises (how, why, and what)
- How to use the `then`, `resolve`, `catch` methods
- How to use every method of the Promise object
- Throw / Try
- The await operator
- How to use an async function

## Requirements

- All files will be interpreted/compiled on Ubuntu 20.04 LTS using node 20.x.x and npm 9.x.x
- All files should end with a new line
- Your code should use the js extension
- Your code will be tested using Jest and the command `npm run test`
- Your code will be verified against lint using ESLint
- Your code needs to pass all the tests and lint
- All functions must be exported

## Setup

Install NodeJS 20.x.x:

```bash
curl -sL https://deb.nodesource.com/setup_20.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

Install dependencies:

```bash
npm install
```

## Tasks

0. **Keep every promise you make** - Return a Promise using getResponseFromAPI()
1. **Don't make a promise...if you know you can't keep it** - Return a promise based on a boolean parameter
2. **Catch me if you can!** - Append handlers to a promise with then and catch
3. **Handle multiple successful promises** - Use Promise.all to resolve multiple promises collectively
4. **Simple promise** - Return a resolved promise with an object containing firstName and lastName
5. **Reject the promises** - Return a Promise rejecting with an Error
6. **Handle multiple promises** - Use Promise.allSettled to handle multiple promises
7. **Load balancer** - Use Promise.race to return the value from the first resolved promise
8. **Throw an error** - Throw an error when denominator is 0
9. **Throw error / try catch** - Use try/catch to create a guardrail function
