# Bike Rentals

A full-stack bike rental management application built with C# and ASP.NET Core MVC.

The project demonstrates the development of a database-driven business application for managing bikes, customers/users and rental transactions through a modern web interface.

## Overview

Bike Rentals was developed as a practical demonstration of ASP.NET Core application development using the MVC architecture.

The system provides functionality for managing a fleet of bikes and recording rental activity, with user authentication and persistent database storage.

The project demonstrates a typical business application structure, separating data models, controllers, views and services while using Entity Framework Core for data access.

## Features

- Bike management
- Rental management
- User management
- User authentication and authorisation
- Database-backed application data
- ASP.NET Core MVC architecture
- Entity Framework Core data access
- Responsive web interface
- REST/API support
- Swagger / OpenAPI integration

## Technology Stack

- **C#**
- **.NET 10**
- **ASP.NET Core MVC**
- **ASP.NET Core Identity**
- **Entity Framework Core**
- **Microsoft SQL Server**
- **SQLite**
- **Razor Views**
- **HTML / CSS / JavaScript**
- **Swagger / OpenAPI**
- **Visual Studio**

## Architecture

The application follows the ASP.NET Core MVC pattern:

- **Models** represent bikes, rentals and application data.
- **Views** provide the browser-based user interface.
- **Controllers** handle application requests and business operations.
- **Entity Framework Core** provides persistence and database access.
- **ASP.NET Core Identity** provides account and authentication functionality.

This separation keeps the application structured and maintainable while providing a foundation that can be extended with additional rental and fleet-management functionality.

## Project Structure

```text
ReactBikeRentals/
│
├── Areas/
│   └── Identity/
├── Controllers/
├── Data/
├── Migrations/
├── Models/
├── Services/
├── Views/
├── wwwroot/
└── Program.cs
