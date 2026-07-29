Project Overview
This project is an ASP.NET Core MVC application designed to manage insurance claims. It allows users to create, view, edit, and delete insurance claims, ensuring efficient tracking and data management.

Features
CRUD Operations: Full Create, Read, Update, and Delete functionality for insurance claims.
Data Validation: Server-side validation using Data Annotations (e.g., ensuring Incident Date is not after Claim Date).
Authentication/Authorization: Secure access control using ASP.NET Core Identity.
Role-Based Access:Admin and User role management.

Technologies Used
Framework: ASP.NET Core 8.0 MVC
ORM: Entity Framework Core
Database: SQL Server
Authentication: ASP.NET Core Identity

Setup Instructions
Clone the repository: `git clone [Your-Repo-Link]`
Open the solution in Visual Studio.
Update the `appsettings.json` connection string to point to your local SQL Server instance.
Run the project using the "Run" button in Visual Studio.

Database Setup
Open the Package Manager Console in Visual Studio.
Run the command: `Update-Database`
The database will be created automatically based on the migration files.

Known Issues
The search functionality is not yet fully implemented.
