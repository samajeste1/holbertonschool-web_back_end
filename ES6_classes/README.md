# ES6 Classes

This project covers ES6 classes, inheritance, getters/setters, static methods, and metaprogramming with symbols.

## Learning Objectives

- How to define a Class
- How to add methods to a class
- Why and how to add a static method to a class
- How to extend a class from another
- Metaprogramming and symbols

## Requirements

- All files will be interpreted/compiled on Ubuntu 20.04 LTS using node 20.x.x and npm 9.x.x
- All files should end with a new line
- Your code should use the `.js` extension
- Your code will be tested using Jest and the command `npm run test`
- Your code will be verified against lint using ESLint
- Your code needs to pass all the tests and lint

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

0. **0-classroom.js** - ClassRoom class with maxStudentsSize attribute
1. **1-make_classrooms.js** - Function that returns an array of 3 ClassRoom objects
2. **2-hbtn_course.js** - HolbertonCourse class with getters/setters and type verification
3. **3-currency.js** - Currency class with displayFullCurrency method
4. **4-pricing.js** - Pricing class with static convertPrice method
5. **5-building.js** - Abstract Building class
6. **6-sky_high.js** - SkyHighBuilding class that extends Building
7. **7-airport.js** - Airport class with custom toString
8. **8-hbtn_class.js** - HolbertonClass with Number/String casting
9. **9-hoisting.js** - Fixed code with hoisting issues
10. **10-car.js** - Car class with cloneCar method using symbols

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

Run full test (lint + tests):
```bash
npm run full-test
```
