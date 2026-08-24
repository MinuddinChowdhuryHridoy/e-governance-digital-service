\# User Role and Use Case Diagram



```mermaid

flowchart LR



&#x20;   Citizen\[Citizen]

&#x20;   Officer\[Municipal Officer]

&#x20;   Supervisor\[Department Supervisor]

&#x20;   Admin\[System Administrator]



&#x20;   subgraph System\[Municipal Service Request System]



&#x20;       UC1\[Register / Login]

&#x20;       UC2\[Submit Service Request]

&#x20;       UC3\[Track Request]

&#x20;       UC4\[View Updates]

&#x20;       UC5\[Provide Feedback]



&#x20;       UC6\[View Assigned Requests]

&#x20;       UC7\[Review Request]

&#x20;       UC8\[Assign Request]

&#x20;       UC9\[Update Status]

&#x20;       UC10\[Add Resolution Details]



&#x20;       UC11\[Monitor Department Requests]

&#x20;       UC12\[Review Escalated Requests]

&#x20;       UC13\[View Performance Reports]



&#x20;       UC14\[Manage Users and Roles]

&#x20;       UC15\[Manage Departments]

&#x20;       UC16\[Manage Service Categories]

&#x20;       UC17\[View System Reports]

&#x20;   end



&#x20;   Citizen --> UC1

&#x20;   Citizen --> UC2

&#x20;   Citizen --> UC3

&#x20;   Citizen --> UC4

&#x20;   Citizen --> UC5



&#x20;   Officer --> UC1

&#x20;   Officer --> UC6

&#x20;   Officer --> UC7

&#x20;   Officer --> UC8

&#x20;   Officer --> UC9

&#x20;   Officer --> UC10



&#x20;   Supervisor --> UC1

&#x20;   Supervisor --> UC11

&#x20;   Supervisor --> UC12

&#x20;   Supervisor --> UC13



&#x20;   Admin --> UC1

&#x20;   Admin --> UC14

&#x20;   Admin --> UC15

&#x20;   Admin --> UC16

&#x20;   Admin --> UC17

