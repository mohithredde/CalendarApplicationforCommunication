# Calendar Application for Communication Tracking

## Objective

The **Calendar Application for Communication Tracking** is a React-based solution designed to help organizations manage and track their communications with external companies. It ensures timely follow-ups, consistent engagement, and actionable insights into communication effectiveness.

---

## Features

### Admin Module
- **Company Management**:
  - Add, edit, and delete companies.
  - Store details like name, location, LinkedIn profile, email addresses, phone numbers, comments, and default communication periodicity.

- **Communication Method Management**:
  - Define communication methods with properties like name, description, sequence, and mandatory status.
  - Default methods include:
    1. LinkedIn Post
    2. LinkedIn Message
    3. Email
    4. Phone Call
    5. Other

### User Module
- **Dashboard**:
  - Grid view displaying companies, last five communications, and next scheduled communication.
  - Color-coded highlights for overdue (red) and due-today (yellow) communications.

- **Communication Action**:
  - Log new communication for one or multiple companies.
  - Capture type, date, and notes of the communication.

- **Notifications**:
  - Overdue and due-today communications displayed in grids.
  - Badge count on notification icon.

- **Calendar View**:
  - View past and upcoming communications in a calendar format.

### Reporting and Analytics Module (Optional)
- Communication frequency reports.
- Engagement effectiveness dashboard.
- Overdue communication trends.
- Downloadable reports in PDF/CSV format.
- Real-time activity log.

---

## Setup and Deployment

### Prerequisites
- Node.js v16 or above
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/calendar-application.git
   cd calendar-application
