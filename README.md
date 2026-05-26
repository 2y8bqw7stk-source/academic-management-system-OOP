# 🎓 Academic Management System

## 📌 Overview

This project is a robust **Academic Management System** developed in **C++**.  
It is designed to streamline educational administration by centralizing data management for students, faculty, courses, and performance tracking.

The system follows strict **Object-Oriented Programming (OOP)** principles, ensuring a modular architecture with a clear separation between data interfaces and functional logic.



## 📂 Project Structure

The system consists of **19 units** organized into functional modules.  
Each business entity (except the entry point) is composed of a **header file (.h)** for declarations and a **source file (.cpp)** for implementation.



 ### 1. 🧑‍💼 Identity & Personnel

- **Person** (`personne.h / personne.cpp`)  
  Base class defining fundamental identity attributes.

- **Student** (`etudiant.h / etudiant.cpp`)  
  Manages academic records and student-specific data.

- **Teacher** (`enseignant.h / enseignant.cpp`)  
  Handles faculty information and assignments.



 ### 2. 📚 Academic Administration

- **Module** (`Module.h / Module.cpp`)  
  Defines subjects, credits, and course structure.

- **Enrollment** (`inscription.h / inscription.cpp`)  
  Manages registration and student-course relationships.

- **Assessment** (`Note.h / Note.cpp`, `controle.h / controle.cpp`)  
  Handles grading system and exam organization.



 ### 3. ⚙️ Core Engine & Infrastructure

- **System** (`systeme.h / systeme.cpp`)  
  Central controller coordinating all modules.

- **Table** (`tableau.h / tableau.cpp`)  
  Custom data structure for managing object collections.

- **Main** (`Main.cpp`)  
  Entry point containing the main execution loop.



## 🛠️ Technical Specifications

- 🖥️ **Environment**: Dev-C++ IDE  
- 📁 **Project File**: `Seance 3.dev`  
- 💻 **Language**: C++ (ISO C++11 or higher recommended)  
- 🧠 **Paradigm**: Object-Oriented Programming (Inheritance, Encapsulation, Polymorphism)



## 🚀 Getting Started

1. Launch **Dev-C++ IDE**
2. Open the project file: `Seance 3.dev`
3. Ensure all `.h` and `.cpp` files are in the source directory
4. Compile & Run using **F11**
