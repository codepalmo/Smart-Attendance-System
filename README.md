# 📑 Smart Attendance System (SAS)
*A Software Engineering Approach to Automated Classroom Management*

## 🎯 Project Overview
The **Smart Attendance System** is designed to solve the problem of manual attendance tracking. By digitizing the process, we reduce paper waste, save time, and ensure data integrity.

## 🚀 Key Features 
- **User Authentication**: Separate secure portals for Faculty and Students.
- **Automated Logging**: Attendance is marked with a single scan/click, preventing manual entry errors.
- **Dynamic Reporting**: Generates instant summaries so teachers don't have to calculate percentages manually.
- **Scalability**: The system is designed to handle multiple classrooms simultaneously.

## 🏗️ Architectural Design 
I chose the **Model-View-Controller (MVC)** architecture for this project:
1. **Model (Data)**: Manages student records and attendance logs.
2. **View (Interface)**: The screens the students and teachers interact with.
3. **Controller (Logic)**: The "brain" that checks if a student is actually enrolled before marking them present.
