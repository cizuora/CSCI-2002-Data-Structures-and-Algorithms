# CSCI 2002 – Data Structures and Algorithms ☕

Assignments and labs from **CSCI 2002 - Data Structures and Algorithms** course.  
All projects are written in **Java** and cover core data structures including stacks, queues, bags, arrays, and ArrayLists.

---

## 📁 Repository Structure

```
CSCI-2002-Data-Structures-and-Algorithms/
│
├── Assignment1/
│   ├── Car.java
│   └── CarAutoTester.java
│
├── Assignment2/
│   ├── BagInterface.java
│   ├── ArrayBag.java
│   └── ArrayBagTester.java
│
├── Assignment3/
│   ├── Ticket.java
│   ├── TicketStack.java
│   ├── RideQueue.java
│   └── ThemeParkTicketingSystemTester.java
│
├── lab1/
│   ├── Die.java
│   └── DiceDemo.java
│
├── lab2/
│   ├── Book.java
│   └── Student.java
│
├── lab3/
│   ├── AreaCalculator.java
│   └── MathOperations.java
│
├── lab4/
│   └── ArrayIntro.java
│
├── lab5/
│   └── ArrayListIntro.java
│
├── lab6/
│   ├── Book.java
│   └── BookEqualsTest.java
│
├── .gitignore
└── README.md
```

---

## 📚 Assignments

### Assignment 1 – Car Class
Models a `Car` object with fuel management and driving logic.  
**Concepts:** Encapsulation, constructors, getters/setters, method design.

Key features:
- Default and overloaded constructors
- `drive(double distance)` — calculates fuel consumption, handles running out of gas
- `fillGas(double amount)` — prevents overfilling the tank
- `canDrive(double distance)` — checks if enough fuel exists for a trip
- `CarAutoTester.java` — automated test suite with scoring

How to run:
```bash
cd Assignment1
javac Car.java CarAutoTester.java
java CarAutoTester
```

---

### Assignment 2 – Array Bag
Implements the `BagInterface<T>` using a fixed-size generic array.  
**Concepts:** Interfaces, generics, array-based ADTs (Abstract Data Types).

Key features:
- `BagInterface.java` — defines the Bag ADT contract
- `ArrayBag.java` — full array-based implementation with 8 extra methods:
  - `union` — combines two bags into one
  - `intersection` — finds common elements between two bags
  - `difference` — subtracts one bag from another
  - `replace` — replaces an element in the bag
  - `toSet` — removes duplicates from the bag
  - `getMostFrequentItem` — returns the most common element
  - `isSubsetOf` — checks if this bag is a subset of another
  - `areEqual` — checks if two bags contain the same elements
- `ArrayBagTester.java` — automated test suite with scoring (25 points)

How to run:
```bash
cd Assignment2
javac BagInterface.java ArrayBag.java ArrayBagTester.java
java ArrayBagTester
```

---

### Assignment 3 – Theme Park Ticketing System
Simulates a theme park ticketing system using both a **Stack** and a **Queue**.  
**Concepts:** Stacks, queues, LIFO/FIFO behavior, object-oriented design.

Key features:
- `Ticket.java` — models a theme park ticket with ID and customer name
- `TicketStack.java` — stack-based ticket management (LIFO); sell and return tickets
- `RideQueue.java` — queue-based ride line (FIFO); add and remove customers
- `ThemeParkTicketingSystemTester.java` — full automated system test (25 points)

How to run:
```bash
cd Assignment3
javac Ticket.java TicketStack.java RideQueue.java ThemeParkTicketingSystemTester.java
java ThemeParkTicketingSystemTester
```

---

## 🧪 Labs

### Lab 1 – Dice Simulation
Models a `Die` object and simulates dice rolls with configurable sides.  
**Concepts:** Classes, constructors, random number generation, object instantiation.

```bash
cd lab1
javac Die.java DiceDemo.java
java DiceDemo
```

---

### Lab 2 – Book and Student Classes
Basic OOP practice with `Book` and `Student` classes including constructors, getters/setters, and `toString()`.  
**Concepts:** Classes, instance variables, constructors, encapsulation.

```bash
cd lab2
javac Book.java Student.java
java Book
java Student
```

---

### Lab 3 – Area Calculator & Math Operations
Demonstrates **method overloading** through geometric calculations and arithmetic operations.  
**Concepts:** Method overloading, static methods, primitive types.

```bash
cd lab3
javac AreaCalculator.java MathOperations.java
java AreaCalculator
java MathOperations
```

---

### Lab 4 – Array Introduction
Introduction to Java arrays — declaring, accessing, modifying, iterating, and finding the maximum value.  
**Concepts:** Arrays, for loops, enhanced for loops, indexing.

```bash
cd lab4
javac ArrayIntro.java
java ArrayIntro
```

---

### Lab 5 – ArrayList Introduction
Introduction to Java's `ArrayList` with sorting, searching, and element manipulation.  
**Concepts:** ArrayLists, `Collections.sort()`, dynamic sizing, built-in methods.

```bash
cd lab5
javac ArrayListIntro.java
java ArrayListIntro
```

---

### Lab 6 – Book equals() and Method Chaining
Explores `equals()` override for value-based object comparison and **method chaining** using `return this`.  
**Concepts:** Object equality, `equals()` override, method chaining, reference vs value comparison.

```bash
cd lab6
javac Book.java BookEqualsTest.java
java BookEqualsTest
```

---

## 🧠 Topics Covered

| | Topic |
|---|---|
| Assignment 1 | Classes, encapsulation, constructors, method design |
| Assignment 2 | Interfaces, generics, array-based ADTs, set operations |
| Assignment 3 | Stacks, queues, LIFO/FIFO, OOP system design |
| Lab 1 | Classes, random number generation |
| Lab 2 | OOP basics, constructors, encapsulation |
| Lab 3 | Method overloading |
| Lab 4 | Arrays, loops, indexing |
| Lab 5 | ArrayLists, sorting, searching |
| Lab 6 | Object equality, method chaining |

---

## ⚙️ Prerequisites

- Java JDK 8 or higher
- Any Java IDE (Eclipse, IntelliJ, VS Code) or command line

Check your Java version:
```bash
java -version
```

---

## 👤 Author

**Chidera Izuora**  
Computer Science Student  
Course: CS2002 – Data Structures and Algorithms

- GitHub: [github.com/cizuora](https://github.com/cizuora)
- Email: cizuora@gmail.com
- LinkedIn: [linkedin.com/in/chidera-izuora-233804146](https://www.linkedin.com/in/chidera-izuora-233804146/)
