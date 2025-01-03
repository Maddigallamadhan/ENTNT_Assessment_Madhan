# **Calendar Application for Communication Tracking**

![Screenshot 2025-01-02 021738](https://github.com/user-attachments/assets/61ca0c1f-269d-4f05-b446-9cadf32a3f0f)
![Screenshot 2025-01-02 021755](https://github.com/user-attachments/assets/7cc6a479-19a2-469a-a2c4-7500d906f66a)
![Screenshot 2025-01-02 021825](https://github.com/user-attachments/assets/7919fa59-11eb-4d30-82d4-9228e0fb769e)
![Screenshot 2025-01-02 021858](https://github.com/user-attachments/assets/f3f59517-1c3c-411c-86f4-088852bc11ce)
![Screenshot 2025-01-02 021930](https://github.com/user-attachments/assets/41bfdcdd-4445-41b7-934e-9db8e62e8c76)



## **Overview**
This **React-based Calendar Application** is designed to help organizations efficiently manage and track their communication with other companies. It centralizes the process of planning, logging, and analyzing interactions, ensuring timely follow-ups and maintaining strong professional relationships.

## **Features**

### **1. Admin Module**
The Admin Module allows administrators to configure the application and manage foundational data.

#### **Company Management**
Admins can:
- Add, edit, and delete company details.
- Each company entry includes:
  - **Name**: Company name.
  - **Location**: Physical or operational location.
  - **LinkedIn Profile**: Link to the company’s LinkedIn page.
  - **Emails**: One or more email addresses.
  - **Phone Numbers**: Contact details.
  - **Comments**: Notes or additional information.
  - **Communication Periodicity**: Default interval for scheduled communication (e.g., every 2 weeks).

#### **Communication Method Management**
Admins can define and manage communication methods:
- **Fields**:
  - **Name**: E.g., "Visit" or "LinkedIn Post."
  - **Description**: E.g., "Visit to company premises."
  - **Sequence**: Determines the order of communication (e.g., LinkedIn Post → LinkedIn Message → Email).
  - **Mandatory Flag**: Marks if the method is required in the sequence.
- **Default Methods** (in order):
  1. LinkedIn Post  
  2. LinkedIn Message  
  3. Email  
  4. Phone Call  
  5. Other  

---

### **2. User Module**
The User Module is the primary interface for tracking and logging communication.

#### **Dashboard**
- **Grid View**: Displays company details:
  - **Company Name**: Name of the company.
  - **Last Five Communications**: Summary of the five most recent communications (type and date).
  - **Next Scheduled Communication**: Upcoming communication (type and date).
- **Color-Coded Highlights**:
  - **Red**: Overdue communication.
  - **Yellow**: Communication due today.
  - Users can override or disable highlights as needed.
- **Interactive Hover Effect**: Displays notes or comments for completed communications.

#### **Communication Actions**
- **Log Communication**:
  - Select one or multiple companies.
  - Input details (communication type, date, and notes).
  - Reset overdue or due highlights after submission.

#### **Notifications**
- **Overdue Communications Grid**: Lists companies with overdue tasks.
- **Today’s Communications Grid**: Shows tasks due today.
- **Notification Badge**: Displays a count of overdue and due communications.

#### **Calendar View**
- **Past Communications**: Displays dates and methods of completed interactions.
- **Upcoming Communications**: Schedule and manage future tasks.

---

### **3. Reporting and Analytics Module** *(Optional)*
Offers insights into communication activities and trends.

#### **Key Features**
- **Communication Frequency Report**:
  - Visual representation (e.g., bar chart or pie chart) of communication methods used.
  - Filters: Company, date range, and method.
- **Engagement Effectiveness Dashboard**:
  - Tracks response rates for emails, phone calls, and LinkedIn messages.
- **Overdue Communication Trends**:
  - Displays trends (e.g., heatmaps) of overdue tasks by company.
- **Downloadable Reports**:
  - Export data in PDF or CSV format.
- **Real-Time Activity Log**:
  - Live feed of communication activities.

---

## **Objective**
This application ensures seamless communication management, timely follow-ups, and actionable insights, empowering organizations to strengthen and sustain professional relationships.

---

## **Tech Stack**
- **Frontend**: React.js
- **Backend**: Node.js (Optional)
- **Database**: MongoDB or PostgreSQL (Optional)
- **Styling**: CSS/Bootstrap

## **Getting Started**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/calendar-communication-tracking.git
