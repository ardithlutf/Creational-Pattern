# Creational-Pattern

## 1. Introduction
In software engineering, a Design Pattern describes an established solution to the most commonly encountered problems in software design. It represents the best practices evolved over a long period through trial and error by experienced software developers.

No. | Type | Go to File
------------ | ------------- | -------------
01 | Singleton | :rocket: [come here!](https://github.com/Ardith24/Creational-Pattern/tree/master/SingletonPattern/src/singletonpattern) |
02 | Factory Method | available soon |
03 | Abstract Factory | available soon |
04 | Builder | :rocket: [come here!](https://github.com/Ardith24/Creational-Pattern/tree/master/BuilderPattern/src/builderpattern) |



## 2. Creational Design Patterns
Creational Design Patterns are concerned with the way in which objects are created. They reduce complexities and instability by creating objects in a controlled manner.

The new operator is often considered harmful as it scatters objects all over the application. Over time it can become challenging to change an implementation because classes become tightly coupled.

Creational Design Patterns address this issue by decoupling the client entirely from the actual initialization process.

    1. Singleton – Ensures that at most only one instance of an object exists throughout application
    2. Factory Method – Creates objects of several related classes without specifying the exact object to be created
    3. Abstract Factory – Creates families of related dependent objects
    4. Builder – Constructs complex objects using step-by-step approach



## 3. Singleton Design Pattern
The Singleton Design Pattern aims to keep a check on initialization of objects of a particular class by ensuring that only one instance of the object exists throughout the Java Virtual Machine.

A Singleton class also provides one unique global access point to the object so that each subsequent call to the access point returns only that particular object.

### 3.1 When to Use Singleton Design Pattern
    - For resources that are expensive to create (like database connection objects)
    - It's good practice to keep all loggers as Singletons which increases performance
    - Classes which provide access to configuration settings for the application
    - Classes that contain resources that are accessed in shared mode



## 4 Builder Design Pattern
The original Builder Design Pattern introduced by GoF focuses on abstraction and is very good when dealing with complex objects, however, the design is a little complicated.

### 4.1 When to Use Builder Design Pattern
    - When the process involved in creating an object is extremely complex, with lots of mandatory and optional parameters
    - When an increase in the number of constructor parameters leads to a large list of constructors
    - When client expects different representations for the object that's constructed



# References
[www.baeldung.com - Introduction to Creational Design Patterns](https://www.baeldung.com/creational-design-patterns#introduction)
