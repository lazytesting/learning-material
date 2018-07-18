# Classes

## What is a class

It's like a car, it provides a specific set of functionalities like driving and steering.
To do that it has a set of components, by example an engine or a steering wheel.

To make it a bit more accurate it's more like a technical drawing of car. You cannot drive it yet, but you know 
exactly what it can do and how it will work.


## What does it contain
Two types of components: 
- Methods
- Properties

## Why are classes useful
It provides a way of seperating specific parts of the application.
- You don't have to scroll between a gazillion lines of code
- It allows you to re-use code

## Instancation
Before you can use a class you need an instance of the class. Just like with the car,
you can't drive a technical drawing.

Why is that useful?


## Example
```
class Main {
  public static void main(String[] args) {
    Hoi hoi = new Hoi();
    Hoi hi = new Hoi();
    hi.SetLanguageEN();
    hoi.ZegHoi();
    hi.ZegHoi();
  }
}
```

```
class Hoi {
  private boolean isEnglish = false;

  public void SetLanguageEN() {
    isEnglish = true;
  }

  public void ZegHoi() {
    if (isEnglish) {
      System.out.println("Hello world!");
    }
    else {
      System.out.println("Hoi wereld!");
    }
  }
}
```