# 🏢 Apartment Expense Management System

*"Gestiune Administrație Bloc"* is a C-based application designed to manage apartment building expenses efficiently. It follows a multi-layered architecture, ensuring scalability, modularity, and maintainability, while applying Object-Oriented Programming (OOP) principles in C.


## 🏗️ Architecture Overview

The project follows a layered architecture, ensuring clarity, scalability, and maintainability throughout the development process:

-  📦 Domain Layer – Core Data Structures
Defines the essential business entities of the application:

    - Cheltuiala – Represents an expense, consisting of:
        -  numar_apartament – The apartment number associated with the expense.

        -  suma – The amount of the expense.

        -  tip – The type of expense (e.g., Water, Gas, Maintenance).

💾 Repository Layer – Data Storage & Management
Handles all data storage and retrieval operations:

✔️ Implements CRUD (Create, Read, Update, Delete) operations.
🗂️ Uses liste dinamice for storing and managing expenses.
⚙️ Optimizes memory usage with malloc/free to ensure efficient performance.

⚙️ Service Layer – Business Logic Implementation
Implements the core functionalities of the system:

🔹 Adding, updating, and deleting expenses ✏️.
🔹 Sorting expenses 🔄 (e.g., by amount, apartment number).
🔹 Filtering expenses 🔍 based on specific parameters.
🔹 Undo Feature ↩️ – Allows users to revert the last action.

🖥️ User Interface (UI) – Command-Line Interface
A menu-driven CLI interface:

🎯 Simple and intuitive navigation.
📊 Real-time feedback for executed operations.
🛑 Input validation and error handling to prevent invalid actions.

✅ Data Validation & Error Handling
Ensures data integrity and system reliability:

✔️ Validates apartment numbers and expense amounts.
❌ Prevents invalid operations (e.g., deleting non-existent expenses).
💡 Manages memory efficiently to avoid memory leaks.
🛠️ Handles incorrect user inputs gracefully to ensure smooth operation.

🌟 Key Features
🔹 Modular, Multi-Layered Architecture 🏗️ – Ensures clean, maintainable code.
🔹 Full Expense Management System 📝 – Supports full CRUD operations.
🔹 Sorting & Filtering 🔍 – Easily retrieve expenses based on various criteria.
🔹 Undo Feature ↩️ – Allows reverting the last action for better control.
🔹 Dynamic Memory Management 🧠 – Uses malloc/free for optimal performance.
🔹 Robust Error Handling 🛡️ – Ensures correct input and prevents unexpected behavior.

🔬 Technical Highlights
🖥️ Language: C
🛠 Architecture: Multi-layered (Domain, Repository, Service, UI)
📂 Data Management: Uses liste dinamice (no database required).
⚡ Memory Management: Efficient allocation and deallocation with malloc/free.
🚀 Performance Optimizations: Sorting and filtering for fast data retrieval.
