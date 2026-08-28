\# Navigation Structure and User Flow



\## Purpose



The purpose of this document is to define how users will move between the main screens of the prototype. A clear navigation structure helps prevent unnecessary steps and keeps the interface easy to understand.



\## Citizen Navigation



After login, the citizen will mainly use the following navigation:



Dashboard  

→ Report New Issue  

→ My Requests  

→ Track Request  

→ Notifications  

→ Profile



The Citizen Dashboard will act as the main starting point. The most important actions, Report New Issue and Track Request, should be easy to find without searching through menus.



\## Municipal Officer Navigation



After login, a municipal officer will mainly use:



Officer Dashboard  

→ Assigned Requests  

→ Request Details  

→ Update Status  

→ Add Progress Information  

→ Complete Request



The officer interface should focus on processing requests rather than showing unnecessary information.



\## Department Supervisor Navigation



The supervisor will mainly use:



Supervisor Dashboard  

→ Department Requests  

→ Delayed Requests  

→ Escalated Requests  

→ Workload Summary  

→ Performance Reports



The supervisor should be able to quickly identify requests that need attention.



\## System Administrator Navigation



The administrator will mainly use:



Administrator Dashboard  

→ Users and Roles  

→ Departments  

→ Service Categories  

→ Permissions  

→ Reports  

→ System Settings



The administrator interface should focus on system management rather than request processing.



\# Key User Flows



\## Flow 1: Citizen Submits a Service Request



1\. Citizen opens the platform.

2\. Citizen logs in.

3\. Citizen enters the Dashboard.

4\. Citizen selects Report New Issue.

5\. Citizen selects a service category.

6\. Citizen enters the issue title and description.

7\. Citizen provides the location.

8\. Citizen may upload a supporting photo.

9\. Citizen reviews the information.

10\. Citizen submits the request.

11\. The system displays a confirmation message.

12\. A unique tracking ID is generated.

13\. Citizen can go to Request Details or return to the Dashboard.



Flow:



Landing / Login  

→ Citizen Dashboard  

→ Report New Issue  

→ Enter Request Details  

→ Submit  

→ Confirmation + Tracking ID



\## Flow 2: Citizen Tracks a Request



1\. Citizen opens My Requests or selects Track Request.

2\. Citizen selects the required service request.

3\. The Request Details screen opens.

4\. Citizen can see the current status.

5\. Citizen can see the responsible department.

6\. Citizen can view progress updates.

7\. If the request is delayed, the delay information is shown.

8\. When resolved, resolution details become available.



Flow:



Citizen Dashboard  

→ My Requests  

→ Select Request  

→ Request Details / Tracking  

→ View Status and Progress



\## Flow 3: Citizen Provides Feedback



1\. A request is marked as resolved.

2\. Citizen receives a notification.

3\. Citizen opens the resolved request.

4\. Citizen selects Provide Feedback.

5\. Citizen gives a rating and optional comment.

6\. Citizen submits the feedback.



Flow:



Resolution Notification  

→ Request Details  

→ Provide Feedback  

→ Feedback Submitted



\## Flow 4: Municipal Officer Processes a Request



1\. Officer logs in.

2\. Officer enters the Officer Dashboard.

3\. Officer opens an assigned request.

4\. Officer reviews the request information.

5\. Officer checks the category, description, location, and supporting evidence.

6\. Officer assigns the request to the appropriate field team when required.

7\. Officer updates the request status.

8\. Officer adds progress notes during processing.

9\. If delayed, the officer records the delay reason.

10\. After completing the work, the officer adds resolution details and supporting evidence.

11\. The request is marked as resolved.



Flow:



Officer Dashboard  

→ Assigned Request  

→ Review Details  

→ Assign / Process  

→ Update Progress  

→ Add Resolution Details  

→ Mark Resolved



\## Flow 5: Supervisor Reviews a Delayed Request



1\. Supervisor logs in.

2\. Supervisor opens the Supervisor Dashboard.

3\. Supervisor views delayed or escalated requests.

4\. Supervisor selects a request.

5\. Supervisor reviews the delay reason and previous updates.

6\. Supervisor checks the assigned officer or field team.

7\. Supervisor adds a note or takes the required action.

8\. The request continues through the processing workflow.



Flow:



Supervisor Dashboard  

→ Delayed / Escalated Requests  

→ Select Request  

→ Review Details  

→ Supervisor Action



\## Flow 6: Administrator Manages System Information



1\. Administrator logs in.

2\. Administrator enters the Administrator Dashboard.

3\. Administrator selects the required management area.

4\. Administrator can manage users, departments, service categories, or permissions.

5\. Changes are saved in the system.



Flow:



Administrator Dashboard  

→ Management Area  

→ Add / Update / Manage Information  

→ Save Changes



\## Navigation Design Considerations



The prototype navigation will follow these principles:



\- Important actions should require as few steps as possible.

\- The Dashboard should act as the main starting point after login.

\- Navigation labels should use simple and familiar words.

\- Users should always know which screen they are currently viewing.

\- A consistent navigation structure should be used across related screens.

\- Important actions such as Submit, Save, Update Status, and Provide Feedback should be clearly visible.

\- Users should be able to return to the Dashboard without restarting the process.

\- Error messages should not force users to re-enter all previously provided information.

