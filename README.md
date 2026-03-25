# BookMyStay - Hotel Booking Management System

A comprehensive Java-based hotel booking system demonstrating Object-Oriented Programming (OOP) principles, data structures, and software engineering concepts through 12 progressive use cases.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Use Cases](#use-cases)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

BookMyStay is an educational Java project that implements a complete hotel room booking system. The project is structured as 12 use cases (UC1-UC12), each demonstrating different programming concepts and building upon previous implementations. It showcases real-world software development practices including encapsulation, inheritance, polymorphism, exception handling, multithreading, and data persistence.

## ✨ Features

### Core Functionality
- **Room Management**: Three room types (Single, Double, Suite) with different pricing
- **Inventory Tracking**: Real-time availability management
- **Booking System**: FIFO queue-based booking requests
- **Room Allocation**: Unique room ID generation and assignment
- **Add-on Services**: Optional services like breakfast, WiFi, spa
- **Booking History**: Complete reservation tracking and reporting

### Advanced Features
- **Concurrent Processing**: Thread-safe booking handling
- **Data Persistence**: File-based inventory storage and recovery
- **Error Handling**: Comprehensive validation and exception management
- **Cancellation System**: Booking cancellation with inventory rollback
- **Search Functionality**: Available room filtering

## 🏗️ Architecture

The system follows a layered architecture with clear separation of concerns:

- **Domain Layer**: Room classes with inheritance hierarchy
- **Service Layer**: Business logic for booking, inventory, and reporting
- **Data Layer**: Persistence and state management
- **Presentation Layer**: Console-based user interface

### Key Design Patterns
- **Abstract Factory**: Room creation
- **Observer**: Inventory updates
- **Strategy**: Different booking strategies
- **Singleton**: Service instances
- **Command**: Booking operations

## 📚 Use Cases

| Use Case | Description | Key Concepts |
|----------|-------------|--------------|
| **UC1** | System Welcome | Basic Java application structure |
| **UC2** | Room Details Display | OOP (Abstraction, Encapsulation, Polymorphism) |
| **UC3** | Inventory Management | HashMap, state management |
| **UC4** | Room Search | Service layer, filtering |
| **UC5** | Booking Queue | Queue data structure, FIFO |
| **UC6** | Booking Processing | Atomic operations, ID generation |
| **UC7** | Add-on Services | Composite pattern, cost calculation |
| **UC8** | Booking Reports | Collections, data aggregation |
| **UC9** | Input Validation | Exception handling, defensive programming |
| **UC10** | Booking Cancellation | Stack, rollback operations |
| **UC11** | Concurrent Booking | Multithreading, synchronization |
| **UC12** | Data Persistence | File I/O, system recovery |

## 📋 Prerequisites

- **Java Development Kit (JDK)**: Version 8 or higher
- **Text Editor/IDE**: VS Code, IntelliJ IDEA, or Eclipse
- **Operating System**: Windows, macOS, or Linux

## 🚀 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd BookMyStay
   ```

2. **Compile the Project**
   ```bash
   # Compile all Java files
   javac *.java
   ```

3. **Run Individual Use Cases**
   ```bash
   # Run a specific use case (replace X with 1-12)
   java UCX
   ```

## 💻 Usage

### Running Use Cases

Each use case can be run independently to demonstrate specific functionality:

```bash
# Welcome screen
java UC1

# Room details and availability
java UC2

# Inventory management
java UC3

# Room search
java UC4

# Booking queue
java UC5

# Booking processing
java UC6

# Add-on services
java UC7

# Booking reports
java UC8

# Input validation
java UC9

# Booking cancellation
java UC10

# Concurrent booking
java UC11

# Data persistence
java UC12
```

### Sample Output

```
======================================
        BOOK MY STAY APP
     Hotel Booking System v1.0
======================================
Welcome to the Hotel Booking Management System!
Application started successfully.
Thank you for using Book My Stay.
```

## 📁 Project Structure

```
BookMyStay/
├── README.md                 # Project documentation
├── inventory.txt            # Persistent inventory data
├── UC1.java                 # System welcome
├── UC2.java                 # Room details display
├── UC3.java                 # Inventory management
├── UC4.java                 # Room search service
├── UC5.java                 # Booking queue
├── UC6.java                 # Booking processing
├── UC7.java                 # Add-on services
├── UC8.java                 # Booking reports
├── UC9.java                 # Input validation
├── UC10.java                # Booking cancellation
├── UC11.java                # Concurrent processing
└── UC12.java                # Data persistence
```

## 🛠️ Technologies Used

- **Language**: Java (SE 8+)
- **Data Structures**: ArrayList, HashMap, Queue, Stack, Set
- **Concurrency**: Threads, Synchronization
- **File I/O**: BufferedReader, BufferedWriter
- **Exception Handling**: Custom exceptions
- **Collections Framework**: Java Collections API

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎓 Educational Value

This project serves as an excellent learning resource for:

- **Java Fundamentals**: OOP concepts, data types, control structures
- **Data Structures**: Practical implementation of collections
- **Software Design**: Layered architecture, separation of concerns
- **Concurrency**: Thread safety, synchronization
- **File Handling**: Persistence, data recovery
- **Error Handling**: Validation, exception management

## 📞 Support

For questions or issues, please open an issue in the repository or contact the development team.

---

**Happy Coding! 🚀**