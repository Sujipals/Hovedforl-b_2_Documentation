# Inheritance and Polymorphism

## Inheritance

Inheritance allows one class to inherit behavior and properties from another class.

```csharp
public class Animal
{
    public void Eat()
    {
        Console.WriteLine("Eating");
    }
}

public class Dog : Animal
{
    public void Bark()
    {
        Console.WriteLine("Bark");
    }
}
```

## Polymorphism

Polymorphism means that different objects can be treated through the same base type.

```csharp
Animal myAnimal = new Dog();
myAnimal.Eat();
```

## Overload vs override

- Overload: same method name with different parameters
- Override: derived class changes virtual method behavior from the base class

## Why it matters

Inheritance and polymorphism help build more flexible and reusable system designs.

## School note

These concepts are often taught with heroes, vehicles, or library objects in real assignments.
