# My-first-project
Code-flowchart conversion
```mermaid
graph TB
    A[Create timetables]:::fit --> B[Check for exam clashes]:::fit
    B --> C[Display schedule details]:::partial
    C --> D[Attach question paper to timetable]:::gap
    D --> E[Prevent duplicate question papers]:::gap

    classDef fit fill="#bbf7d0",stroke="#15803d",stroke-width=2px,color="#064e3b";
    classDef partial fill="#fef9c3",stroke="#ca8a04",stroke-width=2px,color="#713f12";
    classDef gap fill="#fecaca",stroke="#b91c1c",stroke-width=2px,color="#7f1d1d";
```

