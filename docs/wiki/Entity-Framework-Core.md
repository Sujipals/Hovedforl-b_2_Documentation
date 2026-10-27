# Entity Framework Core

## Overview

Entity Framework Core (EF Core) is an ORM used to work with relational database data in .NET applications.

## Benefits

- easier database access
- cleaner code
- object-based queries
- less manual SQL writing

## Example

```csharp
var products = context.Products
    .Where(p => p.Category == "Computer")
    .ToList();
```

## Important idea

The database is mapped to C# classes. You write queries against objects instead of raw SQL.

## Usage in school assignments

This is used when the project stores product data in a database and the assignment requires CRUD and filtering through LINQ expressions.
