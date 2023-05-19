```mermaid
        graph TD
        A[*] --> B[Load Balancer]
        B --> C[Server01]
        B --> D[Server02]
        C --> E[*]
        D --> E[*]
        E[*] --> F
        E[*] --> G
```