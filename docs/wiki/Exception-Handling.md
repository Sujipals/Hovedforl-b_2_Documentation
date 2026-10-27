# Exception Handling

## Overview

Exceptions are used to handle unexpected or invalid situations at runtime.

## Basic structure

```csharp
try
{
    int result = 10 / 0;
}
catch (DivideByZeroException ex)
{
    Console.WriteLine("You cannot divide by zero.");
}
finally
{
    Console.WriteLine("This always runs.");
}
```

## Custom exceptions

A custom exception can make the code clearer and more meaningful.

```csharp
public class BookAlreadyBorrowedException : Exception
{
    public BookAlreadyBorrowedException(string message) : base(message)
    {
    }
}
```

## Why exception handling is important

It helps the program respond to errors without crashing. It also separates the business rules from the user-facing behavior.

## In the library project

Exceptions can be used when:

- a book is already borrowed
- a borrower has no valid ID
- a user tries to borrow a non-existing item

## Oral exam tip

Be prepared to explain try/catch/finally and why custom exceptions are useful in domain-driven code.
