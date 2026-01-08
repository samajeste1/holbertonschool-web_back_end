# Node.js Basic

This project covers the fundamentals of Node.js including file operations, HTTP servers, and Express.js.

## Learning Objectives

- Run JavaScript using Node.js
- Use Node.js modules
- Use specific Node.js modules to read files
- Use process to access command line arguments and the environment
- Create a small HTTP server using Node.js
- Create a small HTTP server using Express.js
- Create advanced routes with Express.js
- Use ES6 with Node.js using Babel-node
- Use Nodemon to develop faster

## Requirements

- All files will be interpreted/compiled on Ubuntu 20.04 LTS using node 20.x.x and npm 9.x.x
- All files should end with a new line
- Your code should use the .js extension
- Your code will be tested using Jest and the command `npm run test`
- Your code will be verified against lint using ESLint
- Your code needs to pass all the tests and lint
- All functions/classes must be exported

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

### 0. Executing basic JavaScript with Node.js
Create a function `displayMessage` that prints in STDOUT the string argument.

### 1. Using Process stdin
Create a program that displays a welcome message and accepts user input from stdin.

### 2. Reading a file synchronously with Node.js
Create a function `countStudents` that reads a database file synchronously.

### 3. Reading a file asynchronously with Node.js
Create a function `countStudents` that reads a database file asynchronously using Promises.

### 4. Create a small HTTP server using Node's HTTP module
Create a small HTTP server using the `http` module that displays "Hello Holberton School!".

### 5. Create a more complex HTTP server using Node's HTTP module
Create an HTTP server that handles multiple routes and reads from a database file.

### 6. Create a small HTTP server using Express
Create a small HTTP server using Express that displays "Hello Holberton School!".

### 7. Create a more complex HTTP server using Express
Create an Express server that handles multiple routes and reads from a database file.

### 8. Organize a complex HTTP server using Express
Create a full server with organized structure using controllers, routes, and utilities.

#### Structure:
```
full_server/
├── controllers/
│   ├── AppController.js
│   └── StudentsController.js
├── routes/
│   └── index.js
├── utils.js
└── server.js
```

## Running the servers

### Simple HTTP server (task 4):
```bash
node 4-http.js
```

### HTTP server with database (task 5):
```bash
node 5-http.js database.csv
```

### Express server (task 6):
```bash
node 6-http_express.js
```

### Express server with database (task 7):
```bash
node 7-http_express.js database.csv
```

### Full server (task 8):
```bash
npm run dev
```

## Testing

Run tests:
```bash
npm test
```

Run linter:
```bash
npm run lint
```

Run full test suite:
```bash
npm run full-test
```
