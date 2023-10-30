# dotnet web api practice

This repository contains code for practicing building web APIs using .NET 7.0 It includes examples of CRUD operations, authentication, and authorization.

## Video

[.NET 7 Beginner Course 🚀 Web API, Entity Framework 7 & SQL Server](https://youtu.be/9zJn3a7L1uE?si=TnCwflXjc-rnpJz7)

## Prerequisites

- [.NET 7.0](https://dotnet.microsoft.com/download/dotnet/7.0)
- [AutoMapper](https://www.nuget.org/packages/AutoMapper)
- [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/get-started/overview/first-app?tabs=netcore-cli)
- [SQLite](https://www.sqlite.org)

## Getting Started

To get started, clone the repository and run the following command:

#### Add database

```
dotnet ef migrations add InitialCreate
```

```
dotnet ef database update
```

#### Run project

```
dotnet watch run
```
