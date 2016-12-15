# Software Vocab

## Software Development Lifecycle
* [Software Development Lifecycle (SDLC)](https://en.wikipedia.org/wiki/Systems_development_life_cycle) - The process used to development and maintain software. There are several philosophies and methods that can be used, like Agile or Waterfall.
* [Scope Creep](https://en.wikipedia.org/wiki/Scope_creep) / [Feature Creep](https://en.wikipedia.org/wiki/Feature_creep) - When the initial scope or feature set for a product grows beyond the original intentions
* [Agile](https://en.wikipedia.org/wiki/Agile_software_development) - A philosophy around SDLC that focuses on functionality and release speed over features
* [Scrum](https://en.wikipedia.org/wiki/Scrum_(software_development)) - A methodology that works well with Agile, focusing on speed of development, using constructs like Sprints and stand-up
* [Sprint](https://en.wikipedia.org/wiki/Sprint_(software_development)) - A span of time (usually 1-3 weeks) used as a work unit in Scrum. When planning, sprints are dedicated to one or more features, where the feature is expected to be functional by the end of the sprint.
* [Stand-up](https://en.wikipedia.org/wiki/Stand-up_meeting)) - A short, daily meeting within a development team where members describe yesterday's progress, today's plans, and anything harming their progress. Its purpose is to increase transparency and allow members to help improve others' efficiency and remove blockers.
* Blocker - Anything that gets in the way of normal progress speed. Blockers could manifest as a lack of knowledge, dependency on another team, a long running process, or anything else causing a delay. Good planning identifies blockers early and plans to address them before they harm the timeline.
* [Waterfall](https://en.wikipedia.org/wiki/Waterfall_model) - A work philosophy (including SDLC) that prioritizes prior planning over adaptability. It is useful in settings where changes are costly, like manufacturing, but is generally frowned upon in settings where the cost of changes is low, as in software development. That is not to say that Waterfall is not useful in software, but it often carries a negative connotation.

## Software Theory
* [Variable](https://en.wikipedia.org/wiki/Variable_(computer_science)) - A unit of data referenced by a name. For example, you can declare that there is a variable called "x" that stores the data "5".
* [Subroutine / Function / Method](https://en.wikipedia.org/wiki/Subroutine) - A set of instructions represented by a name that may receive input and may produce output. For example, you could have a function called "add" that takes in two numbers and outputs one number.

### Object Oriented Programming
* [Object Oriented Programming (OOP)](https://en.wikipedia.org/wiki/Object-oriented_programming)) - A programming paradigm where data is represented as objects, making it easier to conceptualize and manipulate information.
* [Object](https://en.wikipedia.org/wiki/Object_(computer_science)) - A unit of data and functionality in OOP. Using the blueprint and building analogy, this is the building.
* [Class](https://en.wikipedia.org/wiki/Class_(computer_programming)) - A template for how an object should behave - what properties it stores and what methods it provides. Using the blueprint and building analogy, this is the blueprint.
* [Instance / Instantiation / Instantiate](https://en.wikipedia.org/wiki/Instance_(computer_science)) - An instance refers to an object. To instantiate an object is to create an object from its class. Instantiation is the act of instantiating an object.
* [Constructor](https://en.wikipedia.org/wiki/Constructor_(object-oriented_programming)) - A method defined on a class that produces an object of that class.
* [Encapsulation](https://en.wikipedia.org/wiki/Object-oriented_programming#Encapsulation)) - The idea that an object has its own copy of information that is distinct from other objects of the same type/class.
* [Inheritance](https://en.wikipedia.org/wiki/Object-oriented_programming#Composition.2C_inheritance.2C_and_delegation)) - The ability for one class to inherit from another allows the inheriting class (child or subclass) to automatically have properties and methods from the inherited class (parent or superclass) defined. Without inheritance, polymorphism is not possible.
* [Composition](https://en.wikipedia.org/wiki/Object-oriented_programming#Composition.2C_inheritance.2C_and_delegation)) - The ability for one object to store another object in order to have access to its properties and methods. For example, a House object may be composed of Wall, Door, and Window objects. The House would then have the ability to "open" by opening the Door it is composed of.
* [Polymorphism](https://en.wikipedia.org/wiki/Polymorphism_(computer_science)) - Subtype polymorphism states that a subclass can be treated as if it were its parent class, since it inherits all properties and methods the parent class has. The idea of polymorphism can also be used to describe overloading.
* [Overloading](https://en.wikipedia.org/wiki/Function_overloading)) - The ability to create methods with the same name but with different return types and/or inputs, usually only applicable in strongly-typed languages.
* [Strong and Weak Typing](https://en.wikipedia.org/wiki/Strong_and_weak_typing)) - Strongly typed languages dictate that variables must be defined to store a certain type of data and that functions must take in and produce specific types of data. Weakly typed languages do not have these constraints.
* [Abstraction](https://en.wikipedia.org/wiki/Abstraction_(software_engineering)) - The idea that implementation details can be ignored for the purpose of ease and development speed. For example, you don't need to know how a coffee brewer works; you only need to know how to use it to brew coffee. Abstraction can also refer to classes that cannot be instantiated as objects.
