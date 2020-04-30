[Home - Table of Contents](index)

## Operators and Loops

### Comparison and Logical Operators

Comparison operators include:

==  equal to

!=  not equal to

=== strictly equal to

!== not strictly equal to

>, <, >=, and <=

Logical operators include: 

&&  and

||  or

!   not

### Loops
Loops test a condition and based on the outcome will run a series of commands zero, one, or more times until the condition changes.

A **for** loop runs code a specific number of times. This code will write 0 to 4 to the console.
```
for (var i=0; i<5, i++) {
    console.log(i);
}
```

A **while** loop checks a condition first, and only runs while that condition is true. It is good if you don't know how many times the code will need to be run before the condition is met.
```
while (i<5) {
    console.log(i);
    i++;
}
```

A **do while** loop always executes the code once. The condition is not checked until after the code has been run once.
```
do {
    console.log(i);
    i++;
} while (i<5);