# 🏢 Apartment Expense Management System

*"Gestiune Administrație Bloc"* is a C-based application designed to manage apartment building expenses efficiently. It follows a multi-layered architecture, ensuring scalability, modularity, and maintainability, while applying Object-Oriented Programming (OOP) principles in C.


## 🏗️ Architecture Overview

The project follows a multi-layered architecture, ensuring clarity, scalability, and maintainability throughout the development process:

-  📦 Domain Layer: Contains the core data entities, defining the fundamental components of the system:

      -  Cheltuiala – Represents an expense with attributes such as numar_apartament (apartment number), suma (expense amount), and tip (expense type, e.g., Water, Gas, Maintenance).

-  💾 Repository Layer: Responsible for handling data storage and retrieval:

      -  Implements CRUD (Create, Read, Update, Delete) operations to manage expense data.

      -  Uses liste dinamice (dynamic lists) for storing and managing expense records.

-  ⚙️ Service Layer: Implements the business logic of the system:

      -  Manages the addition, updating, and deletion of expenses.

      -  Allows sorting and filtering of expenses based on criteria such as apartment number or expense amount.

-  🖥️ Console Interface (UI): Provides an interactive user interface via the command line:

      -  Offers a simple, menu-driven navigation system for users.

      -  Handles input, output, and error management for smooth user interaction.

-  ✅ Validation Module: Ensures data integrity and prevents invalid entries:

      -  Validates correct apartment numbers and expense amounts.

      -  Prevents the addition or deletion of non-existent records.

## 🗂️ Data Persistence
The system employs a file-based data storage approach, making it easy to implement and maintain:

-  *cheltuieli.txt* — Stores expense records.

-  *apartamente.txt* — Contains apartment data, including apartment numbers and associated expenses.

## 🌟 Key Features
-  🎯 **Modular Design**: The multi-layered architecture ensures clear separation of concerns, improving both code comprehension and maintainability.

-  🔍 **Input Validation**: Strong validation rules ensure the integrity and consistency of user data, preventing errors and inconsistencies.

-  📤 **Full CRUD Functionality**: Supports full lifecycle management for expenses, providing a complete solution for tracking apartment building expenses.

-  📑 **Sorting & Filtering**: Advanced query options allow users to filter and sort expenses, making it easier to find specific records.

-  🛠️ **Efficient Memory Management**: Uses malloc and free for dynamic memory allocation, ensuring optimal system performance and avoiding memory leaks.

-  🛡️ **Robust Error Handling**: The system is built to gracefully handle errors, ensuring stability even when faced with invalid inputs or unexpected scenarios.

## 🔬 Technical Highlights
-  **Language**: C

-  **Architecture**: Multi-layered architecture (Domain, Repository, Service, UI)

-  **Data Persistence**: File-based system using text files for storing records

-  **Memory Management**: Efficient use of malloc and free for dynamic memory allocation

-  **Error Management**: Comprehensive input validation and exception handling



