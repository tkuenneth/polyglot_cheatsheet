# Arrows

Arrows are often used in combination with lambda expressions.

## Java

```java
List<String> strings = Arrays.asList(new String [] {"Hello", "polyglot", "dev"});
strings.forEach(element -> System.out.println(element));
```

## Kotlin

```kotlin
val strings = listOf("Hello", "polyglot", "dev")
strings.forEach(action = { s: String -> println(s) })
```

## C#

## JavaScript

Spot the difference: `->` vs. `=>`. Some languages use the arrow for something else.

## Swift

In combination with closures the `in` keyword is used.

## Other arrows

C-like languages offer another arrow type: `>>` and `<<`.

---
[Back](/README.md) to main page