# Principles of Structured Programming

The formation and development of structured programming is associated with the name of Edsger Dijkstra.
* Principle 1: Avoid using the goto operator.
* Principle 2. Any program is built from three basic control structures: sequence, branching, loop.
* Principle 3. In a program, basic control structures can be nested inside each other in any way. There are no other means of controlling the sequence of operations.
* Principle 4. Repeated program fragments can be formatted as subroutines (procedures and functions). In the same way (in the form of subroutines), you can arrange logically integral program fragments, even if they are not repeated.
* Principle 5. Each logically complete group of instructions should be designed as a block. Blocks are the basis of structured programming.
* Principle 6. All listed structures must have one entrance and one exit.
* Principle 7. Program development is carried out step by step, using the top-down method.

Corollaries and additions to the above principles:

1. Prohibition of using global variables
2. No more than one function exit. The exception is the preliminary check of function arguments
3. No more than one exit from the loop - this can be either a condition or the break keyword
4. The nesting of any blocks should not exceed 4
5. The size of functions is limited by lines and is 40-50 lines
