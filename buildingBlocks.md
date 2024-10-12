```mermaid
graph TD;
  E[Dashboard] --> D[Widget]
    D --> B[Indicator]
    B --> A[Indicator Source]
    C[Scheduled Job] --> B
    
