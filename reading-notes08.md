##Reading 08

Operators and Loops
Surprise Jscript has a lot of types of expressions and operators
1. Assignment
2. Comparison
3. Arithmetic
4. Bitwise
5. Logical
6. String
7. Conditional (ternary)
8. Comma ?!?!
9. Unary
10. Relational
11. This seems like review…..

Loops: a way to get a program to do something a set (or infinite…) number of times. Ex

``for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}
Lots of different kinds of loops:
1.for statement
2.Do…while statement
3.While
4.Labeled
5.Break
6.Continue
7.For…in
8.For…of
The for loop runs until it hits false: handy!

##While loop-like for, but runs till evaluates ‘true’

Ex
while (condition)
  statement
Susceptible to the ol’ infinite loop problem: avoid. Looks like 

// Infinite loops are bad!
while (true) {
  console.log('Hello, world!');
}
// Infinite loops are bad!
while (true) {
  console.log('Hello, world!');
}

[Back](README.md)