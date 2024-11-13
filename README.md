graph TD
    subgraph "Level 1: Digital Literacy & Fundamentals"
        A1[Basic Computer Skills]
        A2[Problem Solving Basics]
        A3[Algorithm Building with Blocks]
        A1 --> A2 --> A3
    end

    subgraph "Level 2: Visual Programming"
        B1[Scratch Programming]
        B2[Game Creation]
        B3[Interactive Stories]
        A3 --> B1 --> B2
        B1 --> B3
    end

    subgraph "Level 3: Text-Based Programming"
        C1[Python Basics]
        C2[Simple Applications]
        C3[Data Structures]
        B2 --> C1
        B3 --> C1
        C1 --> C2 --> C3
    end

    subgraph "Level 4: Web Development"
        D1[HTML & CSS]
        D2[JavaScript Basics]
        D3[Simple Web Projects]
        C2 --> D1 --> D2 --> D3
    end

    subgraph "Level 5: Advanced Projects"
        E1[Personal Portfolio]
        E2[Team Projects]
        E3[Capstone Project]
        D3 --> E1 --> E2 --> E3
    end

    style A1 fill:#d0f4de
    style B1 fill:#a7e9af
    style C1 fill:#7fdfd4
    style D1 fill:#6dbfff
    style E1 fill:#8093f1

    classDef milestone fill:#ffd700,stroke:#ff8c00,stroke-width:2px
    class E3 milestone
