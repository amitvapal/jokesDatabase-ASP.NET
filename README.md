# Jokes App - ASP.NET Core Project

## Overview

This project is an implementation tailored to create a dynamic web application for managing jokes. It serves as a practical example of applying ASP.NET Core principles to build a full-stack web application. The app allows users to perform CRUD operations on jokes, implementing user authentication to secure these actions.

### Features

- **CRUD Operations**: Users can create, read, update, and delete jokes.
- **User Authentication**: Secure registration and login system.
- **Search Functionality**: Users can search for jokes based on keywords.
- **Responsive Design**: Utilizes Bootstrap for a mobile-friendly user interface.

### Built With

- **ASP.NET Core**: For backend logic and framework structure.
- **Entity Framework Core**: For database interactions and ORM.
- **SQL Server**: As the relational database system.
- **Bootstrap**: For frontend styling and responsiveness.

## Getting Started

Follow these instructions to get a copy of the project running on your local machine.

### Prerequisites

Ensure you have the following installed:
- .NET Core SDK
- An IDE like Visual Studio or VS Code with C# support
- SQL Server (LocalDB or Express)

## Installation and Running the Application

Follow these steps to set up and run the Jokes App on your local environment:

### Open the Solution

1. Open the cloned repository in your preferred IDE that supports .NET Core development (such as Visual Studio, VS Code with C# extension, or Rider).

### Restore Packages

2. Before running the application, you need to restore the necessary dependencies. Open a terminal or command prompt in the project's root directory (where the `.csproj` file is located) and run the following command:

   ```bash
   dotnet restore

### Setup Database

3. In same terminal apply command -- dotnet ef database update

### Run the Application

4. Then run the application using -- dotnet run
5. You can access it by the URL indicated in your terminal in your web browser
