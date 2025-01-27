# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug involving loose equality (`==`) and the handling of `null` and `undefined` values.

## Problem

JavaScript's loose equality operator (`==`) performs type coercion before comparison, which can lead to unexpected results.  This is particularly problematic when dealing with `null` and `undefined`.

The `bug.js` file contains code that illustrates this issue.  Incorrect comparisons may produce incorrect logic.

## Solution

The recommended approach is to always use the strict equality operator (`===`).  `bugSolution.js` demonstrates how to refactor the code to use strict equality and handle `null` and `undefined` values appropriately.

## How to Run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a JavaScript environment (browser's developer console, Node.js, etc.).
3. Run the code and compare the outputs to observe the difference in behavior between loose and strict equality.
