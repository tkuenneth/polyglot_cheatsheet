---
layout: page
title: Miscellaneous
---

### Arrows

Arrows (`->` or `=>`) are used in combination with lambda expressions. But please note that there are other use cases. C-like languages, for example, offer another arrow type: `>>` and `<<` represent operators.

##### C#

```csharp
List<String> strings = new List<String> { "Hello", "polyglot", "dev" };
strings.ForEach(element => System.Diagnostics.Debug.WriteLine(element));
```

##### Java

```java
List<String> strings = Arrays.asList(new String [] {"Hello", "polyglot", "dev"});
strings.forEach(element -> System.out.println(element));
```

##### JavaScript

```javascript
let strings = ["Hello", "polyglot", "dev"];
strings.forEach((element) => {console.log(element)});
```

##### Kotlin

```kotlin
val strings = listOf("Hello", "polyglot", "dev")
strings.forEach(action = { s: String -> println(s) })
```

##### Swift

In combination with closures the `in` keyword is used.

### Asynchronicity

This page briefly shows how to do (pseudo-)parallel execution of code. Actually, concepts of asynchronicity and concurrency are deliberately mixed to provide a first impression of how this is done in different programming languages. Please note that, depending on the language support for asynchronicity may be provided through the core language using keywords like `async` and `await`, or (class) libraries, or a mix of both.

##### C#

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

##### Dart

##### Java

```java
var t = new Thread(() -> {
  try {
    for (int i = 0; i < 3; i++) {
      System.out.println(i);
      Thread.sleep(3000);
    }
  } catch (InterruptedException e) {
    e.printStackTrace();
  }
});
t.start();
t.join();
System.out.println("Done");
```

##### JavaScript

##### Kotlin

##### Swift
