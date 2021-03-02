# Backend-ApiRestFull
Ejemplos de Api restfull desarrollandolo en el visual code

Dotnet Core SQLServer Swagger

dotnet new api —> creamos nuevo api

dependencia
dotnet add package Microsoft.EntityFrameworkCore

dotnet tool install —global dotnet-ef
dotnet tool add —global dotnet-ef
dotnet ef —version

dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.Sqlite
dotnet add package microsoft.entityframeworkcore.sqlserver
dotnet add package Swashbuckle.AspNetCore


Migración
dotnet ef migrations add InitialCreate
dotnet ef database update

Correr la aplicación
dotnet watch run
