# ES6 Basics

This project covers the fundamentals of ECMAScript 6 (ES6), including new features and syntax introduced in ES2015.

## Learning Objectives

- What ES6 is
- New features introduced in ES6
- The difference between a constant and a variable
- Block-scoped variables
- Arrow functions and function parameters default to them
- Rest and spread function parameters
- String templating in ES6
- Object creation and their properties in ES6
- Iterators and for-of loops

## Requirements

- All files will be interpreted/compiled on Ubuntu 20.04 LTS using node 20.x.x and npm 9.x.x
- All files should end with a new line
- Your code should use the `.js` extension
- Your code will be tested using the Jest Testing Framework
- Your code will be analyzed using the linter ESLint
- All of your functions must be exported

## Setup

### Install NodeJS 20.x.x

```bash
curl -sL https://deb.nodesource.com/setup_20.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

### Install Jest, Babel, and ESLint

```bash
npm install
```

## Tasks

0. **0-constants.js** - Use const and let instead of var
1. **1-block-scoped.js** - Block-scoped variables
2. **2-arrow.js** - Arrow functions
3. **3-default-parameter.js** - Parameter defaults
4. **4-rest-parameter.js** - Rest parameter syntax
5. **5-spread-operator.js** - Spread syntax
6. **6-string-interpolation.js** - Template literals
7. **7-getBudgetObject.js** - Object property value shorthand
8. **8-getBudgetCurrentYear.js** - Computed property names
9. **9-getFullBudget.js** - ES6 method properties
10. **10-loops.js** - For...of loops
11. **11-createEmployeesObject.js** - Iterator
12. **12-createReportObject.js** - Create report object

## Usage

Run a file with Babel:
```bash
npm run dev <filename>
```

Run tests:
```bash
npm test
```

Run linter:
```bash
npm run check-lint
```
