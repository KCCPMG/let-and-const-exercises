let and const Exercise
======================

In this exercise, you’ll refactor some ES5 code into ES2015.

ES5 Global Constants
--------------------
```
var PI \= 3.14;
PI \= 42; // stop me from doing this!
```
ES2015 Global Constants
-----------------------
```
/\* Write an ES2015 Version \*/
const PI = 3.14
```

Quiz
----

*   What is the difference between var and let?

-var is function scoped, and let is block scoped, so for example, a var initialized in a for loop would persist after the end of that for loop, whereas a let would not. Using both var and let can allow for reassignment, but var can be redeclared and let cannot. Additionally, var is hoisted whereas let is not.

*   What is the difference between var and const?

-The differences between const and var are the same as the differences between let and var, with the biggest exception to that being that const does not allow for redeclaration *or* reassignment. 

*   What is the difference between let and const?

-Variables declared as const cannot be reassigned, whereas variables declared by let can be.

*   What is hoisting?

-Hoisting is processing code at the beginning, regardless of where it was declared. For the purposes of var, variables declared through var are hoisted so that they are declared as undefined prior to being assigned, so attempts to access them will result in undeclared rather than in a ReferenceError.

Solution
--------

See [Our solution](solution/index.html).