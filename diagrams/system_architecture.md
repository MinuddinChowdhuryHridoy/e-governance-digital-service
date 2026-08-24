\# System Architecture Diagram



```mermaid

flowchart TB



&#x20;   Citizen\[Citizen]

&#x20;   Officer\[Municipal Officer]

&#x20;   Supervisor\[Department Supervisor]

&#x20;   Admin\[System Administrator]



&#x20;   Frontend\[Web Application / Frontend]

&#x20;   Backend\[Backend / REST API]



&#x20;   Auth\[Authentication \& Access Control]

&#x20;   Request\[Service Request Management]

&#x20;   Notify\[Notification Service]

&#x20;   Report\[Reporting \& Monitoring]



&#x20;   Database\[(Database)]

&#x20;   Storage\[(Photo / File Storage)]



&#x20;   Citizen --> Frontend

&#x20;   Officer --> Frontend

&#x20;   Supervisor --> Frontend

&#x20;   Admin --> Frontend



&#x20;   Frontend --> Backend



&#x20;   Backend --> Auth

&#x20;   Backend --> Request

&#x20;   Backend --> Notify

&#x20;   Backend --> Report



&#x20;   Auth --> Database

&#x20;   Request --> Database

&#x20;   Request --> Storage

&#x20;   Report --> Database

&#x20;   Notify --> Database

