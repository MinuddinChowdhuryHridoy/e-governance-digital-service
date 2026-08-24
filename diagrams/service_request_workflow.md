\# Service Request Workflow Diagram



```mermaid

flowchart TD



&#x20;   A\[Citizen Submits Service Request]

&#x20;   B\[System Generates Tracking ID]

&#x20;   C\[Municipal Officer Reviews Request]

&#x20;   D{Is Information Sufficient?}

&#x20;   E\[Request Sent Back for Additional Information]

&#x20;   F\[Assign Responsible Department]

&#x20;   G\[Assign Officer / Field Team]

&#x20;   H\[Work In Progress]

&#x20;   I{Completed Within Expected Time?}

&#x20;   J\[Record Delay Reason]

&#x20;   K\[Escalate for Supervisor Review]

&#x20;   L\[Add Resolution Details and Evidence]

&#x20;   M\[Mark Request as Resolved]

&#x20;   N\[Notify Citizen]

&#x20;   O\[Citizen Provides Feedback]



&#x20;   A --> B

&#x20;   B --> C

&#x20;   C --> D



&#x20;   D -- No --> E

&#x20;   E --> C



&#x20;   D -- Yes --> F

&#x20;   F --> G

&#x20;   G --> H



&#x20;   H --> I



&#x20;   I -- No --> J

&#x20;   J --> K

&#x20;   K --> H



&#x20;   I -- Yes --> L

&#x20;   L --> M

&#x20;   M --> N

&#x20;   N --> O

