# Todo App Development Challenge

## Problem Statement

Your task is to create a simplified Todo web application using ASP.NET Core within a limited time frame of 2 hours. You can choose any technology stack from Web APIs, Blazor, Razor Pages, or MVC based on your preference and expertise. The primary focus is on demonstrating your technical skills, particularly in implementing authentication, task management, and priority assignment. Note that only the submitted code will be evaluated, and a complete project is not required.

## Requirements

1. **Setup:**
   - Create a new ASP.NET Core project using the technology stack of your choice (Web APIs, Blazor, Razor Pages, or MVC).
   - Configure the project to use Individual User Accounts for authentication.

2. **Authentication:**
   - Implement user registration, login, and logout functionalities using ASP.NET Core Identity.
   - Ensure that only authenticated users can access the app.

3. **Todo Model:**
   - Develop a "Todo" model with properties including ID, Title, Description, Due Date, Priority, and Status.
   - Implement an enumeration for Priority (Low, Medium, High) and Status (Pending, Completed).

4. **Database and Entity Framework:**
   - Create a database context using Entity Framework Core.
   - Set up a DbSet for the Todo model to store task data.

5. **Authorization:**
   - Implement authorization to allow users to view, create, edit, and delete their own todos.
   - Ensure users cannot access or modify tasks owned by others.

6. **CRUD Operations:**
   - Create API endpoints or controller actions for creating, reading, updating, and deleting todos.
   - Implement validation to ensure required fields are populated and due dates are valid.

7. **Todo Form:**
   - Design a basic form-based interface for adding and editing todos.
   - Include input fields for title, description, due date, priority, etc.

## Submission Guidelines

- Complete the code within a time frame of 2 hours.
- Submit the code to GitHub and share the repository link.
- To submit the task, create an **issue** on this repository with the following details:
  - **Title:** Your Name
  - **Description:** Link to your GitHub repository containing the task code files.
- Only the submitted code files will be evaluated, not a complete running project.

## Bonus

- Allow users to filter tasks by priority or status.
- Provide simple sorting options for tasks.
- Implement a basic listing page to display tasks.

This task assesses your ability to implement key functionalities within a time-constrained environment using a technology stack of your choice. Focus on demonstrating your technical skills in authentication, task management, and priority assignment, even if the user interface is minimal.
