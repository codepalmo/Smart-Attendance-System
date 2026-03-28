# Technical Specifications

## 1. Requirements Analysis
### Functional (What it DOES):
- Allows students to log their presence.
- Allows admins to generate attendance reports.
- Validates student ID against the course database.

### Non-Functional (How it BEHAVES):
- **Security**: Only registered users can access the system.
- **Usability**: Simple interface for quick check-ins between classes.

## 2. System Logic (The Flow)
When a student marks attendance:
1. The **View** sends the Student ID to the **Controller**.
2. The **Controller** asks the **Model** if that ID is valid.
3. If valid, the **Model** updates the database and the **View** shows "Success."
