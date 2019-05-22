# Lecture 1 - Course overview; Using objects

## Object-Oriented Programming

* Object: A repository of data.

* Class: Type of object.
* Method: Procedure or function that operates on an object or class.
  	+ addItem(): adds an item to any shoppingList object.

* Inheritance: A class may inherit properties from a more general class.
  - shoppingList inherits from List the property of storing a sequence of items.

* Polymorphism(多型，多态): One method works on several classes, even if the classes need different implementations.
  * e.g., "addItem()" method on **every** kind of List, though adding item to a shoppingList is different from a shoppingCart.

* Object-Oriented: Each object knows its own class & methods. Each shoppingList & shoppingCart knows which implementation applies to it.

## Java

* Variables: You must **declare** them and their **type**.

  * ```java
    int x;
    x = 1
    ```

  * the first line of code does 2 things:

    * Allocates memory to store an integer, type `int`.
    * Names variable "x".

  - Variables are also used to **reference** objects. There are 2 ways to get classes:
    - Use one defined by somebody else. Java has tons(standard library).
    - Define your own.