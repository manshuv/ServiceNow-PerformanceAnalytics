```mermaid
graph TD;
     A[Indicator Source] --> B[Indicator]
    B --> C[Scheduled Job]
    B --> D[Widget]
    D --> E[Dashboard]
    
    subgraph Performance Analytics Report
        A --> B --> C --> D --> E
    end

    style A fill:#62D84E,stroke:#032D42,stroke-width:2px
    style B fill:#24C2CE,stroke:#032D42,stroke-width:2px
    style C fill:#FFDE1D,stroke:#032D42,stroke-width:2px
    style D fill:#5274FF,stroke:#032D42,stroke-width:2px
    style E fill:#FC7786,stroke:#032D42,stroke-width:2px
