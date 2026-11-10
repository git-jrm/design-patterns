# DESIGN PATTERNS
  
* Design patterns are known solutions to recurring problems in software design in code.
* The patterns is not specific piece of code, but a general concept for solving problem.
* An algorithm is a recipe, whereas a pattern is a blueprint.
* The pattern consist of: intent (problem and solution) + motivation (detailed problem and solution) + structure (components relationships) + code (example).
* The most low-level patterns are _idioms_, the most high-level patterns are _architectural patterns_.

## 💬 INDEX

* **Creational patterns** provide object creation mechanisms to increase flexibility and code reuse.
* **Structural patterns** explain how to assemble objects and classes into larger structures while keeping them flexible and efficient.
* **Behavioral patterns** take care of effective communication and the assignment of responsibilities between objects.

## CREATIONAL PATTERNS

These patterns offer different ways to create objects, making code more flexible and reusable.

| Creational Patterns | Description |
| --- | --- |
| **Singleton** | Ensures a class has only one instance and provides a global point of access to it. |
| **Builder** | Constructs complex objects step by step, avoiding constructors with multiple parameters. |
| **Factory Method** | Provide interface for create objects in a superclass allowing subclasses alter object type. |
| **Abstract Factory** | Produces families of related objects without specifying their concrete classes. |
| **Prototype** | Copies existing objects without making the code dependent on their classes. |

## STRUCTURAL PATTERNS

These patterns assemble objects and classes into larger structures while keeping them flexible.

| Structural Patterns | Description |
| --- | --- |
| **Decorator** | Extends functionality dynamically by wrapping them, avoiding rigid inheritance hierarchies. |
| **Adapter** | Translates incompatible interfaces so objects can work together. |
| **Facade** | Provides a simplified interface to a complex library, framework, or set of classes. |
| **Proxy** | Provides a substitute or placeholder for another object to control access to it. |
| **Composite** | Organizes objects into tree structures to treat single objects and groups uniformly. |
| **Bridge** | Splits a large class or closely related classes into two separate hierarchies (abstraction and implementation). |
| **Flyweight** | Fits more objects into available RAM by sharing common parts of state between multiple objects. |

## BEHAVIORAL PATTERNS

| Creational Patterns | Description |
| --- | --- |
| **Observer** | Defines a subscription mechanism (pub-sub/listener) to notify multiple objects about events. |
| **Strategy** | Encapsulates a family of interchangeable algorithms, eliminating complex `if-else` or `switch` blocks. |
| **Chain of Responsibility** | Passes requests along a chain of handlers until one of them processes it. |
| **Command** | Turns a request into a stand-alone object containing all information about the request. |
| **Iterator** | Traverses elements of a collection without exposing its underlying representation. |
| **Mediator** | Reduces chaotic dependencies between objects by forcing them to communicate only via a mediator object. |
| **Memento** | Saves and restores the previous state of an object without revealing its implementation details. |
| **State** | Lets an object alter its behavior when its internal state changes. |
| **Template Method** | Defines the skeleton of an algorithm in a superclass, letting subclasses override specific steps. |
| **Visitor** | Separates algorithms from the objects on which they operate. |

> **Modern Trend:** Prefer composition over inheritance, and simplify heavy patterns (like Strategy or Command) using first-class functions or closures in modern languages.
