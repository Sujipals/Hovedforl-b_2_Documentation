# LINQ to Objects

## What is LINQ?

LINQ stands for Language Integrated Query. It allows data to be queried in a readable and consistent way in C#.

## Example

```csharp
List<int> numbers = new() { 1, 2, 3, 4, 5 };
var evenNumbers = numbers.Where(n => n % 2 == 0).ToList();
```

## Common operators

- Where
- Select
- OrderBy
- GroupBy
- FirstOrDefault
- Count
- Sum

## Why it matters

LINQ is useful for filtering, sorting, and analysing collections in a clear and concise way.
