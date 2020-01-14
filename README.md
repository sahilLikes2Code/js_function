# Function In JavaScript

The aim of the exercise is to get started with Function
* [ ] Function Decleration
* [ ] Function Expression
    * [ ] Arrow Function
* [ ] Function Invocation
* [ ] IIFE

## Getting Started

**Setup your project by following these instructions:**

* [ ] Make your own copy by forking this exercise.
* [ ] Go to the settings of the newly forked repo and add your mentor as a collaborator on the repo.
* [ ] Make a clone of your forked repo.
* [ ] Create a new branch called develop: `git checkout -b develop`.
* [ ] Work on the exercise on your `develop` branch.
* [ ] Push commits to `develop` branch ONLY. Command - `git push origin develop`.


**After you are done.**

* [ ] Submit a Pull Request to merge `develop` branch into the `master` branch of your repo. **Please don't merge your own pull request.**
* [ ] Add your mentor as a reviewer on the PR.
* [ ] The assigned mentor will review the exercise and pass feedback.
* [ ] Once the mentor merges the PR to `master` branch, you are done with this exercise. Yay!

## Goals 🎯
* [ ] Every folder has a `.md` file and a `.js` file
* [ ] Go through the instruction form `.md` file and complete the function in the `.js` file.

## Basic Info 🛠

###  What is a function
  1. A function is a subprogram designed to perform a particular task.
  2. Functions are executed when they are called. This is known as invoking a function.
  3. Values can be passed into functions and used within the function.
  4. Functions always return a value. In JavaScript, if no return value is specified, the function will return  `undefined`.
  5. Functions are objects.

### Defining a function

A `Function Declaration` defines a named function. To create a function declaration you use the `function` keyword followed by the name of the function. When using function declarations, the function definition is hoisted, thus allowing the function to be used before it is defined.

```js
function add(a, b){
  return a + b;
}
```

A `Function Expressions` defines a named or anonymous function. An anonymous function is a function that has no name. Function Expressions are not hoisted, and therefore cannot be used before they are defined.

```js
let add = function(a, b){
  return a + b;
}
```

An `Arrow Function Expression` is a shorter syntax for writing function expressions. Arrow functions do not create their own this value.

```js
let add = (a, b) => {
  return a + b;
}
```

### Function Terms ⚡️

![@wesbos](./assets/function.jpg)


## Invoking a Function

Functions execute when the function is called. This process is known as invocation. You can invoke a function by referencing the function name, followed by an open and closed parenthesis: `()`

```js
let add = (a, b) => {
  return a + b;
}
add();
```

## Concepts & Resources ℹ️

1. [Functions](http://javascript.info/function-basics)
2. [Function expressions and arrows](http://javascript.info/function-expressions-arrows)