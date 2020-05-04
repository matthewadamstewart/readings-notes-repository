# Readings-Notes-Repository

## Class 09 notes for my Readings in Code Fellows 301 Course

[Back To Main](https://matthewadamstewart.github.io/readings-notes-repository/)


### Reading
[Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

* Complexity can make things harder
* Functional Programing is about using math
* **Pure Function** Returns the same results if given the same parameters and has no sde-effect
* Reading external files or using random generators is impure
* mutability is discouraged in Functional Program
* Pure Functions are stable, reliable, an easier to test
* immutibility means it can't change, so instead you make a copy and change that
* recursion can call itself, and keeps the variables unchanging, while accumilating the result
* First-Class is treating functions like entities which can be passed like a parameter or value
* Like Callbacks which we've been doing in class
* Higher Order Functions are either takes a function as a callback or produces a function as its return
* discusses ```filter()```, ```map()``` and ```reduce()``` methods
* ```filter()``` using a boolean test/logic/conditional statement for assessment and only leaves truthy values in the resulting array
    * [Example](https://gist.githubusercontent.com/leandrotk/bfaf14e35d405b462983e3f81145734b/raw/67525a2503f430634cb471f731815b28bbde6b08/imperative-filter-array.js)
* ```map()``` interates over and transforms the contents into a new array with an annonymous or declared function callback
    * [Example](https://gist.githubusercontent.com/leandrotk/a859f1c4960f9e0dd4ce8745d5c90e72/raw/a1c9161a59d2f048136b8abe203804f821e18827/map_people.js)
* ```reduce()``` receive a function and a collection, and return a value created by combining the items, like for example multiplying all the array's entries together, or summing them together, or any other cumlative operation like that
    * [Example](https://gist.githubusercontent.com/leandrotk/c055cde3461374d83cb9107f01043719/raw/68bf003f7da2bca09686aaab5b02905900d11c65/map_reduce_amount.js)


[Refactoring Javascript for Readability](https://dev.to/healeycodes/refactoring-javascript-for-performance-and-readability-with-examples-1hec)

* Balancing speed and readability is the golden middle ground
* It is important to put code to display errors
* It is important to be careful if you're iterating over an array as a main part of your program as refactoring the data within can cause the functions iterating over it to throw 
* A **Hash function** [Maps and Sets use under the surface](https://v8.dev/blog/hash-code)
* Makes a bold claim
* It is important to think ahead so you can see if a function will become large and future needs for breaking into more modular and avoid redundances
* using a [template literal](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals) allows you to make easier to read code
* **THERE ARE NO ABSOLUTE RULES IN MAKING CLEAN CODE** * disclaimer: Including this one
* But here are some guideline (beware the edge cases)
    * > Cache variables so functions can be read like sentences:
    * > Check for Web APIs before implementing your own functionality
    * > It's important to get your code right 

