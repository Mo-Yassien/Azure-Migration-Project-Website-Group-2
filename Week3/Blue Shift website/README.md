# Blueshift Azure Migration Project App

## Overview
This project is a web application built with ASP.NET Core MVC (.NET 8.0) that simulates a real-world Azure migration scenario. It demonstrates the process of migrating a website from an on-premises environment (IIS) to Azure App Service, following best practices for cloud migration.

## Features
- **Project Goal Page:** Describes the migration objective and Azure benefits (scalability, security, reliability, etc.).
- **Timeline Page:** Week-by-week migration plan, including:
  - Setting up the source environment on Azure
  - Building a landing zone website
  - Importing the website into the source server
  - Migrating the website to Azure App Service
- **Team Members Page:** Displays project team members with names, roles, and photos.
- **Modern UI:** Dark theme, responsive layout, and Bootstrap styling.

## Technologies Used
- **Framework:** ASP.NET Core MVC (.NET 8.0)
- **Language:** C#
- **UI:** Bootstrap 5, custom CSS
- **Project Structure:** MVC (Model-View-Controller)

## Getting Started

### Prerequisites
- [.NET 8.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- Visual Studio 2022+ or Visual Studio Code

### Setup & Run
1. Clone or download this repository.
2. Open the solution in Visual Studio or VS Code.
3. Restore dependencies (usually automatic).
4. Run the project:
   - Using terminal: `dotnet run` from the `BlueshiftAzureMigration` directory
   - Or use the Visual Studio play button
5. Open your browser to `https://localhost:5001` (or the port shown in your terminal).

### Project Structure
- `Controllers/` — MVC controllers
- `Views/` — Razor views for each page
- `wwwroot/images/` — Static images (logo, team members)
- `Views/Shared/_Layout.cshtml` — Main layout and navigation

## Customization
- Update content in the Razor views (`Views/Home/Index.cshtml`, `Timeline.cshtml`, `TeamMembers.cshtml`).
- Replace images in `wwwroot/images/` as needed.
- Extend with new pages, features, or connect to a database for dynamic content.

## License
This project is for educational and demonstration purposes. 
