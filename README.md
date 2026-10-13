# Task-Manager-API

A REST API for managing tasks, built to practise C# and ASP.NET Core Web API —
including authentication and Entity Framework Core persistence.

## What's in it

| File | Purpose |
| --- | --- |
| `controllers/TaskController.cs` | CRUD endpoints for tasks |
| `controllers/AuthController.cs` | Registration / login |
| `Models/TaskItem.cs` | The task entity |
| `data/ApplicationDbContext.cs` | EF Core database context |
| `TaskManagerAPI.http` | Ready-made requests for testing endpoints |

## Stack

C# · ASP.NET Core Web API · Entity Framework Core

## Running it

```bash
cd TaskManagerAPI
dotnet run
```

Connection strings and secrets come from `appsettings.json` /
`appsettings.Development.json`. Use `dotnet ef database update` to apply
migrations before first run.

Send requests with the committed `TaskManagerAPI.http` file (VS Code REST
Client or Visual Studio both read it).

## Status

Learning project, originally written in GitHub Codespaces.
