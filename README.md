# Vijay HR Manager: Smart HRM Solution

  Welcome to Vijay HR Manager, a powerful and user-friendly Human Resource Management System designed to simplify and digitize your employee lifecycle processes.

## Purpose

Built as a modern web application, this tool empowers HR departments with efficient management of employees, attendance, departments, and leave workflows — all from a centralized dashboard.

## Key Highlights

✅ Visual Dashboard – Real-time stats on employees, departments, and activity.

✅ Employee CRUD – Add, update, and remove employee profiles easily.

✅ Attendance Logs – Maintain daily check-ins and check-outs with precision.

✅ Leave Management – Handle leave requests with approvals and logs.

✅ Role-Based Interface – Optimized for HR, Admin, and Employees.

## Tech Stack Breakdown

  ### Frontend:  
  React.js + Tailwind CSS🛠 Backend: Node.js + Express.js🗄 
  ### Database: 
  MySQL
  ### Auth:  
  Firebase (Email + Google Login)

## Quick Start Guide

### Clone the Repository

    git clone https://github.com/vijayalluri08/vijay-hrms.git
    cd vijay-hrms

## Install Dependencies
### Frontend

          cd client
          npm install

### Backend

         cd backend
         npm install

## Setup MySQL Database

        Create a new database. (hr_management_database)
        Import the schema from hr_management_database/schema.sql

## Configure Environment Variables (server/.env)

      DB_HOST=localhost
      DB_USER=root
      DB_PASSWORD=your_password
      DB_NAME=hrms_db
      FIREBASE_API_KEY=your_api_key
      ...

 ## Run the Project
 
  ### Start backend
 
         cd server
         npm run dev

  ### Start frontend

         cd ../client
         npm start

## Modules Overview

🧩 Module      -                   📋 Description

📊 Dashboard   - Real-time overview of employee & department data


👤 Employees    - Full CRUD for employee records


🕒 Attendance    - Daily check-in and check-out tracking


📝 Leave Request   - Submit and manage leave applications


🏢 Departments       -View and categorize employees by department                       - View employees by department

## Access the Application:

Open your browser and navigate to http://localhost:3000.
