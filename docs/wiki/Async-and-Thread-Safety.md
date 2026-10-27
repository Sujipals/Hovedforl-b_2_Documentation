# Async and Thread Safety

## Async programming

`async` and `await` are used to perform work without blocking the application.

```csharp
public async Task<string> LoadDataAsync()
{
    await Task.Delay(1000);
    return "Loaded";
}
```

## Thread safety

Thread safety means making code safe when it is used from multiple threads at the same time.

## Problems to avoid

- race conditions
- deadlocks
- shared mutable state without locking

## Practical note

When many tasks access the same object at the same time, synchronization or careful design is necessary.
