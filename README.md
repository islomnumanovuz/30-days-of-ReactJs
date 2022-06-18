## DAY - 1 JavaScript Refresher

- [JavaScript Refresher](#javascript-refresher)
  - [0. Adding JavaScript to a Web Page](#0-adding-javascript-to-a-web-page)
    - [Inline Script](#inline-script)
    - [Internal Script](#internal-script)
    - [External Script](#external-script)
    - [Multiple External Scripts](#multiple-external-scripts)
  - [1. Variables](#1-variables)
  - [2. Data types](#2-data-types)
  - [3. Arrays](#3-arrays)
    - [How to create an empty array](#how-to-create-an-empty-array)
    - [How to create an array with values](#how-to-create-an-array-with-values)
    - [Creating an array using split](#creating-an-array-using-split)
    - [Accessing array items using index](#accessing-array-items-using-index)
    - [Modifying array element](#modifying-array-element)
    - [Methods to manipulate array](#methods-to-manipulate-array)
      - [Array Constructor](#array-constructor)
      - [Creating static values with fill](#creating-static-values-with-fill)
      - [Concatenating array using concat](#concatenating-array-using-concat)
      - [Getting array length](#getting-array-length)
      - [Getting index of an element in an array](#getting-index-of-an-element-in-an-array)
      - [Getting last index of an element in array](#getting-last-index-of-an-element-in-array)
      - [Checking array](#checking-array)
      - [Converting array to string](#converting-array-to-string)
      - [Joining array elements](#joining-array-elements)
      - [Slice array elements](#slice-array-elements)
      - [Splice method in array](#splice-method-in-array)
      - [Adding item to an array using push](#adding-item-to-an-array-using-push)
      - [Removing the end element using pop](#removing-the-end-element-using-pop)
      - [Removing an element from the beginning](#removing-an-element-from-the-beginning)
      - [Add an element from the beginning](#add-an-element-from-the-beginning)
      - [Reversing array order](#reversing-array-order)
      - [Sorting elements in array](#sorting-elements-in-array)
    - [Array of arrays](#array-of-arrays)
  - [💻 Exercise](#-exercise)
      - [Exercise: Level 1](#exercise-level-1)
      - [Exercise: Level 2](#exercise-level-2)
      - [Exercise: Level 3](#exercise-level-3)
  - [4. Conditionals](#4-conditionals)
    - [If](#if)
    - [If Else](#if-else)
    - [If Else if Else](#if-else-if-else)
    - [Switch](#switch)
    - [Ternary Operators](#ternary-operators)
  - [💻 Exercises](#-exercises)
      - [Exercises: Level 1](#exercises-level-1)
      - [Exercises: Level 2](#exercises-level-2)
      - [Exercises: Level 3](#exercises-level-3)
  - [5. Loops](#5-loops)
    - [Types of Loops](#types-of-loops)
      - [1. for](#1-for)
      - [2. while](#2-while)
      - [3. do while](#3-do-while)
      - [4. for of](#4-for-of)
      - [5. forEach](#5-foreach)
      - [6. for in](#6-for-in)
    - [Interrupting a loop and skipping an item](#interrupting-a-loop-and-skipping-an-item)
      - [break](#break)
      - [continue](#continue)
    - [Conclusions](#conclusions)
  - [6. Scope](#6-scope)
    - [Window Scope](#window-scope)
    - [Global scope](#global-scope)
    - [Local scope](#local-scope)
  - [7. Object](#7-object)
    - [Creating an empty object](#creating-an-empty-object)
    - [Creating an objecting with values](#creating-an-objecting-with-values)
    - [Getting values from an object](#getting-values-from-an-object)
    - [Creating object methods](#creating-object-methods)
    - [Setting new key for an object](#setting-new-key-for-an-object)
    - [Object Methods](#object-methods)
      - [Getting object keys using Object.keys()](#getting-object-keys-using-objectkeys)
      - [Getting object values using Object.values()](#getting-object-values-using-objectvalues)
      - [Getting object keys and values using Object.entries()](#getting-object-keys-and-values-using-objectentries)
      - [Checking properties using hasOwnProperty()](#checking-properties-using-hasownproperty)
  - [💻 Exercises](#-exercises-1)
      - [Exercises: Level 1](#exercises-level-1-1)
      - [Exercises: Level 2](#exercises-level-2-1)
      - [Exercises: Level 3](#exercises-level-3-1)
  - [8. Functions](#8-functions)
    - [Function Declaration](#function-declaration)
    - [Function without a parameter and return](#function-without-a-parameter-and-return)
    - [Function returning value](#function-returning-value)
    - [Function with a parameter](#function-with-a-parameter)
    - [Function with two parameters](#function-with-two-parameters)
    - [Function with many parameters](#function-with-many-parameters)
    - [Function with unlimited number of parameters](#function-with-unlimited-number-of-parameters)
      - [Unlimited number of parameters in regular function](#unlimited-number-of-parameters-in-regular-function)
      - [Unlimited number of parameters in arrow function](#unlimited-number-of-parameters-in-arrow-function)
    - [Anonymous Function](#anonymous-function)
    - [Expression Function](#expression-function)
    - [Self Invoking Functions](#self-invoking-functions)
    - [Arrow Function](#arrow-function)
    - [Function with default parameters](#function-with-default-parameters)
    - [Function declaration versus Arrow function](#function-declaration-versus-arrow-function)
  - [💻 Exercises](#-exercises-2)
      - [Exercises: Level 1](#exercises-level-1-2)
      - [Exercises: Level 2](#exercises-level-2-2)
      - [Exercises: Level 3](#exercises-level-3-2)
  - [9. Higher Order Function](#9-higher-order-function)
    - [Callback](#callback)
    - [Returning function](#returning-function)
    - [setting time](#setting-time)
      - [setInterval](#setinterval)
      - [setTimeout](#settimeout)
  - [10. Destructuring and Spreading](#10-destructuring-and-spreading)
    - [What is Destructuring?](#what-is-destructuring)
    - [What can we destructure?](#what-can-we-destructure)
      - [1. Destructuring arrays](#1-destructuring-arrays)
      - [2. Destructuring objects](#2-destructuring-objects)
    - [Exercises](#exercises)
    - [Spread or Rest Operator](#spread-or-rest-operator)
      - [Spread operator to get the rest of array elements](#spread-operator-to-get-the-rest-of-array-elements)
      - [Spread operator to copy array](#spread-operator-to-copy-array)
      - [Spread operator to copy object](#spread-operator-to-copy-object)
      - [Spread operator with arrow function](#spread-operator-with-arrow-function)
  - [11. Functional Programming](#11-functional-programming)
    - [1. forEach](#1-foreach)
    - [2. map](#2-map)
    - [3. filter](#3-filter)
    - [4. reduce](#4-reduce)
    - [5. find](#5-find)
    - [6. findIndex](#6-findindex)
    - [7. some](#7-some)
    - [8. every](#8-every)
    - [Exercises](#exercises-1)
  - [12. Classes](#12-classes)
    - [Defining a classes](#defining-a-classes)
    - [Class Instantiation](#class-instantiation)
    - [Class Constructor](#class-constructor)
    - [Default values with constructor](#default-values-with-constructor)
    - [Class methods](#class-methods)
    - [Properties with initial value](#properties-with-initial-value)
    - [getter](#getter)
    - [setter](#setter)
    - [Static method](#static-method)
    - [Inheritance](#inheritance)
    - [Overriding methods](#overriding-methods)
    - [Exercises](#exercises-2)
      - [Exercises Level 1](#exercises-level-1-3)
      - [Exercises Level 2](#exercises-level-2-3)
      - [Exercises Level 3](#exercises-level-3-3)
  - [13 Document Object Model(DOM)](#13-document-object-modeldom)