# ASP.NET-Core-with-Angular-Todo-App

## 📝 Project Description

**TodoApp** is a simple full-stack application built with **ASP.NET Core Web API** and **Angular**.  
It demonstrates how to create a CRUD (Create, Read, Update, Delete) Todo List using a modern web application stack.

This project is ideal for beginners to learn about:
- Backend API development with ASP.NET Core
- Frontend SPA (Single Page Application) development with Angular
- Communication between frontend and backend via HTTP

---

## 🛠 Technologies Used

| Layer           | Technology                          |
|-----------------|-------------------------------------|
| Backend         | ASP.NET Core 9.0+ (C#)              |
| Frontend        | Angular 15+ (TypeScript, HTML, CSS) |
| Communication   | RESTful API (JSON)                  |
| Development IDE | Visual Studio 2022                  |
| Package Manager | npm (Node Package Manager)          |

---

## 📂 Project Structure

```markdown
TodoApp/
│
├── Controllers/          # C# API Controllers
├── Models/               # C# Data Models (TodoItem)
├── ClientApp/            # Angular Frontend Application
│   ├── src/
│   │   ├── app/
│   │   │   ├── components/  # Angular Components (Todo list, item forms)
│   │   │   ├── services/    # API Service for HTTP requests
│   │   ├── assets/          # Static files
│   │   └── environments/    # Environment configurations
├── Startup.cs / Program.cs  # App startup configuration
└── README.md               # Project documentation
```


---

## 🚀 Getting Started

### Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/) (ASP.NET and Web Development workload)
- [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download)
- [Node.js and npm](https://nodejs.org/en/)
- Angular CLI installed globally:
  ```bash
  npm install -g @angular/cli

## Setup Instructions

### Clone the repository:

git clone https://github.com/yourusername/TodoApp.git
cd TodoApp

### Install Angular dependencies:

cd ClientApp
npm install
cd ..

### Run the application:

In Visual Studio: 
Press F5 to build and run the backend and frontend together.

Or from command line:
dotnet run

### Access the app:

Navigate to the URL shown in the console to view the app.

