Calendar Communication Tracker
Overview
A React-based Calendar Application designed to track communication with companies, ensuring timely and consistent follow-ups. The application includes:

Admin Module: Manage companies and communication parameters.
User Module: View, manage, and log communication tasks.
Optional Reporting Module: Insights and performance metrics.
Features
Admin Module:

Add, edit, and delete companies.
Define communication methods with periodicity and sequences.
User Module:

Dashboard with overdue and due communications.
Calendar view for tracking past and future interactions.
Tech Stack:

Frontend: React, Axios, Material-UI/Tailwind CSS.
Backend: Spring Boot, MySQL.
Deployment: Heroku (Backend), Vercel (Frontend).
Setup Instructions
Backend Setup:

Install Java 17 and Maven.
Create a MySQL database:
sql
Copy code
CREATE DATABASE calendar_app;
Update application.properties with database credentials.
Run the application:
bash
Copy code
mvn spring-boot:run
Frontend Setup:

Navigate to the frontend directory.
Install dependencies:
bash
Copy code
npm install
Run the development server:
bash
Copy code
npm start
API Endpoints
GET /api/companies: Fetch all companies.
POST /api/companies: Add a new company.
DELETE /api/companies/{id}: Delete a company.
Deployment
Backend: Hosted on Heroku.
Frontend: Hosted on Vercel.
