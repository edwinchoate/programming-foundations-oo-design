# Notes

## Ch. 1 Object-Oriented Fundamentals

* The biggest advantage of OO is code reusability - you can mix and match objects you've already create when new scenarios come up. 
* We use small simple examples to learn in the classroom but the real value of OO is once your codebase grows in scale. 

* Objects
    * Identity (ex: a particular instance)
    * Attributes - what are its properties?
        * Attributes that don't change
        * Attributes that change
    * Behaviors - what can it do?

> Objects are _self-contained_. They have their own identities, separate from other objects. 

Tangible objects (ex: Coffee mug) make for obvious objects. But more abstract, intangible things (ex: EventManager) aren't do intuitive. 

Rule of thumb: Is it a noun?

* Nouns don't have to be physical things
* Could you put "the" in front of it? The mug, the bank account, the event

Think of a class as a template of an object (metaphor: cookie cutter)

* Class
    * Name - what is it? (Aka type)
    * Attributes (Aka properties, data)
    * Behaviors (Aka operations, methods)

Methods vs. Functions - methods are functions that are part of a class

_Abstraction_ - Ignoring specific, detailed characteristics and choose to only focus on the essential qualities of an idea.

> What _should_ an object look like, for this application, under these circumstances, at this time? Focus on just the essentials.

It might be true that every person has a height, but if my application doesn't care about that, I don't need that to be part of my class. 

_Encapsulation_ - walling of the contents of a class from the code outside of it, in order to protect it and prevent corrupted data/logic.

> An object should make aspects of itself available only when it is absolutely necessary 

Benefit: by walling off implementation details, you can alter the implementation without having the change the rest of the application. 

Encapsulation is about reducing dependencies. Encapsulate as much as possible. 

_Inheritance_ - allowing some new class to receive the attributes and methods of an existing class. Benefit: code reuse.

_Dynamic Polymorphism_ - (Aka Runtime Polymorphism) Uses method overriding, acceping different types of objects that share the same method signatures at runtime. (You can do this with inheritance, interfaces, or abstract base classes)

_Static Polymorphism_ - Uses method overloading to achieve different behaviors given different inputs 

OO Analysis, OO Design, OO Programming

1. Analysis - understand the problem. What's the problem you're trying to solve? 
2. Design - plan your solution. How are you going to solve this problem? 
3. Programming - build your solution. Solving the problem.

Approach 

1. Requirements gathering
2. Define
3. Identify objects
4. Describing the interactions between objects 
5. Diagram 

**Unified Modeling Language (UML)** 

<img src="./Ch01/class-diagram.jpg"> 

