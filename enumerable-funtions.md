Questions

Describe a `map` method.

A. The map method allows us to iterate over each item in an array to transform it and return a new array without modifying the original.

Describe a `filter` method.

A. Allows us to iterate over an array and filters out any items based when the condition is false. It also does not affect the original.

What is the difference between the `map()` and the `filter()` function?

A. `filter` creates a new array with removed items. `map` creates a new array with changed items.

Code Practice

Using the numbers provided in the editor, use `filter()` function to remove any numbers that are less than four then use `reduce()` function to sum the remaining numbers.

```
var numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 2, 3, 4, 5, 6, 1, 2, 3, 4, 5, 6, 7, 8, 8, 4, 3, 2];

var total = numbers
  .filter(item => item > 4)
  .reduce((total, amount) => total + amount);

console.log(total);
```
