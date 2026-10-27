# Value and Reference Types

## Overview

C# has both value types and reference types.

## Value types

Value types store their own data directly.

Examples:

- int
- float
- double
- decimal
- bool
- struct

```csharp
int a = 10;
int b = a;
b = 20;

Console.WriteLine(a); // 10
Console.WriteLine(b); // 20
```

## Reference types

Reference types store a reference to the object in memory.

Examples:

- class
- string
- array
- List<T>

```csharp
Book book1 = new Book();
book1.Title = "C# Basics";

Book book2 = book1;
book2.Title = "Updated Title";

Console.WriteLine(book1.Title); // Updated Title
```

## Why this matters in programming

When assigning reference types, both variables point to the same object. This affects how changes propagate through the program.

## Why decimal is used for money

`decimal` is preferred for currency because it stores numbers with higher precision and avoids rounding issues that can occur with `double`.
