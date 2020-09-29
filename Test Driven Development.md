“Test-driven development” refers to a style of programming in which
three activities are tightly interwoven: coding, testing (in the form of
writing unit tests) and design (in the form of refactoring).

It can be succinctly described by the following set of rules:

write a “single” unit test describing an aspect of the program run the
test, which should fail because the program lacks that feature write
“just enough” code, the simplest possible, to make the test pass
“refactor” the code until it conforms to the simplicity criteria repeat,
“accumulating” unit tests over time

## Definition

TDD is based on a simple idea: write a failing test before you write production code itself. However, this “simple” idea takes skill and judgment to do well. 
TDD is really a technique for design. The foundations of TDD are focused on using small tests to design systems from the ground up in an emergent manner, and to rapidly get value while building confidence in the system. A better name for this technique might really be Test-Driven Design. 

## Examples

Smoke and sanity tests check if the software will run even in basic form.
Continuous testing runs in every iteration, such as when we run Maven.
We use regression tests when we add new programming code or alter existing code. We want to be sure that the other code keeps working.
Performance tests measure the time it takes to run the software.
Acceptance tests check if the stakeholders are happy with the software and that they are willing to pay the bill.