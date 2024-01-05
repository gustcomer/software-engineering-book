## First steps in software design

When you design software systems, remember that the domain of the software is important. Good design is all about finding good models for that domain, or
simply put, finding good *domain models*.

The model is an organized and selective abstraction of the knowledge in the domain expert's head, and its representation and communication is usually split
up into 3 artifacts:

- English sentences spoken or written
- Diagrams
- Written code

## Crunching Knowledge

As a software developer, contrary to a domain expert, the first step before designing a system would be to try and find a domain model, and for this purpose, we need to go by the inverse path, that is, get in the domain expert's head by trying to think in the problem in terms of their jargon, write some diagrams and possibly write some code. This process is known as *crunching knowledge*.

We have to keep in mind that the model will drive de design of the system. And
this will be done with the help of a paradigm, which in our case will be OOP.

## Summary of the step-by-step Design method

1. Experiment with some ***Knowledge Crunching***.
  - Think freely about the system and write down some of the entity names and their relationships, trying to establish some internal dialog as the PCB dialog example
  - Write down some diagrams
  - Try to write some pseudocode and choose some methods names
2. These are some diagrams (artifacts) that can be delivered in this stage
  - Associations Class diagram (kinda a UML but simplified without attributes or methods, just associations)
  - Objects and method calls diagram
  - Simplified Class diagrams for Entities and Value Objects without the methods, just attributes and relationships