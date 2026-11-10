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

# CREATIONAL PATTERNS

These patterns offer different ways to create objects, making code more flexible and reusable.

| Creational Patterns | Description |
| --- | --- |
| **Singleton** | Ensures a class has only one instance and provides a global point of access to it. |
| **Builder** | Constructs complex objects step by step, avoiding constructors with multiple parameters. |
| **Factory Method** | Provide interface for create objects in a superclass allowing subclasses alter object type. |
| **Abstract Factory** | Produces families of related objects without specifying their concrete classes. |
| **Prototype** | Copies existing objects without making the code dependent on their classes. |


# STRUCTURAL PATTERNS

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


# BEHAVIORAL PATTERNS

| Creational Patterns | Description |
| --- | --- |
| -Observer (pub-sub, listener) | Messaging pattern define pub-subs mechanism to notify objects |
| -Strategy | Allows create a group of different algorithms in interchangeable classes |
| Chain of Responsibility |  |
| Command |  |
| Iterator |  |
| Mediator |  |
| Memento |  |
| State |  |
| Template Method |  |
| Visitor |  |

--
Strategy: Elimina switch/if-else complejos encapsulando algoritmos intercambiables.

Observer: Eje central de arquitecturas orientadas a eventos y programación reactiva.

*(Tendencia actual: Prefiere composición sobre herencia y simplifica patrones pesados (como Strategy o Command) usando funciones de primera clase o closures en lenguajes modernos.).



