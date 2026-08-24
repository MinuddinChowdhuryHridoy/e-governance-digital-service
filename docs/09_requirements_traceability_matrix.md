\# Requirements Traceability Matrix



\## Purpose



The Requirements Traceability Matrix connects each system requirement with the stakeholder who needs it, the related system module, the planned design element, and a test case. This helps make sure that every important requirement is considered during design and can later be tested during development.



\## Traceability Matrix



| ID    | Requirement                    | Stakeholder | Module                     | Design Element                   | Proposed Test Case                                                       |

| ----- | ------------------------------ | ----------- | -------------------------- | -------------------------------- | ------------------------------------------------------------------------ |

| FR-01 | Citizen registration and login | Citizen     | User Management            | Registration and Login Interface | Verify that a citizen can create an account and log in successfully      |

| FR-02 | Submit service request         | Citizen     | Service Request Management | Service Request Form             | Verify that a citizen can submit a request with valid information        |

| FR-03 | Provide issue location         | Citizen     | Service Request Management | Address / Map Location Input     | Verify that a citizen can provide the location of an issue               |

| FR-04 | Upload supporting photo        | Citizen     | Service Request Management | Photo Upload Option              | Verify that a supported image can be attached to a request               |

| FR-05 | Generate tracking ID           | Citizen     | Tracking                   | Tracking ID Generator            | Verify that every submitted request receives a unique tracking ID        |

| FR-06 | Track request status           | Citizen     | Tracking and Notification  | Request Status Page              | Verify that a citizen can view the current status of a submitted request |

| FR-07 | View responsible department | Citizen | Tracking and Notification | Request Details Page | Verify that the responsible department is shown for an assigned request |

| FR-08 | View expected resolution time | Citizen | Tracking and Notification | Request Details Page | Verify that the expected resolution time is displayed when available |

| FR-09 | Receive request notifications | Citizen | Tracking and Notification | Notification System | Verify that the citizen receives a notification after an important request update |

| FR-10 | View resolution details | Citizen | Service Request Management | Resolution Details Section | Verify that the citizen can view the final resolution information after completion |

| FR-11 | Provide feedback | Citizen | Feedback Management | Feedback Form | Verify that a citizen can submit feedback after a request is resolved |

| FR-12 | View related reports | Citizen | Service Request Management | Related Request Suggestion | Verify that the system can show a related existing report when a similar issue is identified |

| FR-13 | View assigned requests | Municipal Officer | Request Processing | Officer Request Dashboard | Verify that an officer can view requests assigned to them or their department |

| FR-14 | Review request details | Municipal Officer | Request Processing | Request Details Page | Verify that an officer can view category, description, location, photo, submission time, and status |

| FR-15 | Assign request | Municipal Officer | Request Processing | Request Assignment Interface | Verify that an authorized officer can assign a request to the appropriate department or field team |

| FR-16 | Update request status | Municipal Officer | Request Processing | Status Update Control | Verify that an officer can change a request status to a valid processing stage |

| FR-17 | Add progress notes | Municipal Officer | Request Processing | Progress Update Section | Verify that an officer can add and save progress notes for a request |

| FR-18 | Record delay reason | Municipal Officer | Request Processing | Delay Reason Field | Verify that an officer can record a reason when a request is delayed |

| FR-19 | Update expected resolution time | Municipal Officer | Request Processing | Resolution Time Update Field | Verify that an authorized officer can update the expected resolution time |

| FR-20 | Handle related reports | Municipal Officer | Service Request Management | Related Request Management | Verify that an officer can identify and link reports related to the same issue |

| FR-21 | Add resolution evidence | Municipal Officer | Request Processing | Resolution Form and Evidence Upload | Verify that an officer can add resolution details and supporting evidence before completing a request |

| FR-22 | View department requests | Department Supervisor | Reporting and Monitoring | Department Dashboard | Verify that a supervisor can view all requests handled by their department |

| FR-23 | Monitor request progress | Department Supervisor | Reporting and Monitoring | Request Monitoring Dashboard | Verify that pending, active, delayed, and completed requests are displayed correctly |

| FR-24 | Review escalated requests | Department Supervisor | Escalation Management | Escalated Request List | Verify that a supervisor can view and review escalated requests |

| FR-25 | Monitor workload | Department Supervisor | Reporting and Monitoring | Workload Summary | Verify that the supervisor can see the number of requests assigned to officers or field teams |

| FR-26 | View performance reports | Department Supervisor | Reporting and Monitoring | Department Report Page | Verify that the supervisor can view basic performance information such as completed requests, delayed requests, and average resolution time |

| FR-27 | Manage user accounts | System Administrator | Administration | User Management Panel | Verify that an administrator can create, update, and deactivate user accounts |

| FR-28 | Manage user roles | System Administrator | Administration | Role and Permission Management | Verify that an administrator can assign valid roles and permissions to users |

| FR-29 | Manage departments | System Administrator | Administration | Department Management Page | Verify that an administrator can add, update, and remove department information |

| FR-30 | Manage service categories | System Administrator | Administration | Service Category Management Page | Verify that an administrator can create, update, and remove service categories |

| FR-31 | Monitor system activity | System Administrator | Administration | Activity Log | Verify that authorized administrators can view recorded important system activities |

| FR-32 | Manage system settings | System Administrator | Administration | System Settings Page | Verify that an administrator can update permitted system settings |

| FR-33 | View overall reports | System Administrator | Reporting and Monitoring | System Report Dashboard | Verify that an administrator can view overall request and department statistics |

| NFR-01 | Protect accounts and sensitive information | All Users | Security | Authentication and Access Control | Verify that unauthorized users cannot access protected system features |

| NFR-02 | Protect personal and location information | Citizen / Staff | Security and Privacy | Role-Based Data Access | Verify that private citizen information is visible only to authorized users |

| NFR-03 | Provide a simple and clear interface | All Users | User Interface | Simple Navigation and Forms | Verify that users can complete common tasks without unnecessary steps |

| NFR-04 | Provide reasonable system response time | All Users | System Performance | Optimized API and Database Operations | Verify that common pages and actions respond within an acceptable time |

| NFR-05 | Maintain system availability | All Users | System Infrastructure | Application Server and Monitoring | Verify that the system remains accessible during normal operating conditions |

| NFR-06 | Support accessibility needs | Citizen | User Interface | Accessible Interface Design | Verify that important features can be used with clear text, labels, and accessible navigation |

| NFR-07 | Support mobile and desktop devices | All Users | User Interface | Responsive Web Design | Verify that the main features work properly on mobile and desktop screen sizes |

| NFR-08 | Protect against important data loss | System Administrator | Data Management | Database Backup Mechanism | Verify that system data can be backed up and recovered successfully |

| NFR-09 | Support growth in users and requests | System Administrator | System Architecture | Scalable Application Structure | Verify that the system can continue operating when the number of requests increases |

| NFR-10 | Maintain records of important actions | Municipal Staff / Administrator | Audit and Monitoring | Activity and Status History Log | Verify that important actions such as assignment and status changes are recorded |

