# RaceDay System

A full-stack event management platform for South African road running, walking, and cycling events. 

This repository contains the complete **Part 2 (RESTful API)** and **Part 3 (MVC Frontend, Azure Blob Storage, and Docker)** submissions.

## Project Overview

The RaceDay system allows Participants to browse events, enrol in race categories, and view their personal results. It allows Organisers to create and manage events, categories, upload banner images, and record participant results.

- **Part 2 (Backend):** ASP.NET Core Web API with JWT-based authentication and role-based access control.
- **Part 3 (Frontend):** ASP.NET Core MVC application that consumes the API, handles session management, and provides role-specific dashboards. The system is fully containerized using Docker and uses Azure Blob Storage for image uploads.

## Technology Stack

| Technology | Purpose |
|---|---|
| ASP.NET Core 8.0 | Web API and MVC Frontend |
| Entity Framework Core 8.0 | ORM (Code-First) |
| SQL Server (LocalDB) | Database |
| JWT (JSON Web Tokens) | Authentication |
| BCrypt.Net-Next | Password hashing |
| Swagger / Swashbuckle | API documentation |
| xUnit | Unit testing |
| Azure Blob Storage | Image storage (Part 3) |
| Docker | Containerization (Part 3) |
| GitHub Actions | CI/CD pipeline |



## Local Setup Instructions

**Prerequisites:** .NET 8.0 SDK, Visual Studio 2022, SQL Server LocalDB.

**Step 1 - Clone the repository:**
```bash
git clone https://github.com/kgothatso1006/RaceDay.API.git
cd RaceDay.API
