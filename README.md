#   Calendar Application for Communication Tracking

![Screenshot 2025-01-02 021738](https://github.com/user-attachments/assets/61ca0c1f-269d-4f05-b446-9cadf32a3f0f)
![Screenshot 2025-01-02 021755](https://github.com/user-attachments/assets/7cc6a479-19a2-469a-a2c4-7500d906f66a)
![Screenshot 2025-01-02 021825](https://github.com/user-attachments/assets/7919fa59-11eb-4d30-82d4-9228e0fb769e)
![Screenshot 2025-01-02 021858](https://github.com/user-attachments/assets/f3f59517-1c3c-411c-86f4-088852bc11ce)
![Screenshot 2025-01-02 021930](https://github.com/user-attachments/assets/41bfdcdd-4445-41b7-934e-9db8e62e8c76)

The goal is to develop a React-based Calendar Application that helps the company efficiently track and manage communications with other organizations. The application will ensure timely follow-ups, maintain professional relationships, and provide a centralized system for planning and logging interactions. Key features include an Admin Module, a User Module, and an optional Reporting and Analytics Module to offer actionable insights.

Application Features
1. Admin Module
The Admin Module focuses on setting up and managing foundational data.

a. Company Management Admins can add, edit, and delete company details. Each entry includes:

Name: Company name.
Location: Operational or physical location.
LinkedIn Profile: Link to the company’s LinkedIn page.
Emails: One or more email addresses.
Phone Numbers: Contact details for representatives.
Comments: Notes or additional information about the company.
Communication Periodicity: Default time interval for scheduled communications (e.g., every two weeks).
b. Communication Method Management Admins can define and manage available communication methods. Each method includes:

Name: For example, "Visit" or "LinkedIn Post."
Description: A brief explanation, e.g., "Visit to company premises."
Sequence: Defines the order of communication (e.g., LinkedIn Post → LinkedIn Message → Email → Phone Call → Other).
Mandatory Flag: Marks whether the communication method is mandatory in the sequence.
Default Communication Methods (in sequence):

LinkedIn Post
LinkedIn Message
Email
Phone Call
Other
2. User Module
The User Module serves as the primary interface for users to view, manage, and log communications.

a. Dashboard The dashboard provides a grid view where each row represents a company. Key columns include:

Company Name: Name of the company.
Last Five Communications: Summary of the five most recent communications (type and date).
Next Scheduled Communication: Type and date of the next planned communication.
Color-Coded Highlights:

Red: Indicates overdue communication.
Yellow: Communication due today.
Users can disable or override these highlights for specific companies or tasks.
Interactive Features:

Hover Effect: Displays notes or comments on completed communications when hovered over.
b. Communication Actions

Single or Multi-Selection: Users can select one or multiple companies.
Action Modal: Log a new communication by:
Selecting the type (e.g., LinkedIn Post, Email).
Inputting the communication date.
Adding notes or comments.
Submitting the action resets any overdue or due highlights for the selected company/companies.
c. Notifications A dedicated section highlights overdue and due communications:

Overdue Communications Grid: Lists companies with overdue tasks.
Today’s Communications Grid: Displays tasks due today.
Notification Badge: Shows the count of overdue and due communications.
d. Calendar View

View Past Communications: Displays dates and methods of previous interactions.
Manage Upcoming Communications: Allows scheduling and editing future communication plans.
3. Reporting and Analytics Module (Optional)
This module offers insights and metrics related to communication activities.

Key Features:

Communication Frequency Report: Visual representation (e.g., bar chart or pie chart) of how often each communication method is used, with filters for company, date range, and method.
Engagement Effectiveness Dashboard: Tracks the success of various communication methods (e.g., response rates for emails or phone calls).
Overdue Communication Trends: Displays trends or heatmaps for overdue tasks over time, categorized by company.
Downloadable Reports: Allows exporting data in PDF or CSV format.
Real-Time Activity Log: Live feed of all communication activities, sortable by date, user, or company.
Objective
This tool ensures seamless communication management, timely follow-ups, and actionable insights, empowering the company to build and sustain professional relationships effectively.
