# Python OOP Core Projects 🚀

This repository is a **core Object-Oriented Programming (OOP) playground in Python**, built to deeply understand and apply **real OOP principles** rather than just theory.

All projects here are **small but intentional**, focusing on **clean design, abstractions, and extensibility** — the kind of skills that actually transfer to real software engineering.

> 🔥 **Highlight Project:** `PolygonAreaCalc.py` — a strong demonstration of inheritance, polymorphism, encapsulation, and design thinking.

---

## 🧠 OOP Concepts Demonstrated

This repository intentionally covers:

* **Encapsulation** – controlled access using getters, setters, and private attributes
* **Inheritance** – shared behavior via base classes
* **Abstraction** – interfaces and abstract base classes
* **Polymorphism** – same method names behaving differently across subclasses
* **Single Responsibility Principle** – each class does one job
* **Open/Closed Principle** – new behavior without modifying existing code

---

## 📂 Projects Overview

### 1️⃣ Polygon Area Calculator (**Major Project**)

**File:** `PolygonArea Calc.py`

This is the most important project in the repository.

#### ✅ What it does

Calculates areas of different polygons using a **common interface** while allowing each shape to implement its own logic.

#### 🧩 Design Breakdown

* **Base Class:** `Polygon`

  * Defines the common structure for all shapes
  * Exposes `get_area()` as a shared interface

* **Derived Classes:**

  * `Rectangle`
  * `Square`

Each subclass:

* Inherits from `Polygon`
* Overrides `get_area()` → **polymorphism**
* Uses setters/getters → **encapsulation**

#### 💡 Why this project matters

* Shows how real-world math models map to clean OO design
* Demonstrates extendability (adding a new polygon needs *no changes* to existing logic)
* Mimics real engineering practice instead of exam-style coding

---

### 2️⃣ Discount Calculator (Strategy Pattern)

**File:** `Discount Calculator.py`

* Implements multiple discount strategies
* Each strategy follows the same interface

✅ **OOP Concepts Used:**

* Polymorphism
* Composition over inheritance
* Open/Closed Principle

---

### 3️⃣ Movie Catalogue System

**File:** `Movie Catalogue.py`

* Base media catalogue class
* Specialized classes for Movies and TV Series

✅ Concepts:

* Inheritance
* Method overriding
* Clean object modeling

---

### 4️⃣ Player Interface (Abstraction Example)

**File:** `Player interface.py`

* Uses **abstract base classes (ABC)**
* Defines required methods for player types
* Concrete subclass (`Pawn`) implements behavior

✅ Core Concepts:

* Abstraction
* Interface-based design

---

### 5️⃣ Game Character Stats Tracker

**File:** `Game character stats tracker.py`

* Tracks character attributes like health, level, power
* Demonstrates state management in objects

✅ Concepts:

* Encapsulation
* Object state handling

---

### 6️⃣ Salary Tracker System

**File:** `Salary trackeer.py`

* Employee class with controlled salary updates
* Uses validation inside setters

✅ Demonstrates:

* Encapsulation
* Data protection
* Business rule enforcement

---

## 📌 Why This Repository Exists

This repo is not about writing the **largest** projects.
It is about writing **correct**, **clean**, and **extensible** object-oriented code.

It proves understanding of:

* *Why* inheritance should be used (not overused)
* *When* abstraction is necessary
* *How* polymorphism reduces complexity


---

### ✅ Final Note

If you understand *why* this code is structured the way it is — you understand **real OOP**, not just syntax.


