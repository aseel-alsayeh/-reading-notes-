### Concepts of Functional Programming in Javascript


- What is functional programming?
 a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable.

- What is a pure function and how do we know if something is a pure function?
1. It returns the same result if given the same arguments (it is also referred as `deterministic`)
2. It does not cause any observable side effects

- What are the benefits of a pure function?
The code’s definitely easier to test. We don’t need to mock anything.

- What is immutability?
Unchanging over time or unable to be changed.
When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

- What is Referential transparency?
pure functions + immutable data = referential transparency