Questions

What are the three types of conditional statements?

A. `if` statements, `else` statements, `else if` statements

What are four types of Comparison Operators and how you would use them?

A.
1. Equality operator `==` (Will test if the value is equal).
2. Strict equality operator `===` (Will test both the value and the data type for equality).
3. Inequality operator `!=` (Will test if value is NOT equal)
4. Strict Inequality operator `!==` (Will test both if the value and the data type are NOT equal)

Code Practice

Create a variable called grade and set it to the grade you plan to receive on this assignment. Then write an `if` statement that will check whether the grade is equal to an A, B, C, D, F and inform the user if they passed or failed using `console.log()`

```
let grade = "A";

if (grade === "A") {
console.log("You passed and Aced it." );
}

else if (grade === "B") {
console.log("You passed, Good job.");
}

else if (grade === "C") {
console.log("You passed");
}

else if (grade === "D") {
console.log("You passed, but barely");
}

else {
console.log("You Failed");
}
```
