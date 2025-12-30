# WalletIQ
WalletIQ is a real-world finance tracker application developed in ASP.NET Core MVC with secure authentication, category-wise expense management, analytics, and reporting features.
💰 WalletIQ – Income & Expense Tracker

WalletIQ is a secure and scalable ASP.NET Core MVC–based personal finance management web application that helps users track income and expenses, analyze spending patterns, and manage their finances efficiently.
The application is hosted on AWS EC2, following best practices for deployment and security.

🚀 Live Deployment

Hosted on: AWS EC2 (Linux/Windows)

Web Server: IIS 

Database: SQL Server

Cloud Features: Public access with security group configuration

🧩 Modules Overview
1️⃣ Authentication & Authorization Module

User Registration & Login

Secure password storage

OTP-based Forgot Password

Role-based access control

Session management

2️⃣ User Profile Module

View and update user profile details

Change password functionality

Secure account workflows

3️⃣ Income Management Module

Add, update, delete income records

Category-wise income tracking

Date-wise income history

Real-time balance updates

4️⃣ Expense Management Module

Add, update, delete expenses

Category-based expense tracking

Expense filtering by date and category

Validation to ensure data accuracy

5️⃣ Dashboard & Analytics Module

Total income vs total expense overview

Current balance calculation

Monthly and category-wise analytics

Interactive charts and summaries

6️⃣ Reports Module

Financial summaries (daily, monthly)

Expense and income reports

Export reports as PDF

Secure access to reports

7️⃣ Notification & Email Module

SMTP email configuration

OTP delivery via email

Account-related notifications

8️⃣ Admin / System Management (Optional / Basic)

Application-level configuration

Monitoring user activities (basic)

Error logging and handling

🛠️ Tech Stack

Frontend: Razor Views, HTML, CSS, Bootstrap

Backend: ASP.NET Core MVC

ORM: Entity Framework Core

Database: SQL Server

Authentication: ASP.NET Core Identity

Email Service: SMTP

Hosting: AWS EC2

Deployment: IIS / Kestrel

☁️ AWS EC2 Deployment Details

Created an EC2 instance on AWS

Configured inbound rules (HTTP/HTTPS)

Deployed application using IIS

Configured connection strings securely

Hosted SQL Server database

Ensured application availability via public IP

🔐 Security Features

Password hashing and validation

OTP-based password recovery

Authorization filters

Input validation and error handling

Secure session management

📂 Project Structure (High Level)
WalletIQ
│── Controllers
│── Models
│── Views
│── Data
│── Services
│── wwwroot
│── appsettings.json
│── Program.cs
│── Startup.cs
