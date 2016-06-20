JavaScript Closures Lab
---

## Objectives

1. Practice using closures in an application setting
2. Practice returning functions that close over "private" variables
3. Use a closure to define a partially applied function

## Introduction

- Include a brief review of the previous lesson (https://github.com/learn-co-curriculum/javascript-closures)
- Be sure to spend some time talking about partially applied functions
- These things can be hard/weird to test — we're sort of violating a lot of testing principles by testing implementation instead of behavior, which can go against an experienced programmer's intuition
- It might be worth setting up contrived examples for the first few practice problems
  - A simple curried example:

  ```javascript
  function adder(x) {
    return function(y) {
      return x + y
    }
  }

  var add5 = adder(5)
  add5(4) // 9
  ```

- Remember to push `master` and `solution` branches separately

## Resources

- [Curried JavaScript functions](http://javascript.crockford.com/www_svendtofte_com/code/curried_javascript/)
