# DESIGN PRINCIPLES

## General Principles

- KISS (Keep It Simple Sir): Prefer the simplest design that solves the problem. Simple code is easier to debug and trust than other clever solutions.
- DRY (Don’t Repeat Yourself): Every piece of logic should have a single representation in the code to prevent bugs from changes.
- YAGNI (You Aren’t Gonna Need It): Build only what your current requirements demand. Avoid adding speculative features for "future flexibility" you do not yet need.
- Separation of Concerns: Divide a system into distinct sections (such as UI, business logic, and data access) so each part can be understood, developed, and tested independently.
- Law of Demeter: A module should only talk to its immediate "friends" or dependencies, reducing deep object-chaining and tightly coupled code.

## SOLID

### Single responsibility principle
The single-responsibility principle (SRP) states that there should never be more than one reason for a class to change.[6] In other words, every class should have only one responsibility.[7]

### Open–closed principle
The open–closed principle (OCP) states that software entities should be open for extension, but closed for modification.[8]

## Liskov substitution principle
The Liskov substitution principle (LSP) states that functions that use pointers or references to base classes must be able to use pointers or references of derived classes without knowing it.[9]

## Interface segregation principle
The interface segregation principle (ISP) states that clients should not be forced to depend upon interface methods that they do not use.[10][4]

## Dependency inversion principle
The dependency inversion principle (DIP) states that one should depend upon abstractions, not concretes.[11][4]

