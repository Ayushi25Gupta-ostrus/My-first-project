# My-first-project
Code-flowchart conversion
```mermaid
flowchart TB
    subgraph Fits[**FITS** ✅]
        F1([Timetable Creation - Manual & Automated]):::fit
        F2([Clash Detection for Students]):::fit
        F3([Attach Question Paper]):::fit
    end

    subgraph Gaps[**GAPS** ⚠️]
        G1([Display All Required Fields in Timetable View]):::gap
        G2([Validation for Unique Question Papers]):::gap
    end

    classDef fit fill:#d4f8d4,stroke:#228B22,stroke-width:2px,color:#000
    classDef gap fill:#f8d4d4,stroke:#B22222,stroke-width:2px,color:#000
