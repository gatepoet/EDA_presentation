# Event-Driven Architecture (EDA)

## Agenda
1. Pub/Sub vs RPC and Distributed Systems
2. Clients and Task-Based UIs
3. Server-Side and CQRS
4. Event Sourcing and its relation to EDA
5. Conclusion and Q&A

## Pub/Sub vs RPC and Distributed Systems

Pub/Sub and RPC are two different communication patterns used in distributed systems. 

![Pub/Sub Diagram](https://cloud.google.com/pubsub/architecture)
*Diagram illustrating the Pub/Sub communication pattern.*

![RPC Diagram](https://www.geeksforgeeks.org/what-is-rpc-mechanism-in-distributed-system/)
*Diagram illustrating the RPC communication pattern.*

Distributed systems are systems where components located on networked computers communicate and coordinate their actions by passing messages.

![Distributed Systems Diagram](https://www.researchgate.net/figure/A-simple-architecture-of-a-distributed-system_fig10_287198069)
*Diagram illustrating a distributed system.*

## Clients and Task-Based UIs

Task-based UIs are designed around the tasks that a user needs to perform, not around the data that those tasks manipulate.

![Task-Based UI Diagram](https://codeopinion.com/decomposing-crud-to-a-task-based-ui/)
*Diagram illustrating a task-based UI.*

Uni-directional flow is a concept in which the data flows in a single direction, which makes the application more predictable and easier to understand.

![Uni-directional Flow Diagram](https://coderpad.io/blog/development/master-react-unidirectional-data-flow/)
*Diagram illustrating uni-directional flow.*

## Server-Side and CQRS

Command Query Responsibility Segregation (CQRS) is a pattern that segregates the operations that read data (queries) from the operations that update data (commands) by using separate interfaces.

![CQRS Diagram 1](https://learn.microsoft.com/en-us/azure/architecture/patterns/cqrs)
*Diagram illustrating the CQRS pattern.*

![CQRS Diagram 2](https://www.ibm.com/cloud/architecture/architectures/event-driven-cqrs-pattern/)
*Another diagram illustrating the CQRS pattern.*

## Event Sourcing and its relation to EDA

Event Sourcing is a pattern where state changes are logged as a time-ordered sequence of records.

![Event Sourcing Diagram 1](https://learn.microsoft.com/en-us/azure/architecture/patterns/event-sourcing)
*Diagram illustrating Event Sourcing.*

![Event Sourcing Diagram 2](https://medium.com/design-microservices-architecture-with-patterns/event-sourcing-pattern-in-microservices-architectures-e72bf0fc9274)
*Another diagram illustrating Event Sourcing.*

## Conclusion and Q&A

In conclusion, Event-Driven Architecture (EDA) is a powerful architectural pattern that can provide numerous benefits for distributed systems.

