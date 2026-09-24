# DESIGN PATTERNS

* Design patterns are known solutions to recurring problems in software design in code.
* The patterns is not specific piece of code, but a general concept for solving problem.
* An algorithm is a recipe, whereas a pattern is a blueprint.
* The pattern consist of: intent (problem and solution) + motivation (detailed problem and solution) + structure (components relationships) + code (example).
* The most low-level patterns are _idioms_, the most high-level patterns are _architectural patterns_.

## 💬 INDEX
* **Creational patterns** provide object creation mechanisms to more flexibility and code reuse.
* **Structural patterns** allow assemble objects and classes while keeping flexible and efficient structure.
* **Behavioral patterns** to effective communication and assignment of responsibilities between objects.

# CREATIONAL PATTERNS
These patterns offer different ways to create objects making code more flexibility and reuse current code.
| Creational Patterns | Description |
| --- | --- |
| -Singleton (unique instance) | Ensure only one instance and provide global access of a class |
| -Factory Method | Provide interface for create objects in a superclass allowing subclasses to alter object type |
| -Builder | To complex object with multiparameter |

# STRUCTURAL PATTERNS
| Structural Patterns | Description |
| --- | --- |
| -Decorator: Extiende funcionalidad dinámicamente evitando jerarquías rígidas de herencia. | |
| Adapter: Traduce interfaces incompatibles. | |

# BEHAVIORAL PATTERNS
| Creational Patterns | Description |
| --- | --- |
| -Observer (pub-sub, listener) | Messaging pattern define subs mechanism to notify objects |
| Chain of Responsibility |  |
| Command |  |
| Iterator |  |
| Mediator |  |
| Memento |  |
| State |  |
| -Strategy |  |
| Template Method |  |
| Visitor |  |

--
Strategy: Elimina switch/if-else complejos encapsulando algoritmos intercambiables.
Observer: Eje central de arquitecturas orientadas a eventos y programación reactiva.

*(Tendencia actual: Prefiere composición sobre herencia y simplifica patrones pesados (como Strategy o Command) usando funciones de primera clase o closures en lenguajes modernos.)



