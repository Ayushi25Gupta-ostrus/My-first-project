# My-first-project
Code-flowchart conversion
flowchart TD
    A([Start]) --> B[Input Examination Details]
    B --> C[Clash Detection]
    C -->|Conflict Exists| D[Prompt Admin to Adjust Schedule]
    D --> C
    C -->|No Conflict| E[Timetable Generation]
    E --> F[Display Timetable & Export Options]
    F --> G([End])

    subgraph Input Details
        B
    end
    subgraph Conflict Resolution
        C --> D
    end
    subgraph Output
        E --> F
    end

