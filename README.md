
# MS Learn - Minimal API

[Create web apps and services with ASP.NET Core, minimal API, and .NET](https://learn.microsoft.com/en-us/training/modules/build-web-api-minimal-api)

## Course Notes

Use the `dotnet new` command to scaffold a project.

```
dotnet new web -o PizzaStore -f net8.0
```

Add Swagger

```
dotnet add package Swashbuckle.AspNetCore --version 6.5.0
```

## Bonus: (How to use Identity to secure a Web API backend for SPAs)[https://learn.microsoft.com/en-us/aspnet/core/security/authentication/identity-api-authorization?view=aspnetcore-8.0]

### Nuget packages

```
dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.InMemory

```
