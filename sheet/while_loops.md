# while loops

`while`-loops execute code blocks as long as a condition is met. Most programming languages can have these condition checks either at the beginning or at the end. The latter one is useful if you want the code to execute at least once, even if it turns out that the condition is **not** met.

## C#

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

## Dart	

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

## Java	

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

## JavaScript

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

## Kotlin	

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

## Swift

```swift
var count = 0
while (count < 4) {
  print("\(count)")
  count += 1
}
```

---
[Back](/README.md) to main page