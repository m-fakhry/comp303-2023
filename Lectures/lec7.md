# Lecture 7

**Topics we covered**

- translational semantics

    - translate from source language to target language
      - Examples:
        - from English to Frensh
        - from C++ to assembly
        - etc.
    - define the target machine language
      - LOAD, STO, ADD, SUB, MULT, DVD, AND, OR, NOT, TSTGT, TSTLT, TSTGE, TSTLE, TSTEQ, TSTNE, J, JF, LABEL
    - Examples
      - $x = 2 + y$
      - $x = 2 + y * z $
      - $x = 2 * y + 3 * z $
      - if $(x>2*y)$ {$z=2+3$}
      - if $(x>2*y)$ {$z=2+3$} else {$z=3*5$}

    - the general translation of if-else statement
      ```
      if (cond)
        {statement1}
      else
        {statement2}
      statement3
      ```
      the translation should follow the following steps
      1. code of the `condition`
      1. `JF L2`
      1. code for `statement1`
      1. `J L1`
      1. `L2 LABEL`
      1. code for `statement2`
      1. `L1 LABEL`
      1. code for `statement3`
