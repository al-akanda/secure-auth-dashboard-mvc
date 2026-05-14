# SecureAuth Dashboard MVC

A modern **ASP.NET Core MVC web application** featuring secure authentication, authorization, Entity Framework Core integration, and dashboard CRUD functionality.

Built as a practical learning project to demonstrate real-world ASP.NET MVC application development.

---

##  Project Overview

SecureAuth Dashboard MVC is an ASP.NET Core MVC project that demonstrates:

- User Registration & Login
- Password Encryption / Hashing
- JWT Authentication
- Cookie-Based Authorization
- Entity Framework Core (Code First)
- SQL Server Integration
- MVC Routing & View Binding
- Dashboard CRUD Operations
- Validation & Exception Handling

This project combines backend logic, database management, authentication security, and frontend Razor view development.

---

## ✨ Features

### MVC Core Architecture
✔ ASP.NET Core MVC project structure  
✔ Controllers, Models, Views  
✔ `Program.cs` configuration  
✔ `appsettings.json` setup  
✔ `launchSettings.json` usage  
✔ Shared layout using `_Layout.cshtml`

### Controllers & Routing
✔ MVC Controllers  
✔ API Controllers  
✔ MVC vs API comparison  
✔ Routing configuration  
✔ Redirect between controllers  
✔ `View()` vs `RedirectToAction()`

### Database Integration
✔ Entity Framework Core setup  
✔ SQL Server connection string  
✔ Code First approach  
✔ Database migrations  
✔ AppDbContext configuration  
✔ SQL table inspection

### Authentication & Security
✔ User registration  
✔ Login functionality  
✔ Password hashing  
✔ JWT authentication  
✔ Cookie authorization  
✔ Protected routes/dashboard access

### Razor Views
✔ Login page UI  
✔ Registration page UI  
✔ Strongly typed views  
✔ `asp-for` model binding  
✔ Controller-to-view data transfer

### Data Passing
✔ ViewBag  
✔ ViewData  
✔ TempData  
✔ Model binding

### Validation
✔ Form validation  
✔ Model validation  
✔ Null exception handling  
✔ Input safety checks

### Dashboard CRUD
✔ Create records  
✔ View records  
✔ Update records  
✔ Delete records  
✔ Dashboard data listing

---

## 🛠 Tech Stack

### Backend
- ASP.NET Core MVC
- C#
- Entity Framework Core
- JWT Authentication
- Cookie Authentication

### Database
- SQL Server

### Frontend
- Razor Views
- HTML5
- CSS3
- Bootstrap
- JavaScript

### Tools
- Visual Studio
- SQL Server Management Studio (SSMS)
- Git
- GitHub

---

##  Project Structure

```bash
secure-auth-dashboard-mvc/
│
├── MyFirstMVCApp/
│   ├── Controllers/
│   ├── Models/
│   ├── Views/
│   ├── wwwroot/
│   ├── Program.cs
│   ├── appsettings.json
│   └── MyFirstMVCApp.csproj
│
├── .gitignore
└── MyFirstMVCApp.slnx


## ⚙️ Installation Guide

```bash
# Clone Repository
git clone https://github.com/al-akanda/secure-auth-dashboard-mvc.git

# Open Project in Visual Studio
MyFirstMVCApp.slnx

# Install Required Packages
Install-Package Microsoft.EntityFrameworkCore
Install-Package Microsoft.EntityFrameworkCore.SqlServer
Install-Package Microsoft.EntityFrameworkCore.Tools
Install-Package Microsoft.AspNetCore.Authentication.JwtBearer

# Run Migration
Add-Migration InitialCreate
Update-Database

# Run Application
dotnet run
```

### Configure Database

Update `appsettings.json`:

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=SecureAuthDb;Trusted_Connection=True;TrustServerCertificate=True;"
}
```
