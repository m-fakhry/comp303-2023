# Lecture 6

**Topics we covered**

- we reviewed more examples on synthesized and inherited attributes
  - continue on the example to make sure that the assignment statment satisfies the rules:
    - all variables used are being defined
    - the left-hand and right-hand sides are of the same type

  - another example is to compute the value of a binary number

    $number \rightarrow number$ $bit$  &nbsp; $|$ &nbsp; $bit$

    $bit \rightarrow 0$ &nbsp; $|$ &nbsp; $1$

    - add attributes to compute the value of the number. The issue is that we need a counter starts with zero to know the number of bits to the right. We need to add one additional rule to set such counter.
    
    $S \rightarrow number$
