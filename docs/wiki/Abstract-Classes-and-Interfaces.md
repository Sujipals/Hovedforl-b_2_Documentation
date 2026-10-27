# Abstract Classes and Interfaces

## Abstract class

An abstract class cannot be instantiated directly and can contain abstract methods.

```csharp
public abstract class Shape
{
    public abstract double Area();
}
```

## Interface

An interface defines a contract. A class that implements it must provide the required members.

```csharp
public interface IComparable
{
    int CompareTo(object obj);
}
```

## Difference between abstract class and interface

- abstract classes can contain shared implementation
- interfaces define behavior contracts without implementation
- classes can implement multiple interfaces, but only inherit from one base class

## When to use them

Use abstract classes when multiple classes share common behavior. Use interfaces when different classes need to follow the same contract.
