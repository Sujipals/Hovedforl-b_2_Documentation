# Delegates, Callbacks and Lambdas

## Delegate

A delegate defines a method signature that can be assigned to methods.

```csharp
public delegate void Notify();
```

## Lambda expression

A lambda is a short anonymous function.

```csharp
Action<string> print = message => Console.WriteLine(message);
print("Hello");
```

## Callback

A callback is a function passed as an argument to another function to be called later.

## Why this matters

Delegates and lambdas are useful when a method needs to respond to events or allow custom behavior.

## Example in school context

A library or order system could use a callback to notify the user when an item is borrowed or returned.
