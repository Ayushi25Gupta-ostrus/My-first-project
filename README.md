# My-first-project
Code-flowchart conversion
```mermaid
flowchart TD
    A[Exam Administrator: Initiate scheduling process] --> B[Enter exam details: subject, type, date, time, student count]
    B --> C[System generates timetable draft]
    C --> D[System performs clash check]

    D -->|Clash Found| E[Alert Exam Administrator to revise timetable]
    E --> B

    D -->|No Clash| F[System generates display table: paper name, type, date, time, student count]
    F --> G[Exam Administrator reviews timetable]
    G --> H[Confirm or make changes]
```

