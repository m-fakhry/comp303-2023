# Lecture 5

**Logistics**

- We agreed to have the midterm exam on November 13.
- Reemphasize that recording of the lecture is prohibited

**Topics we covered**

- Attribute grammars
  - synthesized attributes
  - inherited attributes
  - same attributes could be inherited and synthesized
  - examples
    - compute the value of a decimal number, we also showed the difference between using left and right recursive grammar and how that affects the attributes being used
    $S \rightarrow digit$ $S$ &nbsp; $|$ &nbsp; $digit$
    versus
    $S \rightarrow S$ $digit$ &nbsp; $|$ &nbsp; $digit$

    - another example was provided to write a CFG for declaration and assignment statements in C++. The grammar was used to show how to write an attribute grammar to validate that any variable used in the assignment statement should be defined.
