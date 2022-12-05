# Lecture 8

**Topics we covered**

- we studied how to use attribute grammar to translate into the machine language

  - for the grammar to generate a simple if statement
    ```
    if (cond) {statement1}
    ```
  - write the attribute grammar correponsing to this statement

  - emphasize that we need to use labels in the if statement and we need to make sure all other statement would use different labels.

  - we need to have two attributes for generating labels, one inherited and the other one synthesized.

  - the inherited labels counter takes its value from the synthesized attributes at one of the production rules. 
