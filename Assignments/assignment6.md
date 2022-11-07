# Assignment 6

1. Consider the following BNF Grammar

    > Program $\rightarrow$ Block
    Block $\rightarrow$ DeclSeq _begin_ ComSeq _end_
    DeclSeq $\rightarrow$  Decl |  DeclSeq _;_ Decl
    Decl $\rightarrow$ Type Id
    Type $\rightarrow$ _int_ | _bool_ | _char_
    ComSeq $\rightarrow$ Com | ComSeq _;_ Com
    Com $\rightarrow$ Id := Id
    Id $\rightarrow$ _a_|_b_|_c_| ...|_z_

    - Construct an attribute grammar so that no identifier may be declared than once in the declaration part.

1. Study for the exam and solve as many as you can
