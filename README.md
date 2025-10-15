# Career Connect

Career Connect is a full-stack job platform that enables companies to post jobs, manage candidates, and allows candidates to apply for jobs. The platform also supports article publishing for career guidance and insights.

## Features

- **Role-Based Access Control**
  - Global roles: Candidate, Recruiter
  - Company-specific roles: Admin, Recruiter, Employee
- **Job Management**
  - Post and manage job openings
  - Apply to jobs as a candidate
- **Company Management**
  - Admins can manage company details and users
- **Articles**
  - Publish and view career-related articles
- **Authentication**
  - JWT-based authentication
  - Two-Factor Authentication (2FA)
  - Password reset via email
- **Validation & Security**
  - Input validation using Zod
  - Role and company-role based access control

## Tech Stack

- **Frontend:** React, Tailwind CSS, Shadcn/UI, React Router, Zustand  
- **Backend:** Node.js, Express, Modular controller-service-model architecture, MongoDB (Mongoose)  
- **Other:** JWT for authentication, Nodemailer for emails  

## Installation

1. Clone the repository:

```bash
git clone https://github.com/lalithmadhav11/CarrerConnect.git
Navigate to the project folder:

bash
Copy code
cd CarrerConnect
Install dependencies:

Backend:

bash
Copy code
cd backend
npm install
Frontend:

bash
Copy code
cd ../frontend
npm install
Set up environment variables in backend/.env:

ini
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
Run the project:

Backend:

bash
Copy code
cd backend
npm run dev
Frontend:

bash
Copy code
cd frontend
npm start
Folder Structure
css
Copy code
CareerConnect/
├─ backend/
│  ├─ controllers/
│  ├─ models/
│  ├─ routes/
│  ├─ services/
│  └─ app.js
├─ frontend/
│  ├─ src/
│  │  ├─ components/
│  │  ├─ pages/
│  │  └─ App.js
└─ README.md
