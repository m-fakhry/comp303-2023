# Assignment 4

---

The assignment is due next week and you need to submit it before the lecture starts.

1. Solve Exercises 1 and 10 in Section 3.1 (pages 71-73).

1. Consider the following grammar:

    $T \rightarrow V$ &nbsp; $|$ &nbsp; $T$ -> $T$ &nbsp; $|$ &nbsp; $T *T $

    $V \rightarrow \alpha | \beta | \gamma $

    - Show that this grammar is ambiguous
    - Modify the grammar to an unambiguous grammar by enforcing the following properties:
      - -> is right associative
      - $*$ is left associative
      - $*$ has higher priority than ->

---

The following exercises are for your own, you do not need to submit them.


1. Write a CFG that generates the language: $L = \lbrace (ac)^n (b^m d)^n; n \ge 1 ; m \ge 0\rbrace$.

1. Consider the following grammar:

      $G \rightarrow B$

      $B \rightarrow num ⊕ B$ &nbsp; $|$ &nbsp; $num$

      $B \rightarrow B @ A$ &nbsp; $|$ &nbsp; $A$


      which of the following statements is true?
      1. $⊕$ and $@$ have the same precedence
      2. $@$ has higher precedence than $⊕$
      3. none of the above
