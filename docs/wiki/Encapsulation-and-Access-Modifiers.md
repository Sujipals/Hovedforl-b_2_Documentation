# Encapsulation and Access Modifiers

## Definition

Encapsulation means hiding internal data and exposing only the parts that are intentionally allowed to be used from outside the class.

## Access modifiers

- public: accessible from everywhere
- private: accessible only inside the class
- protected: accessible in the class and derived classes
- internal: accessible within the same assembly

## Example

```csharp
public class Book
{
    private string _title;

    public string Title
    {
        get { return _title; }
        set { _title = value; }
    }
}
```

## Why this matters

Encapsulation helps protect the state of an object and prevents invalid data from being set directly.

## School connection

In a library system, a book should not allow invalid or inconsistent values to be assigned without some control. Encapsulation makes the class safer and easier to maintain.

## Reflection

How does hiding fields help improve code quality?
