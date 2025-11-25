# 🚗 Car Rental Management System (Java GUI + JSP/Servlet + JDBC)

A complete Java-based Car Rental System built using:

- Java Swing GUI  
- JSP + Servlet Web Application  
- JDBC + DAO + Database (SQLite-ready)  
- OOP (Inheritance, Polymorphism, Interfaces)  
- Multithreading + Synchronization  
- MVC Architecture  
- Works on IntelliJ IDEA + GitHub + Tomcat  

This project is designed for academic submission and follows Java Review Rubric 1.

---

## ✨ Features

### ✔ Object-Oriented Programming
- `Vehicle` (abstract)
- `Car` (extends Vehicle)
- `Rentable` (interface)
- `CarNotAvailableException` (custom exception)

### ✔ Collections & Generics
- DAO uses `Map<Integer, Car>`
- Service returns `List<Car>`
- In-memory caching

### ✔ Multithreading
- `AutoRefreshThread` logs availability every 5 seconds
- Thread-safe locking using `ReadWriteLock`

### ✔ Database (DAO + JDBC)
- CRUD operations
- PreparedStatements
- Transactions (`commit` + `rollback`)
- Auto table creation (SQLite)

### ✔ GUI Version
Built using Java Swing:
- List available cars
- Rent / Return
- Add / Edit vehicles

### ✔ Web Version (Servlet + JSP)
- JSP views (list, add, edit, rent, return)
- Session messages
- Classic servlet controller (`CarServlet.java`)
- `web.xml` routing

---

## 🗂 Project Structure

