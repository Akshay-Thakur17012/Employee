Practical Assignment: Employee Directory Portal
Objective:
Build a small Employee Directory where users can login, search, add, edit, and view employee
details. This tests backend API development, frontend skills, basic SQL design, and integration.
 Requirements
 Backend (.NET Core Web API)
• Create endpoints:
o POST /auth/login – JWT-based login
o GET /employees – List all employees with pagination
o GET /employees/{id} – View details
o POST /employees – Add employee
o PUT /employees/{id} – Update employee
o DELETE /employees/{id} – Delete employee
Technologies: .NET Core, JWT, Dependency Injection, ADO.net, SQL Server
 Frontend (React.js/Angular)
• Features:
o Login form
o Dashboard with:
▪ Employee listing (table/grid)
▪ Search bar
▪ Add/Edit employee form
▪ Responsive UI using Bootstrap/Tailwind
Must use: React Hooks, Controlled Forms, Axios/fetch, and React Router
 Database (SQL Server)
• Tables:
o Users (for login)
o Employees (ID, Name, Department, Designation, Email, Mobile, etc.)
Bonus:
• Use at least one stored procedure (e.g., employee search or insert).
• Add indexing on searchable fields (like name).
