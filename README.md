# Student Accommodation Qualification Verification System

## Project Description
The **Student Accommodation Qualification Verification System** is designed to determine whether a student qualifies for university-provided accommodation. The system evaluates student eligibility based on three key criteria:

1. The student must be registered for a minimum of **three (3) modules**.
2. The student must have **passed all registered modules**.
3. The student must **not have matriculated in Cape Town**.

If all conditions are met, the student's application is approved. Otherwise, the application is rejected.

## Features
- Automated verification of student eligibility.
- Integration with student records to fetch academic and registration details.
- Notification system to inform students about their application status.
- Secure and efficient data processing.

## System Flow
The verification process follows this flow:
1. The student applies for accommodation.
2. The system checks if the student is registered for at least 3 modules.
3. If registered, the system checks if the student has passed all modules.
4. If passed, the system verifies the student's matriculation location.
5. If the student has **not** matriculated in Cape Town, the application is approved.
6. Otherwise, the application is rejected.

## Repository Structure
```
|-- Student-Accommodation-Verification
    |-- README.md  # Project documentation
    |-- SPECIFICATION.md  # System specification document
    |-- ARCHITECTURE.md  # C4 architectural diagrams
    |-- src/  # Source code files
    |-- docs/  # Additional documentation
```

## Related Documents
- [System Specification](SPECIFICATION.md)
- [Architectural Design](ARCHITECTURE.md)

## Technologies Used
- Programming Language: Python/Java/Node.js (Choose based on implementation preference)
- Database: MySQL/PostgreSQL
- Frontend: HTML, CSS, JavaScript (if applicable)
- Backend Framework: Django/Flask/Spring Boot/Express.js

## How to Contribute
1. Fork the repository.
2. Clone your forked repository.
3. Create a new branch for your feature.
4. Commit and push changes to the branch.
5. Submit a pull request.
