# ES6 Data Manipulation

This project focuses on ES6 data manipulation techniques using modern JavaScript features.

## Learning Objectives

- How to use map, filter and reduce on arrays
- Typed arrays
- The Set, Map, and Weak link data structures

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

0. **Basic list of objects** - Create a function that returns an array of student objects
1. **More mapping** - Create a function that returns an array of ids from a list of objects using map
2. **Filter** - Create a function that returns students in a specific city using filter
3. **Reduce** - Create a function that returns the sum of all student ids using reduce
4. **Combine** - Create a function that combines filter and map to update grades by city
5. **Typed Arrays** - Create a function that returns a new ArrayBuffer with an Int8 value
6. **Set data structure** - Create a function that returns a Set from an array
7. **More set data structure** - Create a function that checks if all array elements exist in a set
8. **Clean set** - Create a function that returns a string of set values starting with a specific string
9. **Map data structure** - Create a function that returns a map of groceries
10. **More map data structure** - Create a function that updates map items with quantity 1 to 100
