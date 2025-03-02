```mermaid
flowchart TD
    A[Student Applies for Accommodation] --> B[Check Registration Status]
    B --> C{Is the student registered for at least 3 modules?}
    C -->|No| D[Reject Application]
    C -->|Yes| E[Check Academic Performance]
    E --> F{Has the student passed all modules?}
    F -->|No| D
    F -->|Yes| G[Check Matriculation Status]
    G --> H{Did the student matriculate at Cape Town?}
    H -->|Yes| D
    H -->|No| I[Approve Application]
    I --> J[Send Confirmation Email]
    D --> K[Send Rejection Email]

