# Page Objects#



## 1. Why do we need something?##

Sites are more and more component based, pages are just a collection of components. So with the traditional Page Objects we're duplicating a lot of code.

Some examples:

- Each page has a header
- the login form is on multiple pages

## 2. Inheritance ##

Inheritance allows you to inherit functionality from a base class.

 **Conceptual Example**

- Class Dog has 4 legs and eats
- Class Cat has 4 legs and eats

Create base class Animal

- Animal has 4 legs and eats
- Dog inherit from Animal, so it has 4 legs and can eat
- Cat inherit from Animal, so it has 4 legs and can eat

**In Page Objects**

* Class basePage has a home button
* homepage extends basePage, so it has a home button

**In short**

- a class can only inherit from 1 other class
- a class can inherit from a class which inherits another class

## 3. Composition##

Composition let you use functionalities in different classes

**why?**

see conceptual example inheritance, what if we add a fish?

Same for Page Objects, does every page has a home button?

 **Conceptual Example**

- Class Eat can eat
- Class 4 legs can walk
- Class dog implements Eat and 4 Legs
- Class Fish implements Eat 

in short: 

* a class can use multiple other classes by composition
* Bit more work then inheritance
* Think about taxonomy to choose inheritance or composition 

## 4. Further readings##

- https://www.thoughtworks.com/insights/blog/composition-vs-inheritance-how-choose













