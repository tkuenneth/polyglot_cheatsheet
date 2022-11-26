---
layout: page
title: Loops
---

## `for`-loops

`for`-loops may come in different flavors. Many languages have a C-like implementation, which consists of an *initialization*, a *condition* and an *increment*. Another syntax allows to iterate over arrays or lists.

### C#

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

### Dart

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

### Java

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

### JavaScript

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

### Kotlin

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

### Swift

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

## `while`-loops

`while`-loops execute code blocks as long as a condition is met. Most programming languages can have these condition checks either at the beginning or at the end. The latter one is useful if you want the code to execute at least once, even if it turns out that the condition is **not** met.

### C#

```csharp
int count = 0;
do {
    System.Diagnostics.Debug.WriteLine(count++);
} while (count < 4);
```

```csharp
int count = 0;
while (count < 4)
{
    System.Diagnostics.Debug.WriteLine(count++);
}
```

### Dart	

```dart
int count = 0;
do {
    print(count++);
} while (count < 4);
```

```dart
int count = 0;
while (count < 4) {
    print(count++);
}
```

### Java	

```java
int count = 0;
do {
    System.out.println(count++);
} while (count < 4);
```

```java
int count = 0;
while (count < 4) {
    System.out.println(count++);
}
```

### JavaScript

```javascript
let count = 0;
do {
  console.log(count++);
} while (count < 4);
```

```javascript
let count = 0;
while (count < 4) {
  console.log(count++);
}
```

### Kotlin	

```kotlin
var count = 0
do {
  println("${count++}")
} while (count < 4)
```

```kotlin
var count = 0
while (count < 4) {
    println("${count++}")
}
```

### Swift

```swift
var count = 0
while (count < 4) {
  print("\(count)")
  count += 1
}
```
