# 🌟 Introduction to Java and Object-Oriented Programming (OOP) 🌟

## 📚 Overview

Welcome to the world of **Java**! Java is a versatile, object-oriented programming language widely used in application development, from web 🌐 to mobile 📱 and even enterprise applications 🏢. Its "write once, run anywhere" approach means Java code can run on any device with a Java Virtual Machine (JVM), making it incredibly popular in modern software development.

In this module, we’ll start with **Java fundamentals** and later dive into **Object-Oriented Programming (OOP)**, one of the core principles that makes Java so powerful and scalable.

## 🔹 What is Java?

Java was developed by **Sun Microsystems** (now owned by Oracle) in 1995. Java is known for its **portability**, **security**, and **robustness**, making it ideal for large-scale applications. Here are some key highlights of Java:

- 🌍 **Platform Independent**: Thanks to the JVM, Java code can run on any platform, like Windows, macOS, and Linux.
- 🧩 **Object-Oriented**: Java uses OOP concepts, making code easier to manage, scale, and reuse.
- 📚 **Rich Standard Library**: Java comes with an extensive library of pre-built code to help simplify development.
- 🔒 **Secure**: Java includes features like bytecode verification and a Security Manager, making it suitable for building secure applications.

### 🚀 Basic Syntax

Here’s an example of a simple Java program:

```java
// HelloWorld.java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
# 🔹 Java Application Components and Introduction to Object-Oriented Programming (OOP)

## 🛠️ Java Application Components

This program demonstrates the main components of a Java application:

- 🏗️ **Classes**: Java is structured around classes, with `HelloWorld` being an example.
- 🚪 **Methods**: The `main` method is the entry point for any Java program.
- 🔹 **Statements**: Java statements, like `System.out.println`, perform actions within the program.

## 🔹 What is Object-Oriented Programming (OOP)?

**Object-Oriented Programming (OOP)** is a programming paradigm that organizes code into **objects**. These objects represent real-world entities, allowing developers to design more intuitive and scalable software.

Java uses four primary principles of OOP:

1. 🔒 **Encapsulation**: Encapsulating data (attributes) and behaviors (methods) within classes to hide their implementation details.
2. 🎭 **Abstraction**: Providing simplified interfaces for more complex systems, focusing on what an object does rather than how it does it.
3. 🧬 **Inheritance**: Allowing new classes to inherit properties and methods from existing classes, promoting code reusability.
4. 🔄 **Polymorphism**: Enabling a single interface to represent different data types, making code more flexible and extensible.

### 🏎️ Example of OOP Concepts

Consider a simple example of a `Car` class:

```java
// Car.java
public class Car {
    private String color;      // Encapsulation
    private String model;
    
    public Car(String color, String model) { // Constructor
        this.color = color;
        this.model = model;
    }
    
    public void drive() { // Method representing behavior
        System.out.println("The " + color + " " + model + " is driving.");
    }
}
```
In this code:

🔒 Encapsulation is shown by keeping color and model private.
🎭 Abstraction is demonstrated by the drive method, which represents the action of driving without exposing implementation details.
We’ll explore these principles in detail as we progress.

# Understanding `static` in Java

The **static** keyword in Java is a modifier that indicates a member (variable, method, block, or nested class) belongs to the class itself rather than to any specific instance. This means static members can be accessed without creating an instance of the class.

## Key Points

- **Static Variables**: 
  - Shared among all instances of a class.
  - There is only one copy of the static variable, regardless of how many instances of the class are created.

- **Static Methods**: 
  - Can be called without an instance of the class.
  - Can only access static variables and other static methods directly.
  
- **Static Blocks**: 
  - Used for static variable initialization.
  - Executed when the class is loaded.

- **Static Nested Classes**: 
  - Can be instantiated without an outer class instance.
  - Can access static members of the outer class.

## Code Example

```java
public class Counter {
    public static int count = 0; // Static variable

    public Counter() {
        count++; // Increment count for each instance
    }

    public static void displayCount() { // Static method
        System.out.println("Count: " + count);
    }

    public static void main(String[] args) {
        new Counter();
        new Counter();
        Counter.displayCount(); // Outputs "Count: 2"
    }
}
```
