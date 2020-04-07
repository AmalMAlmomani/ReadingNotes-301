# Functional Programming Concepts
  - *Complexity is anything that makes software hard to understand or to modify.*

  - What is functional programming?
    -  programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 
  - **pure functions:**
    - It returns the same result if given the same arguments (it is also referred as deterministic).
    - It does not cause any observable side effects

  - When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.
  - `pure functions + immutable data = referential transparency`
  - Functions as first-class entities can:
     - 1. refer to it from constants and variables
     - 2. pass it as a parameter to other functions
     - 3. return it as result from other functions

  - The **map method** transforms a collection by applying a function to all of its elements and building a new collection from the returned values.

# Refactoring Javascript for Readability