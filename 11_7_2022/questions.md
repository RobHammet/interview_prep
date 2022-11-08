# Rob Interviewing Hika (11/7/2022)

## 1: Which is threadsafe, hashmap or hashtable?
- hashtable
- *Corrections*: additon: HashMap is non-syncronized and so not thread safe while HashTable is thread safe and is synchronized.

## 2: What is the difference between list and set?
- list is ordered, set is unordered
- list is indexed, can access items by index; set has no index
- list can hold duplicate values, set elements must be unique
- 
- *Corrections*: additions: list can have unlimited null values, set can have one null value

## 3: What is GC in Java? How is it used?
- garbage collector
- it automatically manages heap memory
- whenever an object isn't referenced anymore, that object will be eligible for gc
- *Corrections*: none

## 4: What is the difference between Vector and Stack?
- they are both descendents of list class (interface?), they extend it
- stack extends vector, it follows LIFO (last in first out)
- *Corrections*: list is an interface which is implemented by vector and stack; addition: stack has methods like push, pop, and peek

## 5: How would you write an enhanced for loop in Java that iterates through all dogs in an array but only calls the dog's bark method if its color field is "gray"?
- for(gray:dogs){bark()}
- *Corrections*: for ( dog : dogs) { 
if (dog.color == "gray")
dog.bark();
}


## 6: How is TRUNCATE used in SQL?
- we use truncate to delete table
- it keeps structure of table, but deletes all data
- *Corrections*:

## 7: Using SQL, how would you select all names of employees in a table which contain the letter Z?
- select name from employee where name like "%z%"
- *Corrections*: single quotes: ''

## 8: Explain the difference between relational and non-relational databases.
- relational DBs have tables, which have relationship to one another by way of foreign keys
- non-relational DBs store data that don't have relationships with one another
- *Corrections*: additions: non-relational does not use tables; they are document-oriented, can capture all types of data, and are more flexible


## 9: Using SQL, how would you select the first name and last name of all employees from an employee table?
- select firstname, lastname from employees
- *Corrections*:

## 10: What is a 'View' in SQL?
- when you join different tables and extract the data you want
- like virtual table
- you create views to access multiple tables by use of joins, etc.
- *Corrections*: you can create a view from one table







