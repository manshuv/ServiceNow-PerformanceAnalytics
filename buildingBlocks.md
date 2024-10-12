```mermaid
graph TD;
    A[Indicator Source] --> B[Indicator]
    B --> C[Scheduled Job]
    B --> D[Widget]
    D --> E[Dashboard]
