# Rob Interviewing Alec (12/09/2022)

## 1: What is Spring MVC?
- Model, View, Controler, way to program restful apis
- In Spring, it uses MVC annotations to help take control away from programmer, e.g. @Controller, @RequestMapping
- I enjoy Spring MVC annotations
- *Corrections*:

## 2: What's the difference between Spring Boot and Spring Boot Actuator?
- Spring Boot is a way to initialize Spring Applications
- Use an online version of Spring initializer, use different modules and make a template for boilerplate
- Spring Boot Actuator is different, tool for monitoring metrics/health of app
- *Corrections*: 

## 3: What is Spring Data JPA?
- Spring Java Persistence API helps Spring app to take models and transfer data to databases (map non-compatible data together), build repos
- Similar to JDBC, but JPA is more powerful, comes with list of many pre-made requests and database transactions. You can also write your own
- *Corrections*:

## 4: What are some Bean Scopes? 
- Scopes refer to lifespan of object, depends on situation, whether lifespan is whole of application or single request
- There are multiple scopes; they relate to lifespan of a bean.
- Singleton scope for individual objects
- Prototype scope for multiple objects
- Other web scopes for requests, sessions, application, global, etc.
- *Corrections*: 

## 5: What is a Spring IoC Container?
- In Spring, there is a concept "inversion of control"
- There are two containers: 
- Bean factory: lazily intantiates beans
- App Context: instantiates beans eagerly / pre-instantiates them
- Bean Factory and App Context are like a program within a program, they decide when to create beans and manage them
- They do this through different types of dependency injection: constructor injection (included in instantiation/immutable) & setter injection (allows for partial injection / beans are already created when injected)
- *Corrections*:  


## 6: What are all of the TS data types?
- array
- boolean
- string
- enum
- number
- tuple
- void
- any
- null
- *Corrections*:

## 7: Different SQL sublanguages?
- DDL - data definition language: create, alter
- DML - data manipulation language: insert, update, delete
- TCL - transactional control language
- DQL - data query language
- DCL - data control language: security
- SCL - session control language
- *Additions*: DQL has SELECT; TCL has COMMIT

## 8: What constraints are implied in PRIMARY KEY?
- UNIQUE
- NOT NULL
- *Corrections*: 


## 9: With regards to Angular, tell me as much as you can about "Directives."
- Some used for loops, data binding
- Component directive: most common, used to specify template, how component should be used -- like the "@Autowire" of Angular
- Structural: *ngIf, *ngFor
- Attribute: changing how a component looks 
- *Corrections*: -

## 10: The four OOP pillars in 10 words or less:
- Abstraction: simplifies code use by replacing implementation details with naming convention 
- Polymorphism: changing object behavior through overloading and overriding object methods
- Encapsulation: protecting data through private variables and methods in classes
- Inheritance: parent-child relationships between objects through class extensions
- *Corrections*: 







