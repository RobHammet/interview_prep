# Rob Interviewing Luke (11/2/2022)

## 1: What are JDK, JRE, and JVM?
- Java Development Kit - includes JRE
- Java Runtime Environment - includes JVM
- Java Virtual Machine 

## 2: Can non-static methods refer to static variables? Vice versa? Why?
- Non-static methods can refer to static variables, because static variables can be accessible globally
- Static methods cannot access non-static variables, because non-static variables cannot be globally accessible
- *Corrections*: instead of saying "accessed globally", we should say that static variables/methods (class variables/methods) only have one instance, so non-static variables can't be referred to in static methods, because they might be different

## 3: What is meant by "constructor chaining"? How is it done?
- Constructor chaining is constructor overloading. If you have the same cunstructor name and different (+ # of) arguments, you can change the constructor.
- *Corrections*: chaining is used in subclasses, and in order to chain, you need to call the "super"

## 4: What is the difference between hierarchical and multi-level inheritance?
- You cannot inherit multiple inheritance, but you can do multi-level inheritance. Multi-level inheritance means if you inherit from a parent class, and the child class is a child of a child class.
- Hierarchical = ?
- *Corrections*: hierarchical inheritance is when one parent class is inherited by multiple child classes

## 5: What is a wrapper class and when might it be used?
- Wrapper class is related to auto-boxing and boxing. 
- You can change primitive types into String type, and from String type to primitive types
- You don't need to worry about it these days, auto-boxing
- *Corrections*: not only String; primitives are converted into many Object types. Many times this is used for Collections, which don't accept primitive types

## 6: What are some SQL sublanguages?
- DDL: data definition language
- DML: data manipulation language
- DCL: data control language
- TCL: transactional control language
- DQL: data query language
- *Corrections*: we can add some examples of statements or descriptions to each, i.e.
- DDL creates or drops tables, DML updates or deletes rows in tables, DQL selects specific chosen data/records, TCL is about committing and saving/rolling back states, DCL gives access permissions, etc.

## 7: What are DQL clauses?
- Select statement
- *Corrections*: Select is the main statement, but the underlying clauses are things like:
- WHERE
- HAVING
- GROUP BY
- ORDER BY

## 8: Using SQL, how might you get the total number of records in a table called "employees"?
- Can use count
- select count() from employees;
- *Corrections*: select count(*) from employees;


## 9: What are some common SQL constraints?
- Foreign key
- Primary key
- *Corrections*: we can probably mention more, e.g.
- NOT NULL
- UNIQUE
- DEFAULT, etc.

## 10: What is a foreign key?
- Foreign key is key which links two tables
- It is a column(s) whose values match primary key in a different table 







