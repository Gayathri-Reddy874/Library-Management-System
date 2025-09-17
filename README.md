C Library Management System 📚

This repository contains a simple, yet robust, Library Management System (LMS) developed entirely in the C programming language. This console-based application serves as a strong demonstration of foundational C skills, including file handling, basic data management, and direct console manipulation. It's a testament to building a functional system from the ground up without external libraries, showcasing a deep understanding of core programming principles.

Core Functionality
Book and Data Management: The system allows for adding, viewing, editing, and deleting book records. All data is persisted to a binary file (Record.dat), proving proficiency in binary file I/O for efficient data storage and retrieval.

User Authentication: It includes a simple login system with a password stored in a separate file (password.dat), demonstrating basic user security concepts and file handling for authentication.

Search and Retrieval: Users can search for books by their unique ID or name, highlighting the implementation of sequential search logic.

Console UI: The code uses Windows-specific functions like gotoxy() and SetConsoleCursorPosition to create a structured and clean text-based user interface, going beyond simple printf and scanf functions to offer a more interactive experience.

Modular Design: The project is organized into multiple header and source files (general_functions.h, core_functions.h), which helps to keep the code clean, organized, and easy to maintain. This structure reflects a professional approach to code organization.

Project Highlights
This project is a great example for students and developers seeking to understand how to build a complete application using only the C standard library and basic console manipulation techniques. It solidifies core concepts like structures, pointers, file handling, and function modularity in a practical and understandable context.
