# 🦁 Java Zoo Management System

A robust, console-based application demonstrating advanced **Object-Oriented Programming (OOP)** patterns in Java. This project simulates a dynamic zoo environment where diverse animal species interact through shared lineages and distinct behavioral interfaces.

---

## 🚀 Features

* **Complex Inheritance Hierarchy**: Implements a clean class structure where specific animals (`Tiger`, `Dolphin`, `Penguin`) inherit core attributes from an abstract `Animal` base class.
* **Behavioral Abstraction**: Uses Java Interfaces (`Eat`, `Walk`, `Swim`) to decouple actions from class definitions, allowing for flexible behavior assignments.
* **Dual-Environment Logic**: Features a `Penguin` class that uniquely implements both `Walkable` and `Swimmable` interfaces, showcasing multi-behavioral handling.
* **Interactive Management Console**: A user-friendly CLI menu to instantiate animals, trigger specific behaviors, and view real-time status updates.

---

## 🛠️ Architecture & Design

### Class Structure
The project leverages the following design principles:
* **Encapsulation**: Private fields with public getters/setters for animal properties (age, name, species).
* **Polymorphism**: Overridden methods that allow the `Zoo` controller to treat different animals uniformly while executing species-specific logic.
* **Abstract Implementation**: The `Animal` class provides a template for all creatures while enforcing the implementation of the `Eat` interface.

### Tech Stack
* **Language**: Java (JDK 11+)
* **Paradigm**: Object-Oriented Programming

---

## 📖 Usage

1. **Clone the repository**:
   ```bash
   [git clone [https://github.com/yourusername/java-zoo-management.git](https://github.com/yourusername/java-zoo-management.git)](https://github.com/Rei0322/Amazon-Junior-Software-Developer-Professional-Certificate.git)
