\# UX Considerations and Measurable Design Targets



\## Purpose



The purpose of this section is to define practical usability, accessibility, and interaction goals for the prototype. These targets are design goals for future implementation and testing rather than claims that the current prototype has already achieved them.



\## 1. Simple Navigation



The main citizen actions should be easy to find from the dashboard.



Proposed Target:

\- Report New Issue should be accessible directly from the Citizen Dashboard.

\- My Requests should be accessible within one navigation step.

\- Users should be able to return to the Dashboard from all major screens.



Example:

A citizen who wants to report a drainage problem should not need to open several menus before finding the request form.



\## 2. Request Submission Efficiency



The request form should collect enough information to help municipal officers while avoiding unnecessary fields.



Proposed Target:

\- The main request form should contain only essential required fields.

\- Supporting photos should remain optional.

\- Required fields should be clearly marked.

\- Validation errors should appear beside the related field.



Example:

If the citizen forgets to provide the issue location, the system should highlight only the location field and preserve the information already entered in the other fields.



\## 3. Clear Request Status



Citizens should be able to understand request progress without technical knowledge.



Proposed Status Labels:

\- Submitted

\- Under Review

\- Assigned

\- In Progress

\- Delayed

\- Resolved



Status information should use both text and visual indicators rather than color alone.



Example:

A delayed request should display the word "Delayed" together with the delay reason instead of relying only on an orange or red color.



\## 4. Tracking Transparency



Important request information should be available from the Request Details screen.



The screen should provide:

\- Tracking ID

\- Current status

\- Responsible department

\- Progress history

\- Expected resolution information when available

\- Delay reason when applicable

\- Resolution details after completion



Proposed Target:

A citizen should be able to understand the latest condition of a request from one details screen without contacting the municipal office for basic status information.



\## 5. Accessibility



The prototype should support users with different levels of digital experience and accessibility needs.



Proposed Design Targets:

\- Use readable font sizes.

\- Maintain sufficient contrast between text and background.

\- Use clear labels for form fields.

\- Avoid communicating information using color alone.

\- Keep buttons large enough to identify and select easily.

\- Use simple language instead of technical terms.

\- Support keyboard navigation during implementation where possible.



\## 6. Mobile Responsiveness



Citizens may access the service using smartphones as well as desktop computers.



Proposed Target:

The main citizen workflows should remain usable on common mobile and desktop screen sizes.



Priority mobile workflows:

\- Login

\- Submit Service Request

\- Track Request

\- View Request Details

\- Receive Notifications

\- Provide Feedback



\## 7. Error Prevention and Recovery



The system should help users avoid mistakes and recover from them without losing unnecessary work.



Proposed Design Targets:

\- Confirm important actions when needed.

\- Keep previously entered form data after validation errors.

\- Display understandable error messages.

\- Prevent unsupported file types from being uploaded.

\- Explain why a submission cannot continue when required information is missing.



\## 8. Role-Based Simplicity



Different users should only see the tools relevant to their responsibilities.



Citizen:

Focus on reporting, tracking, notifications, and feedback.



Municipal Officer:

Focus on assigned requests, status updates, progress notes, and resolution.



Department Supervisor:

Focus on delayed cases, escalations, workload, and performance.



System Administrator:

Focus on users, roles, departments, service categories, permissions, and settings.



This reduces unnecessary interface complexity for each user group.



\## 9. Feedback Efficiency



Citizens should be able to provide feedback without completing a long survey.



Proposed Target:

The feedback process should require only:

\- Related request

\- Rating

\- Optional comment



Example:

After a streetlight request is resolved, the citizen should be able to provide a rating and short comment within a single screen.



\## 10. Staff Workload Visibility



Municipal officers and supervisors need clear information about pending and delayed work.



Proposed Target:

Officer and supervisor dashboards should clearly display:

\- Assigned requests

\- Pending requests

\- In-progress requests

\- Delayed requests

\- Resolved requests



Supervisors should also be able to see workload by officer or field team.



\## 11. Consistency



The same design patterns should be reused throughout the platform.



Examples:

\- Primary actions should use a consistent button style.

\- Status labels should use consistent wording.

\- Navigation positions should remain similar across related screens.

\- Form fields should use the same label and validation style.

\- Similar tables should use consistent search and filtering controls.



Consistency can reduce the amount of learning required when users move between screens.



\## 12. Proposed Usability Evaluation



During future implementation, the following simple usability checks can be performed:



| Task | Proposed Usability Goal |

|---|---|

| Citizen logs in | Complete without assistance |

| Submit a service request | Complete without unnecessary navigation |

| Find a previous request | Locate through My Requests or tracking search |

| Understand current request status | Identify status from Request Details screen |

| Officer opens an assigned request | Reach processing screen directly from dashboard |

| Supervisor finds delayed cases | Identify them from dashboard or escalation list |

| Citizen gives feedback | Complete on a single feedback screen |



These goals can later be evaluated through usability testing with representative users.



\## Conclusion



The UX design focuses on clarity, transparency, accessibility, and task efficiency. The prototype avoids unnecessary features and gives priority to the tasks that citizens and municipal staff are most likely to perform. The measurable design targets provide a practical basis for future usability testing and implementation.

