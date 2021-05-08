---
layout: page
title: Conditions
---

Condition checks may come in different flavors. Most languages offer the classic `if`-`else` statements. Additionally we may find operators that check special conditions.

### C#

```csharp
if (new Random().Next(10) > 5)
{
    System.Diagnostics.Debug.WriteLine("> 5");
}
else
{
    System.Diagnostics.Debug.WriteLine("<= 5");
}
```

### Dart	

```dart
if (Random().nextInt(10) > 5) {
  print("> 5");
} else {
  print("<= 5");
}
```

The Ternary Operator:

```dart
print( 1 < 2 ? "<" : ">");
```

Test for `null`:

```dart
String s = "Hello"; // Replace with null
print(s?? "is null");
```

### Java

```java
if (Math.random() * 10 > 5) {
    System.out.println("> 5");
} else {
    System.out.println("<= 5");
}
```

### JavaScript

```javascript
if (Math.random() * 10 > 5) {
    console.log("> 5");
} else {
    console.log("<= 5");
}
```

### Kotlin

```kotlin
if ((0 until 10).random() > 5) {
    println("> 5");
} else {
    println("<= 5");
}
```

### Swift

```swift
if (Int.random(in: 0..<10) > 5) {
    print("> 5");
} else {
    print("<= 5");
}
```
