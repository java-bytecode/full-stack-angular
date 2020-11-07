# Java Full Stack 

## Node & NPM

`npm init`: Creates a package with dependencies.

`npm install`: Install dependencies from **package.json**.

`npm -v`: Node Package Manager Version.

### Flags

`-g`: installs the package globally. It makes the package available to all the node projects by installing to a system directory. Using this flag, doesn't list the dependency in **package.json**.

## System Architecture

|   Frontend  |  AngularJS |
|:-----------:|:----------:|
|   Backend   | SpringBoot |
| Data Source |  Database  |

## Javascript & Typescript

`Typescript` = `Javascript` + `Type Safety`

**ECMA Script**: ECMAScript is Standard. Javascript is the implementation of ECMA Script.

**Modern Javascript**: >=Implementation of ES6 or ES2015.

**Javascript**
```
var x = 10
x = "qwerty"
console.log(x)
```

**Typescript**

```
var x: number = 10
x = 2
x = "qwerty" // Invalid
console.log(x)
```

## Angular CLI

Angular CLI helps with 

* Creating Angular projects.

* Unit Testing.

* Integration Testing.

* Code Quality Checks.

```
npm install -g @angular/cli

# To install a specific version
npm install -g @angular/cli@7.0.3

# To check version of ng
ng version
```

## Web Services

HTML is not really a format for application to application interaction.