# ASSESSMENT 4: Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1. What is an instance variable in Ruby? How is it different from other variables?

  Your answer:  an instance variable is created within a class. 

  Researched answer: "An instance variable is a variable that is accessible in any instance method in a particular instance of a class. ... An instance variable has a name beginning with @."



2. What is a block in Ruby?

  Your answer: block is a snippet of code that works together. One way to often find a block is to see what is between 'do' and 'end'.

  Researched answer:
"A block is the same thing as a method, but it does not belong to an object. Blocks are called closures in other programming languages. There are some important points about Blocks in Ruby:

Block can accept arguments and returns a value.
Block does not have their own name.
Block consist of chunks of code.
A block is always invoked with a function or can say passed to a method call.
To call a block within a method with a value, yield statement is used.
Blocks can be called just like methods from inside the method that it is passed to."


3. Ruby has an implicit return. What does that mean?

  Your answer: within a Ruby function, if you do not write 'return', Ruby will automatically return that value for you once the function ends.

  Researched answer:
  "Any statement in Ruby returns the value of the last evaluated expression. A simple example is the getter method. We call a method and expect some value in return."



4. What is object-oriented programming? How is it different than functional programming?

  Your answer: Ruby represents object-oriented programming, meaning that everything inside Ruby is an object. In functional programs, on the other hand, there are functions that are not objects.

  Researched answer:
- "Object-oriented programming (OOP) refers to a type of computer programming (software design) in which programmers define the data type of a data structure, and also the types of operations (functions) that can be applied to the data structure."
- "Functional programming (often abbreviated FP) is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. Functional programming is declarative rather than imperative, and application state flows through pure functions."

5. What is the difference between a class and an object?

  Your answer: a class is a blueprint of an object. It holds keys but not actually values. An object builds up on a class and holds keys and values.

  Researched answer:
"The difference is simple and conceptual. A class is a template for objects. ... An object is a member or an "instance" of a class. An object has a state in which all of its properties have values that you either explicitly define or that are defined by default settings."