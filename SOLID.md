
# SOLID Principles

    These are five principles of Object Oriented class design. They are set of rules and best practices that needs to be followed while creating classes.

    - Single Responsibility Principle
    - Open-Closed Principle
    - Liskov Substitution Principle
    - Interface Segregation Principle
    - Dependency Inversion Principle

### Single Responsibility Principle

A class should do one thing and therefore should only have a single reason to change.
Cohesion and coupling are two terms associated with this principle.
Cohesion means the degree to which various software components are related.
Coupling means the level of inter dependency between components.

Higher cohesion and loose coupling are desired qualities.

### Open-Closed Principle

A class should be closed for modification, but open for extension. Always strive to not modify existing code, if any addtional functionality is required leverage inheritance to extend the class.

### Liskov Substitution Principle

This principle states that subclasses should be substituable for base class. This means that, given that class B is a subclass of class A, we should be able to pass an object of class B to any method that expects an object of class A and the method should not give any weird output in that case.


### Interface Segregation Principle

Segregation means keeping things separated, and the Interface Segregation Principle is about separating the interfaces. No clients should be forced to use the methods that it does not use.

This principle promotes splitting of interfaces as required so that concrete class can implement methods that it requires.

### Dependency Inversion

The Dependency Inversion principle states that our classes should depend upon interfaces or abstract classes instead of concrete classes and functions.


