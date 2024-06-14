# Conditionals
We make decisions everyday from what to eat, what to do first when we wake up, etc. In order to do this we often ask ourselves simple yes or no questions to make decisions. In order to help computers make decisions, we use **conditional statements** to tell the computer what to do at various points in our program.

**Conditional statements** are programming commands that are used to handle decisions and control program flow. We use the keywords `if` and `else` to define a conditional statement in JavaScript. Conditional statements in JavaScript follow a similar syntax as conditional statements in Java.
```javascript
if (condition) {
  code to run if condition is true
} else {
  run some other code instead
}
```
1. The keyword `if` followed by some parentheses.
2. A condition to test, placed inside the parentheses (typically "is this value bigger than this other value?", or "does this value exist?"). The condition makes use of the [comparison operators](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Math#comparison_operators) we discussed in the last module and returns `true` or `false`.
3. A set of curly braces, inside which we have some code — this can be any code we like, and it only runs if the condition returns `true`.
4. The keyword `else`.
5. Another set of curly braces, inside which we have some more code — this can be any code we like, and it only runs if the condition is not `true` — or in other words, the condition is `false`.

In summary, conditional statements allow us to create a decision-making process in our programs, where different actions can be taken depending on whether a condition is true or false.

Source: [MDN Docs on conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

