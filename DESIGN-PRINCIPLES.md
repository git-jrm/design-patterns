[⬅️Home](./README.md)

# 🧭 DESIGN PRINCIPLES

**High Cohesion & Low Coupling:** Group related functionality closely together (high cohesion) while keeping dependencies between separate modules loose and independent (low coupling).

## 📏 General Principles

- **KISS (Keep It Simple, Stupid):** Prefer the simplest design that solves the problem. Simple code is easier to debug and trust than clever solutions.
- **DRY (Don’t Repeat Yourself):** Every piece of logic should have a single representation in the code to prevent bugs from changes.
- **YAGNI (You Aren’t Gonna Need It):** Build only what your current requirements demand. Avoid adding speculative features for "future flexibility" you do not yet need.
- **Separation of Concerns:** Divide a system into distinct sections (such as UI, business logic, and data access) so each part can be understood, developed, and tested independently.
- **Law of Demeter:** A module should only talk to its immediate "friends" or dependencies, reducing deep object-chaining and tightly coupled code.

## 🧱 SOLID

### 1️⃣ Single Responsibility Principle (SRP)
There should never be more than one reason for a class to change. In other words, every class should have only one responsibility.

### 2️⃣ Open–Closed Principle (OCP)
Software entities should be open for extension, but closed for modification.

### 3️⃣ Liskov Substitution Principle (LSP)
Functions that use pointers or references to base classes must be able to use pointers or references of derived classes without knowing it.

### 4️⃣ Interface Segregation Principle (ISP)
Clients should not be forced to depend upon interface methods that they do not use.

### 5️⃣ Dependency Inversion Principle (DIP)
One should depend upon abstractions, not concretes.

[⬅️Home](./README.md)

