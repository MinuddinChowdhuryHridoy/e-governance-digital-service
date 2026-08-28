\# UI/UX Research



\## Purpose of the Research



Before creating the wireframes and final prototype, several existing government digital-service interfaces were reviewed. The purpose was to understand how real public-service platforms organize complaint submission, request tracking, navigation, forms, and feedback.



The goal is not to copy an existing interface. The useful design patterns will be adapted to our Municipal Citizen Service Request \& Complaint Management System.



\## NYC311



NYC311 provides citizens with access to different New York City services and allows users to submit and track service requests.



One important design idea is that major citizen actions are kept clear. Users can report problems, look up existing service requests, browse services, and search for information. For request tracking, users can enter a service request number and check its status. NYC311 also provides a map where service requests can be searched using location, date, and problem type.



Users who provide contact information can also receive request updates through email or SMS. An NYC311 account can be used to keep different submitted service requests together and manage notification preferences.



\### Design Lessons for Our System



\- Make "Report a Problem" and "Track Request" easy to find.

\- Keep request tracking simple.

\- Show submitted requests together on the citizen dashboard.

\- Provide clear request status information.

\- Allow users to receive important progress notifications.

\- Use location information as part of the reporting process.



\## Bangladesh Grievance Redress System (GRS)



Bangladesh GRS provides an online interface for submitting complaints about public services. Its complaint form collects structured information such as the complainant's details, responsible office or service, complaint subject, description, and attachments.



After submission, a tracking number is provided. Citizens can later check the complaint status using their mobile number and tracking number. The tracking interface can show information such as the complaint date, related service, current status, and expected resolution date.



After a complaint has been resolved, the system also provides an option for the citizen to submit a rating and comments.



\### Design Lessons for Our System



\- Give every submitted request a clear tracking ID.

\- Show status and expected resolution information together.

\- Keep the tracking form short and easy to understand.

\- Provide confirmation after successful submission.

\- Allow supporting evidence to be attached.

\- Provide feedback only after the request has been resolved.



\## Government UI/UX and Accessibility Guidance



The U.S. Web Design System (USWDS) was also reviewed because it provides design guidance for government digital services. It emphasizes designing around real user needs and making government interfaces accessible to a wide range of users.



Accessibility should be considered from the beginning rather than added at the end. Important information should be easy to understand, navigation should remain clear, and forms should have properly ordered fields and understandable labels.



Validation and error messages should also appear close to the field where the problem occurred. This makes it easier for users to understand what needs to be corrected.



\### Design Lessons for Our System



\- Use simple and understandable language.

\- Keep navigation consistent between screens.

\- Avoid unnecessarily complicated forms.

\- Use clear labels for every input field.

\- Show validation messages close to incorrect fields.

\- Maintain readable text and sufficient visual contrast.

\- Design the interface for both desktop and mobile screens.

\- Do not rely only on color to communicate important status information.



\## Design Direction for Our Prototype



Based on this research, the prototype will focus on simplicity, transparency, and ease of use.



The citizen interface will give high importance to two main actions: submitting a new service request and tracking an existing request. The dashboard will show recent requests and their current status without requiring the citizen to search through complicated menus.



The service-request form will collect information step by step, including service category, description, location, and optional supporting evidence. After submission, the citizen will receive a clear confirmation and tracking ID.



Municipal staff interfaces will be more task-focused. Officers will need quick access to assigned requests and status-update functions, while supervisors will need information about delayed and escalated requests. Administrator screens will focus on managing users, departments, service categories, and system settings.



The prototype will therefore use a consistent layout, clear navigation, readable typography, simple forms, understandable status information, and a restrained visual design suitable for a public-service platform.

