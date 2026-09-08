<p align="center">
  <a href="https://github.com/lupaxa-developers-toolbox">
    <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/organisations/developers-toolbox/readme-logo.png" alt="Developers Toolbox" />
  </a>
</p>

<h1 align="center">Design Patterns</h1>

Standardised solutions to common software design problems. Each pattern
is a conceptual template — not a concrete implementation — that you can
adapt to the problem and language at hand.

Choosing the right pattern keeps a system flexible, readable, and
maintainable. The wrong one adds complexity. The pages below describe
each pattern and show the same example in Go, Perl, Python, Ruby, and
Rust.

## The Patterns

| Pattern                                                                | Description                                                                                                                                                                            |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Abstract Factory Pattern](patterns/Abstract-Factory.md)               | The abstract factory pattern provides an interface for creating families of related or dependent objects without specifying their concrete classes.                                    |
| [Adapter Pattern](patterns/Adapter.md)                                 | The adapter pattern allows incompatible interfaces to work together by converting the interface of one class into another expected by the client.                                      |
| [Bridge Pattern](patterns/Bridge.md)                                   | The bridge pattern decouples an abstraction from its implementation so that the two can vary independently.                                                                            |
| [Builder Pattern](patterns/Builder.md)                                 | The builder pattern simplifies the construction of complex objects by separating the construction process from the final representation.                                               |
| [Chain of Responsibility Pattern](patterns/Chain-of-Responsibility.md) | The chain of responsibility pattern delegates commands to a chain of processing objects, allowing multiple objects a chance to handle the request.                                     |
| [Command Pattern](patterns/Command.md)                                 | The command pattern encapsulates a request as an object, allowing for parameterization, queuing, logging, and supporting undoable operations.                                          |
| [Composite Pattern](patterns/Composite.md)                             | The composite pattern allows composing objects into tree structures to represent part-whole hierarchies, treating individual objects and compositions uniformly.                       |
| [Decorator Pattern](patterns/Decorator.md)                             | The decorator pattern dynamically adds behaviour to individual objects without affecting the behaviour of other objects from the same class.                                           |
| [Facade Pattern](patterns/Facade.md)                                   | The facade pattern provides a simplified interface to a complex subsystem, making it easier for clients to interact with the system.                                                   |
| [Factory Pattern](patterns/Factory.md)                                 | The factory pattern defines an interface for creating objects but allows subclasses to alter the type of objects that will be created.                                                 |
| [Flyweight Pattern](patterns/Flyweight.md)                             | The flyweight pattern reduces the cost of creating and managing a large number of similar objects by sharing as much data as possible.                                                 |
| [Interpreter Pattern](patterns/Interpreter.md)                         | The interpreter pattern defines a grammatical representation for a language and provides an interpreter to deal with this grammar.                                                     |
| [Iterator Pattern](patterns/Iterator.md)                               | The iterator pattern provides a way to access elements of an aggregate object sequentially without exposing its underlying representation.                                             |
| [Mediator Pattern](patterns/Mediator.md)                               | The mediator pattern defines an object that encapsulates how a set of objects interact, promoting loose coupling.                                                                      |
| [Memento Pattern](patterns/Memento.md)                                 | The memento pattern captures and externalizes an object's internal state without violating encapsulation, so the object can be restored to this state later.                           |
| [Observer Pattern](patterns/Observer.md)                               | The observer pattern defines a one-to-many dependency so that when one object changes state, all its dependents are notified and updated automatically.                                |
| [Prototype Pattern](patterns/Prototype.md)                             | The prototype pattern creates new objects by copying an existing object, known as the prototype.                                                                                       |
| [Proxy Pattern](patterns/Proxy.md)                                     | The proxy pattern provides a surrogate or placeholder for another object to control access to it, enhancing control over the underlying object.                                        |
| [Singleton Pattern](patterns/Singleton.md)                             | The singleton pattern ensures a class has only one instance and provides a global point of access to it, managing shared resources efficiently.                                        |
| [State Pattern](patterns/State.md)                                     | The state pattern allows an object to alter its behaviour when its internal state changes, appearing as if the object changed its class.                                               |
| [Strategy Pattern](patterns/Strategy.md)                               | The strategy pattern defines a family of algorithms, encapsulates each one, and makes them interchangeable, allowing the algorithm to vary independently from the clients that use it. |
| [Template Method Pattern](patterns/Template-Method.md)                 | The template method pattern defines the skeleton of an algorithm, deferring some steps to subclasses.                                                                                  |
| [Visitor Pattern](patterns/Visitor.md)                                 | The visitor pattern separates an algorithm from the objects on which it operates, allowing new operations to be added without modifying the objects.                                   |

<a href="https://github.com/the-lupaxa-project">
  <img src="https://raw.githubusercontent.com/the-lupaxa-project/brand-assets/master/logos/components/footer-for-child-orgs.svg" alt="The Lupaxa Project Footer" width="100%" />
</a>
