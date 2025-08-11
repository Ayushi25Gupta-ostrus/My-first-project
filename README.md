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
```mermaid
flowchart TD
    %% Define swimlanes using subgraphs
    subgraph EA[Exam Administrator]
        A[Initiate scheduling process]
        B[Enter exam details: subject, type, date, time, student count]
        G[Review timetable]
        H[Confirm or make changes]
    end

    subgraph SYS[System]
        C[Generate timetable draft]
        D[Perform clash check]
        E[Alert to revise timetable]
        F[Generate display table: paper name, type, date, time, student count]
    end

    %% Flow connections
    A --> B --> C --> D
    D -->|Clash Found| E --> B
    D -->|No Clash| F --> G --> H
```

