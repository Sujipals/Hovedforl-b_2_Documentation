# Collections and Generics

## What are collections?

A collection is a type that stores multiple items in one structure.

Examples:

- List<T>
- Dictionary<TKey, TValue>
- HashSet<T>
- Queue<T>
- Stack<T>

## Example with List<T>

```csharp
List<Book> books = new();
books.Add(new Book());
books.Add(new Book());
```

## Dictionary

```csharp
Dictionary<string, Book> booksByTitle = new();
booksByTitle["C# Basics"] = new Book();
```

## Why generics matter

Generics make code reusable and type-safe. Instead of using `object`, we can define a type parameter such as `List<Book>`.

## Common uses in the project

Collections are used to manage:

- books in a library
- borrowers in a system
- search results
- records that belong together

## Reflection

Explain when to choose `List<T>` versus `Dictionary<TKey, TValue>` in a real problem.
