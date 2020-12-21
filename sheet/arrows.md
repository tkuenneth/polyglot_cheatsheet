# Arrows

Arrows are often used in combination with lambda expressions.

## C#

## Java

```java
List<String> strings = Arrays.asList(new String [] {"Hello", "polyglot", "dev"});
strings.forEach(element -> System.out.println(element));
```

## JavaScript

Spot the difference: `->` vs. `=>`. Some languages use the arrow for something else.

## Kotlin

```kotlin
val strings = listOf("Hello", "polyglot", "dev")
strings.forEach(action = { s: String -> println(s) })
```

## Swift

In combination with closures the `in` keyword is used.

## Other arrows

C-like languages offer another arrow type: `>>` and `<<`.

---
[Back](/README.md) to main page