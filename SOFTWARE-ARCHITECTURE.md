# SOFTWARE ARCHITECTURE

Software architecture defines the high-level structure of a system, its main components, how they interact, and the key decisions that ensure quality attributes like scalability and maintainability.

## Architectural Patterns

Common high-level ways to organize an application or system.

| Pattern | Description |
| :--- | :--- |
| **Monolithic** | Builds the entire application as a single, unified unit. Simple to develop and deploy at first, but hard to scale independently. |
| **Layered (N-Tier)** | Separates code into horizontal layers (such as Presentation, Business Logic, and Data Access) with clear responsibilities. |
| **Microservices** | Splits the system into small, independent services that communicate over a network and can be deployed separately. |
| **Event-Driven** | Components communicate asynchronously by producing and reacting to events, enabling high decoupling and scalability. |
| **Serverless** | Runs code in stateless, event-triggered functions (FaaS) managed by a cloud provider without handling server infrastructure. |
| **Hexagonal (Ports & Adapters)** | Isolates core business logic from external tools (databases, UI, APIs) using interfaces (ports) and implementations (adapters). |

## Key Architectural Principles

Core guidelines to keep system structures flexible and resilient.

- **Separation of Concerns:** Keep distinct system responsibilities isolated so changes in one area do not break others.
- **Loose Coupling:** Minimize direct dependencies between services or modules so they can evolve independently.
- **Stateless Design:** Avoid storing user session data inside application servers so any instance can handle any request.
- **Design for Failure:** Assume components and networks will fail; use retries, timeouts, and circuit breakers to prevent cascading crashes.

## Distributed Systems Trade-offs

Key decisions when scaling systems across multiple servers or regions.

| Concept | Description |
| :--- | :--- |
| **Horizontal vs. Vertical Scaling** | **Horizontal** adds more machines to share the load; **Vertical** adds more CPU/RAM to a single machine. |
| **CAP Theorem** | A distributed data store can only guarantee two of three properties during a network failure: **Consistency**, **Availability**, or **Partition Tolerance**. |
| **Sync vs. Async Communication** | **Sync** (REST, gRPC) waits for an immediate response; **Async** (Queues, Pub/Sub) sends a message and continues without waiting. |
| **Caching** | Stores frequently accessed data in fast memory (such as Redis) to reduce database load and lower latency. |

## Documentation & Diagrams

Standard tools to communicate architectural decisions clearly.

- **C4 Model:** Visualizes software architecture across four zoom levels: **Context**, **Containers**, **Components**, and **Code**.
- **ADRs (Architecture Decision Records):** Short text files that document an important technical choice, its context, and its trade-offs.
