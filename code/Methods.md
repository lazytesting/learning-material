# Methods

## What is a method

It's a part of a class which allows you to do things with an instance of the class or the data which is hold in the class.
If you see the class as a car (see classes)[./Classes.md] then the steering wheel is a method.

## Input / Output
- A method can have an zero to many inputs.
- A method can have zero or one outputs


## Example

```
  private String helloWorld(String firstName, String lastName) {
     String message = "hello " + firstName + " " + lastName;
     return message;
  }
```
 co
In this example you can see a simple method, let's break it down:
- private => the access modifier of the method
- String => the type of the value which will be returned (output)
- helloWorld => the name of the method
- String => the type of the first input variable
- firstName => name of the first input variable
- String => the type of the second input variable
- lastName => name of the second input variable
- return message => the value which is returned by the method (output)


## Access modifier
This says from where you can use the method
- private => only from the class where the method is in
- public => from every class where you have an instance of the class where the method is in
- protected => only from classes which are inheriting the the class where the method is in

## Keep it pure
It's a good idea to keep methods as pure as possible.
- Don't use anything outside the method, only the input parameters
- Don't change/affect anything outside the method, only return something

Some reasons to do it:
- It makes unit testing easy
- It increase readability
- It can prevent a lot of strange behaviour due to unforseen side-affects
