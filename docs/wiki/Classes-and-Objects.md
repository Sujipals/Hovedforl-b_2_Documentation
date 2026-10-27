# Classes and Objects

## Definition

A class is a blueprint for creating objects. An object is an instance of a class.

Example:

```csharp
public class Book
{
    public string Title { get; set; }
    public string Author { get; set; }
}

Book myBook = new Book();
myBook.Title = "C# for Beginners";
```

## Why classes matter

Classes allow us to group related data and behavior. Instead of storing everything as standalone variables, we organize the data into meaningful units.

## Constructor

A constructor is a special method used to initialize an object when it is created.

```csharp
public class Borrower
{
    public string Name { get; set; }

    public Borrower(string name)
    {
        Name = name;
    }
}
```

## Fields, properties and methods

- Fields store data
- Properties expose data safely
- Methods define behavior

```csharp
public class Library
{
    private List<Book> books = new();

    public void AddBook(Book book)
    {
        books.Add(book);
    }
}
```

## Oral exam tip

Explain the difference between a class and an object, and describe how constructors and properties help model real-world concepts.
