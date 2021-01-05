# Asynchronicity

This page briefly shows how to do (pseudo-)parallel execution of code. Actually, concepts of asynchronicity and concurrency are deliberately mixed to provide a first impression of how this is done in different programming languages. Please note that, depending on the language support for asynchronicity may be provided through the core language using keywords like `async` and `await`, or (class) libraries, or a mix of both.

## C#

```csharp
Task.WaitAll(new Task[]
{
  Task.Run(async () => {
  for (int i = 0; i < 3; i++)
  {
    Console.WriteLine($"{i}");
    await Task.Delay(3000);
  }
})});
Console.WriteLine("Done");
```

## Dart

## Java

## JavaScript

## Kotlin

## Swift

---
[Back](/README.md) to main page