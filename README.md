# design-patterns-python

## Getting Started

These instructions will get you through my exploration of design patterns. The explanations and implementations will be provided along with the time.

### The Principal of Design Patterns

In software engineering, a software design pattern is a general, reusable solution to a commonly occurring problem within a given context in software design. To fully have a good command of it, it is better to understand the principal behind it.

  - Single Responsibility Principal
  
    - definition: every module or class should have responsibility over a single part of the functionality provided by the software, and that responsibility should be entirely encapsulated by the class.
    - advantages: lower the complexity of class, increase readability, maintainability and scalability.
    
  - Liskov Substitution Principal
  
      - definition: if S is a subtype of T, then objects of type T may be replaced with objects of type S (i.e. an object of type T may be substituted with any object of a subtype S) without altering any of the desirable properties of the program (correctness, task performed, etc.). 
    - advantages: increase robustness; 
    
  - Dependence Inversion Principal
  
      - definition: High-level modules should not depend on low-level modules. Both should depend on abstractions; Abstractions should not depend on details. Details should depend on abstractions. 
      - advantages: reduce the amount of work caused by changes in demand
    
  - Interface Segregation Principal
  
      - definition: no client should be forced to depend on methods it does not use. Instead of one fat interface many small interfaces are preferred based on groups of methods, each one serving one submodule.
      - advantages: produce a flexible design 
  
  - Law of Demeter
  
      - definition: "Only talk to your friends" is the motto.
      - advantages: tends to be more maintainable and adaptable. 
      
  - Open Close Principal
  
      - definition: "software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification"; that is, such an entity can allow its behaviour to be extended without modifying its source code.
      - advantages: tends to be more maintainable and adaptable. 
      
All in all, SRP tells us one module should only have responsibility over a single part; LSP tells us not to destruct inheritance system; DIP tells us to code parameter-oriented.ISP tells us to design simple but essential interface; LoD tells us to loose decoupling; OCP tells us to open for expanding but close for modification. Or I should say, high cohesion low decoupling is the ultimate goal.



### Design Patterns

#### simple factory pattern
