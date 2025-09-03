flowchart TD
    A[Inputs] --> B[Activities]
    B --> C[Outputs]
    C --> D[Outcomes]
    D --> E[Impacts]

    subgraph A1 [Inputs]
        A1a[EU funding & HEI commitment]
        A1b[Research Management expertise]
        A1c[SSH expertise]
        A1d[Technical expertise (AI, data)]
        A1e[Partnerships with SMEs, cities, health]
        A1f[Domain knowledge: Urban Planning, Mobility, Health]
    end
    A --> A1

    subgraph B1 [Activities]
        B1a[Institutional reforms (assessment, RMA)]
        B1b[Upskilling (training, mobility, Skills Academy)]
        B1c[Joint R&I agenda + seed DT projects]
        B1d[Digital transformation (AI, DTs paradigm)]
        B1e[Outreach & ecosystem engagement]
    end
    B --> B1

    subgraph C1 [Outputs]
        C1a[Research assessment frameworks & RMA practices]
        C1b[Skills curricula & mobility schemes]
        C1c[Joint R&I agenda in DTs]
        C1d[Pilot DT projects with ecosystems]
        C1e[Infrastructure catalogues & DT access protocols]
        C1f[Digital platforms for knowledge sharing]
    end
    C --> C1

    subgraph D1 [Outcomes]
        D1a[Modernised HEIs (DTs + RMA)]
        D1b[Stronger R&I capacity in DTs]
        D1c[Enhanced careers & attractiveness]
        D1d[Mainstreamed excellence culture]
        D1e[Improved internationalisation]
    end
    D --> D1

    subgraph E1 [Impacts]
        E1a[Societal: DT-informed policy tools]
        E1b[Scientific: critical mass in DTs]
        E1c[Policy: ERA & CoARA alignment]
        E1d[Economic: SMEs & innovation in DTs]
    end
    E --> E1

    %% Highlight transversal role of Digital Twins
    B -.->|Cross-cutting| DT[Digital Twins in Urban Planning, Mobility, Health]
    C -.-> DT
    D -.-> DT
    E -.-> DT
