# EDA_presentation

## Introduction

**Slide 1: Title slide - "Event Driven Architecture: Building Reactive Systems with C# and Angular"**

Text: Event Driven Architecture: Building Reactive Systems with C# and Angular

Presenter comment: Welcome everyone and introduce yourself. Explain the goal of the presentation.

**Slide 2: Agenda - list the main sections of the presentation**

Text: Agenda

- Pub/Sub vs RPC and Distributed Systems
- Clients and Task-Based UIs
- Server-Side and CQRS
- Event Sourcing and its relation to EDA
- Conclusion and Q&A

Presenter comment: Briefly overview the agenda and explain what will be covered in each section.

## Pub/Sub vs RPC and Distributed Systems

**Slide 3: Definition and comparison of Pub/Sub and RPC**

Text: Pub/Sub:

- Asynchronous messaging pattern
- Publishers send messages to channels
- Decoupled communication

RPC:

- Synchronous communication pattern
- Client makes a request and waits for a response
- Tightly coupled communication

Presenter comment: Explain the differences between Pub/Sub and RPC and provide a brief overview of each pattern.

**Slide 4: Benefits and drawbacks of each approach**

Text: Pub/Sub:

- Scalable
- Decoupled
- Asynchronous
- Complex to manage and debug

RPC:

- Simple and straightforward
- Tightly coupled
- Not easily scalable

Presenter comment: Discuss the benefits and drawbacks of each pattern and when to use them.

**Slide 5: Overview of distributed systems**

Text: Distributed Systems

- Components located on different machines
- Communicate and coordinate actions by passing messages

Presenter comment: Introduce distributed systems and explain their importance in modern software architectures.

## Clients and Task-Based UIs

**Slide 6: Introduction to task-based UIs**

Text: Task-Based UIs

- Focus on user tasks, not system features
- Improve usability and user experience

Presenter comment: Explain the concept of task-based UIs and their benefits.

**Slide 7: Uni-directional flow in task-based UIs**

Text: Uni-directional flow

- Data flows in a single direction
- Makes state management more predictable
- Used in Angular with RxJS observables

Presenter comment: Introduce the concept of uni-directional flow and explain its importance in task-based UIs.

**Slide 8: Applying uni-directional flow to client-side and server-side events**

Text: Client-side and server-side events

- Use Angular services to communicate with C# backend
- Leverage SignalR for real-time updates

Presenter comment: Discuss how uni-directional flow can be applied to both client-side and server-side events.

**Slide 9: Example of a task-based UI in a real-world application**

Text: Real-world example

- Task-based UI with Angular and TypeScript

Presenter comment: Show a real-world example of a task-based UI using Angular and TypeScript.

## Server-Side and CQRS

**Slide 10: Introduction to CQRS**

Text: CQRS (Command Query Responsibility Segregation)

- Separates read and write operations
- Improves scalability and maintainability

Presenter comment: Introduce CQRS and explain its purpose and benefits.

**Slide 11: Benefits and drawbacks of CQRS**

Text: Benefits of CQRS:

- Scalability
- Maintainability
- Flexibility

Drawbacks of CQRS:

- Increased complexity
- Eventual consistency

Presenter comment: Discuss the benefits and drawbacks of CQRS and when it makes sense to use it.

**Slide 12: When to use CQRS**

Text: When to use CQRS

- Complex domains
- High-performance requirements
- Separate read and write models

Presenter comment: Explain the scenarios where implementing CQRS is most beneficial.

**Slide 13: Example of CQRS implementation in a real-world application using C#**

Text: Real-world example

- CQRS implementation with C# and .NET Core

Presenter comment: Show a real-world example of a CQRS implementation using C# and .NET Core.

## Event Sourcing and its relation to EDA

**Slide 14: Introduction to Event Sourcing**

Text: Event Sourcing

- Store and retrieve application state as a sequence of events
- Full audit log, ability to replay events, and improved debugging

Presenter comment: Introduce Event Sourcing and explain its purpose and benefits.

**Slide 15: Benefits and drawbacks of Event Sourcing**

Text: Benefits of Event Sourcing:

- Full audit log
- Replay events
- Improved debugging

Drawbacks of Event Sourcing:

- Increased complexity
- Event versioning
- Storage considerations

Presenter comment: Discuss the benefits and drawbacks of Event Sourcing and when it makes sense to use it.

**Slide 16: How Event Sourcing relates to and differs from EDA**

Text: Event Sourcing and EDA

- EDA focuses on system design and communication
- Event Sourcing focuses on how state is stored and retrieved
- Both can be used together for highly reactive and scalable systems

Presenter comment: Explain the relationship between Event Sourcing and EDA, and how they can complement each other.

**Slide 17: Example of Event Sourcing implementation in a real-world application using C# and Angular**

Text: Real-world example

- Event Sourcing with C# backend and Angular frontend

Presenter comment: Show a real-world example of an Event Sourcing implementation using C# and Angular.

## Conclusion and Q&A

**Slide 18: Summary of key points from the presentation**

Text: Summary

- Differences between Pub/Sub and RPC
- Task-based UIs with Angular and uni-directional flow
- CQRS and Event Sourcing in C# backend applications
- How EDA relates to and complements Event Sourcing

Presenter comment: Recap the main points covered in the presentation and emphasize the importance of each.

**Slide 19: Q&A and contact information**

Text: Q&A

Contact info: [Kristoffer Rolf Deinoff](mailto:kristoffer.deinoff@glasspaper.no), [LinkedIn](www.linkedin.com/deicon)

Presenter comment: Encourage the audience to ask questions and provide your contact information for follow-up discussions.
