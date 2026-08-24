\# System Architecture



\## Architecture Overview



The proposed system will follow a simple client-server architecture. Citizens and municipal staff will access the system through a web application. The frontend will communicate with the backend through APIs, while the backend will handle the main business logic and store information in the database.



\## Main Components



\### 1. Frontend Application



The frontend will provide different interfaces based on the user's role.



\* Citizens can submit and track service requests.

\* Municipal officers can review and update requests.

\* Supervisors can monitor department activities.

\* Administrators can manage users, departments, and system settings.



\### 2. Backend / API



The backend will receive requests from the frontend and handle the main system operations. It will manage authentication, service-request processing, status updates, user permissions, notifications, and reporting.



\### 3. Database



The database will store information such as:



\* User accounts

\* Service requests

\* Departments

\* Request status history

\* Uploaded file information

\* Feedback

\* Notifications

\* System activity records



\### 4. File Storage



Photos and other supporting evidence submitted by citizens or municipal officers will be stored separately, while their references will be kept in the database.



\### 5. Notification Service



The notification component will inform citizens about important changes in their requests, such as assignment, progress updates, delays, and resolution.



\## Basic Architecture Flow



Citizen / Officer / Supervisor / Administrator

↓

Web Application

↓

Backend / REST API

↓

Database and File Storage

↓

Notification Service



The architecture keeps the user interface, system logic, and stored data separated. This makes the system easier to develop, maintain, and expand later.



