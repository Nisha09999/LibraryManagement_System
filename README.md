# Library Management System (Java)

An in-memory Library Management System in Java demonstrating OOP principles, SOLID design, and patterns (Factory, Observer, Strategy).

## Features
- Book Management → Add, remove, update, search (title, author, ISBN)
- Patron Management → Add/update patrons, track borrowing history
- Lending Process → Checkout and return books
- Inventory Management → Track available vs borrowed books
- Reservation System → Reserve unavailable books, get notifications
- Recommendation System → Suggest books using strategies
- Factory Pattern → Centralized object creation

## Tech & Design
- Java Collections: List, Set, Map, Queue
- Logging: java.util.logging
- Patterns: Factory, Observer, Strategy
- OOP: Inheritance, Encapsulation, Polymorphism, Abstraction
- SOLID principles applied

## Structure
src/main/java
 ├── app/         → Main entry
 ├── factory/     → Model factories
 ├── model/       → Book, Patron, BorrowRecord, Reservation
 ├── observer/    → Observer & Subject
 ├── service/     → Inventory, Patron, Lending, Notification, Recommendation, Library
 └── strategy/    → Recommendation strategies

## Run
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
javac -d out $(find src/main/java -name "*.java")
java -cp out app.Main

## Example
- Add books/patrons
- Checkout/return
- Reserve & notify
- Generate recommendations

## Class Diagram
(PlantUML diagram provided in README)

