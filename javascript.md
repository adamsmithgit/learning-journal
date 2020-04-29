[Home - Table of Contents](index)

## Programming with JavaScript

### Scripts
JavaScript makes web pages interactive by manipulating content in the browser.

Access - the content of page

Modify - the content of page

Program - execute instructions on information

React - to events triggered

A script is a series of instructions created to achieve a goal. Scripts are usually interpreted (not explicitly compiled) though there are exceptions, e.g., V8. JavaScript is a scripting language.

Writing a script often begin with defining the goal, breaking it down into parts or tasks, and writing code (steps) to perform those tasks. Flowcharts provide a way to visualize the steps and how information flows.

### Expressions and Operators
An expression evaluates into a single value. E.g., var total = balance + newSales;

Expressions use operators. 

Arithmetic operators include +, - , *, % (modulus) E.g., var leftOverEggs = eggs % 12;

The string operator + joins two strings together E.g., var greeting = salutation + lastName;

### Functions
A function is a set of commands that work together to perform a task.

Functions are reusable.

Some functions require or can take one or more inputs (called parameters).

E.g.,
```
function total(prevBalance, salesToday) {
    return prevBalance + salesToday;
}
```
Expects two arguments to be passed in, values that correspond to the prevBalance and salesToday parameters.

Functions can return a result. To return multiple values, an array can be used.
E.g.,
```
function total(prevBalance, salesToday) {
    return [prevBalance + salesToday, salesToday / prevBalance * 100];
}
```
Returns an array. The first value represents the new bank balance. The second represents the percentage by which the bank balance has increased.