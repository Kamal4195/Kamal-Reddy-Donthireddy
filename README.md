# OBJECT ORIENTED PROGRAMMING CONCEPTS

## Objectives

> - Introduction to object oriented programming
 
> - Features of OOPS
 
> - Benefits of OOPS
 
> - Applications of OOPS
## Characteristics of Oriented Programming


  1.Programs are divided into what are known as objects.

  2.Data structures are designed such that they characterize the objects.

  3.Data is hidden and cannot be accessed by external functions.

  4.Objects may communicate with each other through functions.

  5.New data and functions can be easily added whenever necessary.

  6.Follows bottom-up approach in program design.

## Definition

  “Object-oriented programming as an approach that provides a way of
  modularizing programs by creating partitioned memory area for both data and functions that
  can be used as templates for creating copies of such modules on demand.”
  Thus, an object is considered to be partitioned area of computer memory that stores
  data and set of operations that can access that data. 
  
## Basic Concepts of Object-oriented Programming

  It is necessary to understand some of the concepts used extensively in object-oriented
  programming. They are:
 
> - Objects
> - Classes
> - Data abstraction
> - Encapsulation
> - Inheritance
> - Polymorphism
 
 ! [] (https://github.com/Kamal4195/OBJECT-ORIENTED-PROGRAMMING-CONCEPTS/blob/master/Object-Oriented-Programming-Concepts.jpg) 
## Objects

Objects are the basic run-time entities in an object-oriented system. They may
represent a person, a place, a bank account, a table of data or any item that the program has to
handle. They may also represent user-defined data such as vectors, time and lists. Objects take
up space in the memory and have an associated address like a record in Pascal, or a structure
in C. When a program is executed, the objects interact by sending messages to one another.


## Classes

Objects contain data, and code to manipulate that data. The entire set of data and code
of an object can be made a user defined data type with the help of a class. In fact, objects are
variables of the type class. Once a class has been defined, we can create any number of
objects belonging to that class. Each object is associated with the data of type class with
which they are created.

## Encapsulation

The wrapping up of data and functions into a single unit (called class) is known as
encapsulation. Data encapsulation is the most striking feature of a class. The data is not
accessible to the outside world, and only those functions, which are wrapped in the class, can
access it. These functions provide the interface between the object’s data and the program.
This insulation of the data from direct access by the program is called data hiding or
information hiding.

## Data Abstraction

Abstraction refers to the act of representing essential features without including the
background details or explanations. Classes use the concept of abstraction and are defined as a
list of abstract attributes such as size, weight and cost, and functions to operate on these
attributes. They encapsulate all the essential properties of the objects that are to be created.
The attributes are sometimes called data members because they hold information. The
functions that operate on these data are sometimes called methods or member functions. Since
the classes use the concept of data abstraction, they are known as Abstract Data Types (ADT)


## Inheritance

Inheritance is the process by which objects of one class acquire the properties of
objects of another class.Concept of inheritance provides the idea of reusability. This means that we can add
additional features to an existing class without modifying it. This is possible by deriving a
new class from the existing one. The new class will have the combined features of both the
classes. The real appeal and power of the inheritance mechanism is that it allows the
programmer to reuse a class that is almost, but not exactly, what he wants, and to tailor the
class in such a way that it does not introduce any undesirable side-effects into the rest of the
classes. Note that each sub-class defines only those features that are unique to it. Without the
use of classification, each class would have to explicitly include all of its features.

## Polymorphism

Polymorphism means the ability to take more than one form. An operation may exhibit
different behaviors in different instances. The behavior depends upon the types of data used in
the operation.The process of making an operator to exhibit different behaviors in different
instances is known as operator overloading.Polymorphism plays an important role in allowing objects having different
internal structures to share the same external interface. Polymorphism is extensively used in implementing inheritance.
