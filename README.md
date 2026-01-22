# 📚 Description
LuminaLib is a Java-based console application designed to manage a library's daily operations. Building on the concepts of Object-Oriented Programming (OOP) used in my previous Cinema Reservation System, this project focuses on inventory management, user borrowing limits, and date-based tracking.

## 🛠️ Core Features
- Inventory Control: Add, update, and remove different types of media (Books, Magazines, DVDs) using Inheritance.
- Member Management: Register new library members and track their specific borrowing history and status.
- Borrowing System: A logic-gate system to check if a document is available and if a member has reached their borrowing limit.
- Deadline Tracking: Automated calculation of return dates and identification of overdue items using java.time.
- Search Engine: Filter the library catalog by author, title, or ISBN.

## 🏗️ Planned Architecture
The project will follow a modular structure similar to the Cinema model:
- `models/`: Containing the logic for Document, Book, Member, and Loan.
- `interfaces/`: Defining behaviors like Borrowable (similar to the Reservable interface in the Cinema project).
- `services/`: Handling the main business logic (e.g., LibraryManager).
- `app/`: The entry point with a CLI (Command Line Interface) menu.

## 🚀 Learning Objectives
- Implement Inheritance and Polymorphism (one base Document class, multiple sub-classes).
- Deepen knowledge of Encapsulation by protecting sensitive data like member IDs and availability statuses.
- Manage Collections using ArrayList to handle dynamic lists of loans and documents.
- Practice Exception Handling for cases like "Book Already Borrowed" or "Member Not Found".