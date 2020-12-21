# for loops

`for`-loops may come in different flavors. Many languages have a C-like implementation, which consists of an *initialization*, a *condition* and an *increment*. Another syntax allows to iterate over arrays or lists.

## C#

```csharp
for (int i = 0; i <= 3; i++)
{
    System.Diagnostics.Debug.WriteLine(i);
}
```

```csharp
String[] a = { "Java", "C#", "JavaScript", "…" };
foreach (String b in a)
{
    System.Diagnostics.Debug.WriteLine(b);
}
```

## Dart

```dart
for (var i = 0; i < 4; i++) {
    print(i);
}
```

```dart
const numbers = [12, 3, 14, 5]; 
for (var n in numbers) { 
    print(n); 
} 
```

## Java

```java
for (int i = 0; i <= 3; i++) {
    System.out.println(i);
}
```

```java
String [] a = {"Java", "C#", "JavaScript", "…"};
  for (String b : a) {
    System.out.println(b);
}
```

## JavaScript

```javascript
for (i = 1; i <= 3; i++) {
 console.log(i);
}
```

```javascript
var a = ["Java", "C#", "JavaScript", "…"];
for (var b of a) {
  console.log(b);
}
```

## Kotlin

```kotlin
for (i in 1..3) {
  println(i)
}
```

```kotlin
for (i in 6 downTo 0 step 2) {
  println(i)
}
```

```kotlin
for (s in listOf("Java", "C#", "JavaScript", "…")) {
    println(s)
}
```

## Swift

```swift
for b in 1...10 {
  print(b)
}
```

```swift
for b in (1...10).reversed() {
  print(b)
}
```

---
[Back](/README.md) to main page