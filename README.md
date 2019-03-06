# General-Topics

# Advantages of GraphQL:

### GraphQL is declarative: 
   Query responses are decided by the client rather than the server. A GraphQL query returns exactly what a client asks for and no more.

### GraphQL is compositional: 
   A GraphQL query itself is a hierarchical set of fields. The query is shaped just like the data it returns. It is a natural way for product engineers to describe data requirements.

### GraphQL is strongly-typed: 
  A GraphQL query can be ensured to be valid within a GraphQL type system at development time allowing the server to make guarantees about the response. This makes it easier to build high-quality client tools

# What is the Software Design Patterns?
   Design pattern is a general reusable solution or template to a commonly occurring problem in software design. The patterns typically show relationships and interactions between classes or objects. The idea is to speed up the development process by providing tested, proven development paradigm.
### Note:
   Design patterns give us a proven solution to existing and recurring problems.(coding design)
   
## Goal:
   • Understand the problem and matching it with some pattern.
   • Reusage of old interface or making the present design reusable for the future usage.

### Example:
   For example, in many real world situations we want to create only one instance of a class. For example, there can be only one active president of country at a time regardless of personal identity. This pattern is called Singleton pattern. Other software examples could be a single DB connection shared by multiple objects as creating a separate DB connection for every object may be costly. Similarly, there can be a single configuration manager or error manager in an application that handles all problems instead of creating multiple managers.

## Types of Design Patterns
   There are mainly three types of design patterns:
### 1. Creational
   These design patterns are all about class instantiation or object creation. These patterns can be further categorized into Class-creational patterns and object-creational patterns. While class-creation patterns use inheritance effectively in the instantiation process, object-creation patterns use delegation effectively to get the job done.

   Creational design patterns are Factory Method, Abstract Factory, Builder, Singleton, Object Pool and Prototype.

### 2. Structural
   These design patterns are about organizing different classes and objects to form larger structures and provide new functionality.

   Structural design patterns are Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Private Class Data and Proxy.

### 3. Behavioral
   Behavioral patterns are about identifying common communication patterns between objects and realize these patterns.

   Behavioral patterns are Chain of responsibility, Command, Interpreter, Iterator, Mediator, Memento, Null Object, Observer, State, Strategy, Template method, Visitor
