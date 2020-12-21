# Arrows

Arrows (`->` or `=>`) are used in combination with lambda expressions. But please note that there are other use cases. C-like languages, for example, offer another arrow type: `>>` and `<<` represent operators.

## C#

```csharp
List<String> strings = new List<String> { "Hello", "polyglot", "dev" };
strings.ForEach(element => System.Diagnostics.Debug.WriteLine(element));
```

## Java

```java
List<String> strings = Arrays.asList(new String [] {"Hello", "polyglot", "dev"});
strings.forEach(element -> System.out.println(element));
```

## JavaScript

```javascript
let strings = ["Hello", "polyglot", "dev"];
strings.forEach((element) => {console.log(element)});
```

## Kotlin

```kotlin
val strings = listOf("Hello", "polyglot", "dev")
strings.forEach(action = { s: String -> println(s) })
```

## Swift

In combination with closures the `in` keyword is used.

---
[Back](/README.md) to main page