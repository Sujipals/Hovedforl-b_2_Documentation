# .NET and .csproj

## What is .NET?

.NET is the developer platform used to build and run C# applications.

## Main parts

- SDK: tools used to build applications
- runtime: executes the application
- CLR: Common Language Runtime
- BCL: Base Class Library

## .csproj file

The `.csproj` file defines the project settings and dependencies.

```xml
<Project Sdk="Microsoft.NET.Sdk">
  <PropertyGroup>
    <OutputType>Exe</OutputType>
    <TargetFramework>net8.0</TargetFramework>
  </PropertyGroup>
</Project>
```

## Useful dotnet commands

```bash
dotnet new console
dotnet build
dotnet run
```

## Why it matters

Understanding the project file and dotnet CLI is essential for creating, compiling and running .NET projects.
