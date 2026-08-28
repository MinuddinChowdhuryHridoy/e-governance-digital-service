\# Design Rationale and Screen Annotations



\## Purpose



This document explains the purpose of the main prototype screens, the important interface elements on each screen, and the reasons behind the design decisions.



The design decisions are based on the requirements identified during Week 1 and the UI/UX research completed during Week 2. Each important screen is explained using four points:



\- Problem being addressed

\- Design decision

\- Example of use

\- User experience benefit



\## M01 — Landing / Login Screen



\### Problem Being Addressed



Citizens need a clear starting point where they can access the service without being confused by unnecessary options. Existing users need to log in, while new users need a clear registration option.



\### Design Decision



The landing screen gives high visibility to the main citizen actions and keeps the login form simple. Citizen access is separated from staff access so that normal users are not distracted by administrative functions.



\### Example of Use



A citizen who wants to report a broken streetlight can open the platform, log in or create an account, and then continue to the reporting process. A returning citizen can also access request tracking without searching through several menus.



\### UX Benefit



The simple layout reduces unnecessary navigation and makes the main actions easier to identify. Clear form labels also reduce the chance of input mistakes.



\## M02 — Citizen Dashboard



\### Problem Being Addressed



After logging in, citizens need one place where they can quickly understand the condition of their submitted requests. Without a clear dashboard, users may have to open several pages just to check whether a request is pending, in progress, delayed, or resolved.



\### Design Decision



The Citizen Dashboard places the most important actions and request information on one screen. The design gives high visibility to Report New Issue, Track Request, recent requests, request-status summaries, notifications, and help options.



The dashboard avoids unnecessary charts or technical information that would not help a normal citizen complete their main tasks.



\### Example of Use



A citizen previously reported a drainage problem and now wants to know what happened. After logging in, the dashboard immediately shows that the request is In Progress. The citizen can select View Details to see the responsible department, progress updates, and expected resolution information.



The same citizen can also use Report New Issue to submit another municipal problem without searching through additional menus.



\### UX Benefit



The dashboard reduces the number of steps required to perform common tasks. Important actions are visible immediately, while recent requests and status information help citizens understand what is happening without needing technical knowledge.



Using clear status text such as Submitted, In Progress, Delayed, and Resolved also ensures that users do not have to depend only on color to understand request progress.

\## M03 — Submit Service Request



\### Problem Being Addressed



Municipal complaints can be difficult to process when the submitted information is incomplete, unclear, or missing important details such as the issue type or location. Citizens may also be unsure about what information they need to provide.



\### Design Decision



The request form is divided into clear fields such as service category, issue title, description, location, priority, and optional supporting photo. Required fields are clearly identified, while supporting evidence remains optional so that citizens without a suitable photo can still submit a request.



The form also uses simple labels and validation messages so that users can correct missing or incorrect information before submission.



\### Example of Use



A citizen wants to report a pothole on a local road. The citizen selects Road Services, writes a short title, explains the problem, enters the location, and attaches a photo of the damaged road. If the location field is left empty, the system shows a validation message near that field instead of clearing the entire form.



\### UX Benefit



The structured form helps citizens provide more useful information and reduces the chance of incomplete requests reaching municipal officers. Keeping optional evidence separate from required information also makes the service accessible to users who may not have a photo available.



The design also reduces repeated data entry because previously entered information should remain in the form when a validation error occurs.

\## M04 — Request Submission Confirmation



\### Problem Being Addressed



After submitting a service request, citizens need clear confirmation that the request was received successfully. Without this confirmation, users may submit the same complaint again or remain unsure whether the system recorded it.



\### Design Decision



The confirmation screen displays a success message, unique tracking ID, request summary, current status, and clear next-step options such as View Request Details and Return to Dashboard.



\### Example of Use



A citizen submits a waste collection complaint. The system confirms the submission and generates a tracking ID such as REQ-2025-05-000123. The citizen can save this number and use it later to check progress.



\### UX Benefit



Immediate confirmation reduces uncertainty and duplicate submissions. Showing the tracking ID prominently gives citizens a clear reference for future communication and tracking.





\## M05 — My Requests



\### Problem Being Addressed



Citizens who submit several service requests need an easy way to find and compare them without entering individual tracking numbers repeatedly.



\### Design Decision



The My Requests screen presents submitted requests in a structured list or table. Users can search by tracking ID or issue and filter requests by status such as Submitted, In Progress, Delayed, or Resolved.



\### Example of Use



A citizen has previously reported a pothole, drainage problem, and broken streetlight. Instead of searching for three separate tracking IDs, the citizen opens My Requests and sees the status of all three complaints in one place.



\### UX Benefit



Centralizing requests reduces navigation effort and makes the service history easier to understand. Search and filtering also help users quickly locate a specific complaint when many requests exist.





\## M06 — Request Details / Tracking



\### Problem Being Addressed



One of the main problems identified during requirement analysis is the lack of transparency after a citizen submits a complaint. Citizens may not know what stage the request has reached or why progress has stopped.



\### Design Decision



The tracking screen shows the tracking ID, request information, responsible department, current status, progress history, expected resolution information, and delay reason when applicable.



A visual progress timeline is included so that users can understand the request lifecycle without reading large amounts of text.



\### Example of Use



A citizen checks a previously reported pothole complaint. The screen shows that the request was submitted, reviewed, assigned to the Roads Department, and is currently In Progress. If work is delayed, the recorded reason is also displayed.



\### UX Benefit



Providing a clear progress history improves transparency and reduces the need for citizens to repeatedly contact municipal offices for updates. Text labels are used together with visual status indicators so that information does not depend only on color.





\## M07 — Feedback



\### Problem Being Addressed



After a service request is completed, municipal authorities need a simple way to understand whether citizens were satisfied with how the issue was handled.



\### Design Decision



The feedback screen is available after resolution and allows the citizen to select the related request, provide a service rating, and add an optional comment.



\### Example of Use



After a broken streetlight has been repaired, the citizen opens the resolved request and gives a rating of four out of five with a short comment explaining that the repair was successful but took longer than expected.



\### UX Benefit



A short feedback form makes participation easier and avoids forcing citizens to complete a long survey. Linking feedback to a specific resolved request also makes the information more useful for future service evaluation.





\## M08 — Municipal Officer Dashboard



\### Problem Being Addressed



Municipal officers may need to manage many requests at the same time. Without an organized dashboard, delayed or high-priority requests can be difficult to identify.



\### Design Decision



The officer dashboard provides summaries of assigned, pending, in-progress, delayed, and resolved requests. A searchable and filterable request table allows officers to quickly open the cases that require attention.



\### Example of Use



An officer begins the workday and sees 12 assigned requests, including two delayed cases. The officer filters the list by Delayed and immediately opens the oldest request for review.



\### UX Benefit



The dashboard reduces the time required to find important cases and supports better workload organization. Status summaries also help officers understand their current responsibilities without opening every request individually.





\## M09 — Officer Request Processing



\### Problem Being Addressed



Officers need more than a request viewer. They require a working interface where they can review information, assign tasks, record progress, explain delays, and complete requests.



\### Design Decision



The processing screen combines citizen-submitted information with operational controls. Officers can review the request details and evidence, assign a field team, change the status, add progress notes, record delay reasons, update the expected completion time, and attach resolution evidence.



\### Example of Use



An officer opens a road-damage request, verifies the submitted location and photo, assigns the request to a road maintenance team, changes the status to In Progress, and adds a progress note. After repair work is completed, the officer uploads a completion photo and marks the request as Resolved.



\### UX Benefit



Keeping all important processing actions on one screen reduces unnecessary navigation and helps maintain a complete service history. Structured updates also provide citizens and supervisors with clearer information about how a request is being handled.





\## M10 — Supervisor Dashboard



\### Problem Being Addressed



Department supervisors need to monitor overall department performance rather than only individual requests. They must be able to quickly identify delays, workload problems, and requests requiring attention.



\### Design Decision



The supervisor dashboard presents department-level summaries such as active, pending, delayed, escalated, and resolved requests. It also includes officer or team workload information and basic performance indicators.



\### Example of Use



A supervisor notices that the Drainage Team has significantly more active requests than another team and that several cases have become overdue. The supervisor can open those cases and review whether reassignment or another action is needed.



\### UX Benefit



The dashboard supports quicker operational decisions by presenting important department information in one place. It also helps supervisors identify workload imbalance and delayed cases before they become more serious.





\## M11 — Escalated Request Review



\### Problem Being Addressed



Some requests cannot be completed within the expected time or may require management attention. Supervisors need sufficient information to understand why the request was escalated before taking action.



\### Design Decision



The escalated request screen shows the full request details, delay reason, previous status changes, assigned officer or team, escalation history, and previous progress notes. Supervisor actions can include adding instructions, requesting an update, changing priority, or reassigning the work.



\### Example of Use



A waste collection request has remained unresolved beyond its expected completion time. The supervisor reviews the officer's delay note and discovers that the assigned team is unavailable. The supervisor reassigns the case to another team and adds an instruction explaining the change.



\### UX Benefit



Providing the complete history before showing management actions supports informed decisions and reduces unnecessary reassignment. The interface also creates a clear record of why a supervisor changed the handling of a request.





\## M12 — Administrator Dashboard



\### Problem Being Addressed



System administrators need an overall view of the platform to manage users, departments, service categories, and system activity effectively.



\### Design Decision



The administrator dashboard provides high-level information such as total users, departments, service categories, request volumes, status summaries, and recent system activity. It also provides shortcuts to the main management functions.



\### Example of Use



An administrator sees that a newly created municipal department has not yet been linked with any service category. From the dashboard, the administrator opens department management and updates the required configuration.



\### UX Benefit



The dashboard provides a quick understanding of the overall system without requiring the administrator to open multiple management pages. Important management areas remain accessible from a consistent navigation structure.





\## M13 — Management Screen



\### Problem Being Addressed



The platform needs a controlled way to maintain user roles, departments, service categories, permissions, and basic system settings as municipal services change over time.



\### Design Decision



The management screen groups administrative functions into clearly separated areas. Administrators can manage users and roles, update departments, maintain service categories, configure permissions, and adjust approved platform settings.



\### Example of Use



A municipality introduces a new Tree Maintenance service. The administrator creates the new service category, connects it to the responsible department, and confirms which staff roles are allowed to manage requests in that category.



\### UX Benefit



Centralized administration reduces configuration errors and makes system maintenance easier. Role-based controls also help prevent unauthorized users from changing important system information.





\## Overall Design Rationale



The prototype was designed around the main problems identified during the requirements analysis rather than adding features only for visual appearance. Citizen screens focus on simple reporting, request visibility, and communication after submission. Staff screens focus on request processing, workload management, escalation, and administration.



The design also follows several common usability principles:



\- Important actions are placed where users can identify them quickly.

\- Navigation remains consistent between screens.

\- Forms use clear labels instead of relying only on placeholder text.

\- Required and optional information are visually distinguished.

\- Status information uses text as well as visual indicators.

\- Error messages should appear close to the related form field.

\- Previously entered information should remain available after a validation error.

\- Tables include search and filtering when users may need to manage many records.

\- Different user roles receive interfaces based on their responsibilities.

\- Sensitive citizen information should only be visible to authorized staff.

\- Main workflows are designed to remain usable on desktop and mobile layouts.

