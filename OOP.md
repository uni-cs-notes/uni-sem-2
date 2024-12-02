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
## Encapsulation

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
#### In this code:

* 🔒 Encapsulation is shown by keeping color and model private.
* 🎭 Abstraction is demonstrated by the drive method, which represents the action of driving without exposing implementation details.
## Inheritance
```
class Vehicle {
    public void start() {
        System.out.println("Vehicle is starting.");
    }
}

class Car extends Vehicle {
    public void start() {
        System.out.println("Car is starting.");
    }
}
```
## Polymorphism
```
Vehicle myCar = new Car();
myCar.start(); // Outputs: Car is starting.
```
## 🔹 Control Structures
* Java control structures `guide the flow of execution` in a program.
* Conditional Statements: if-else
```
int age = 18;
if (age >= 18) {
    System.out.println("Eligible to vote.");
} else {
    System.out.println("Not eligible to vote.");
}
```
* `Use case: Make decisions based on conditions.`

## Loops: for
```
for (int i = 1; i <= 5; i++) {
    System.out.println("Iteration " + i);
}
```
* `Use case: Execute a block of code multiple times.`

## 🔹 Arrays and Collections
* `Arrays`
* Fixed-size, contiguous memory storage for similar data types.
```
int[] numbers = {1, 2, 3, 4, 5};
System.out.println(numbers[2]); // Outputs: 3
ArrayList
Dynamic-sized collection from the java.util package.

import java.util.ArrayList;

ArrayList<String> list = new ArrayList<>();
list.add("Java");
System.out.println(list.get(0)); // Outputs: Java
```
* `Use case: Store and manipulate dynamic data.`

## 🔹 Methods
* Encapsulate reusable blocks of code.

* Example: Sum of Numbers
```
public int addNumbers(int a, int b) {
    return a + b; // Returns the sum
}
```
* `Use case: Modularize and reuse logic in programs.`

## 🔹 Exception Handling 🚨
* Handle unexpected situations gracefully.
```
try {
    int result = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Error: Division by zero.");
} finally {
    System.out.println("Execution completed.");
}
```
* `Use case: Ensure robust and error-free applications.`

## 🔹 Multithreading 🧵
* Run multiple tasks simultaneously to improve efficiency.
```
class MyThread extends Thread {
    public void run() {
        System.out.println("Thread is running.");
    }
}

MyThread thread = new MyThread();
thread.start();
```
Use case: Develop responsive and high-performance applications.

