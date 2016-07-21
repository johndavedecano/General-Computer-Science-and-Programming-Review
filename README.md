# Computer Science and Programming Notes

## Data Structures
1. Linked List
2. Stack
3. Queue
4. Binary Tree
5. Binary Search Tree
6. Heap
7. Hashing
8. Graph
9. Array
10. Matrix

##Algorithms
Search − Algorithm to search an item in a datastructure.
Sort − Algorithm to sort items in certain order
Insert − Algorithm to insert item in a datastructure
Update − Algorithm to update an existing item in a data structure
Delete − Algorithm to delete an existing item from a data structure

##What is Object
In programming terms, an object is a self-contained component that contains properties and methods needed to make a certain type of data useful. An object’s properties are what it knows and its methods are what it can do. The project management application mentioned above had a status object, a cost object, and a client object, among others. One property of the status object would be the current status of the project. The status object would have a method that could update that status. The client object’s properties would include all of the important details about the client and its methods would be able to change them. The cost object would have methods necessary to calculate the project’s cost based on hours worked, hourly rate, materials cost, and fees.

##Design Patterns

###Creational Patterns
These design patterns provides way to create objects while hiding the creation logic, rather than instantiating objects directly using new opreator. This gives program more flexibility in deciding which objects need to be created for a given use case.

1. Singleton Pattern
2. Factory Pattern
3. Facade Pattern
4. Abstract Factory Pattern

###Structural Patterns
These design patterns concern class and object composition. Concept of inheritance is used to compose interfaces and define ways to compose objects to obtain new functionalities.

1. Adapter Pattern
2. Bridge Pattern
3. Decorator Pattern
4. MVC Pattern
5. DAO Pattern

###Behavioral Patterns
These design patterns are specifically concerned with communication between objects.

1. Observer Pattern
2. Strategy Pattern
3. Chain of Responsibility

##Principles of Object Oriented Programming
1. **Encapsulation** - is an Object Oriented Programming concept that binds together the data and functions that manipulate the data, and that keeps both safe from outside interference and misuse. Data encapsulation led to the important OOP concept of data hiding.
2. **Abstraction** - is one of three central principles (along with encapsulation and inheritance). Through the process of abstraction, a programmer hides all but the relevant data about an object in order to reduce complexity and increase efficiency.
3. **Inheritance** - In object-oriented programming, inheritance enables new objects to take on the properties of existing objects. A class that is used as the basis for inheritance is called a superclass or base class. A class that inherits from a superclass is called a subclass or derived class. The terms parent class and child class are also acceptable terms to use respectively. A child inherits visible properties and methods from its parent while adding additional properties and methods of its own.
4. **Polymorphism** - Polymorphism means to process objects differently based on their data type. Polymorphism is a Greek word that means "many-shaped". 

##SOLID Principles

1. SRP The Single Responsibility Principle A class should have one, and only one, reason to change.
2. OCP	The Open Closed Principle	You should be able to extend a classes behavior, without modifying it.
3. LSP	The Liskov Substitution Principle	Child classes must be able to override parent classes references without any problems.
4. ISP	The Interface Segregation Principle	Make fine grained interfaces that are client specific. Clients should not be forced to depend upon interfaces that they don't use.
5. DIP	The Dependency Inversion Principle - High-level modules should not depend on low-level modules. Both should depend on abstractions. Abstractions should not depend on details. Details should depend on abstractions.

##References
1. http://www.oodesign.com/design-principles.html
2. http://beginnersbook.com/2013/03/oops-in-java-encapsulation-inheritance-polymorphism-abstraction/
3. https://en.wikipedia.org/wiki/Hash_table
4. http://www.tutorialspoint.com/cprogramming/c_arrays.htm
5. https://en.wikipedia.org/wiki/Binary_tree
