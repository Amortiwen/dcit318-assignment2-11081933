# DCIT 318: Programming II – Assignment 2

## Student Name: Agalisi Desmond  
## Student ID: 11081933  
## Course: DCIT 318 – Programming II  
## Semester: First Semester, 2025  

### Description

This repository contains three C# console applications demonstrating key concepts in Object-Oriented Programming (OOP). Each program focuses on a specific OOP concept: **Inheritance**, **Abstract Classes**, and **Interfaces**.

---

### Applications

#### 1. Inheritance and Method Overriding
- Defines a base class `Animal` with a virtual method `MakeSound()`.
- Two derived classes:
  - `Dog`: overrides `MakeSound()` to print `"Bark"`.
  - `Cat`: overrides `MakeSound()` to print `"Meow"`.
- In `Main()`, instances of `Animal`, `Dog`, and `Cat` are created and their `MakeSound()` methods are called to demonstrate polymorphism.

#### 2. Abstract Classes and Methods
- Defines an abstract class `Shape` with an abstract method `GetArea()`.
- Two derived classes:
  - `Circle`: implements `GetArea()` to calculate and return the area of a circle.
  - `Rectangle`: implements `GetArea()` to calculate and return the area of a rectangle.
- In `Main()`, instances of `Circle` and `Rectangle` are created, and their areas are displayed.

#### 3. Interfaces
- Defines an interface `IMovable` with a method `Move()`.
- Two classes implement the interface:
  - `Car`: implements `Move()` to print `"Car is moving"`.
  - `Bicycle`: implements `Move()` to print `"Bicycle is moving"`.
- In `Main()`, instances of `Car` and `Bicycle` are created and their `Move()` methods are called.

---

### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/dcit318-assignment2-11081933.git
