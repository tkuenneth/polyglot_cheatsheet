# for loops

[Back](README.md) to main page

## Dart	

Dart has a C-like `for`-loop:

```dart
for (var i = 0; i < 4; i++) {
    print(i);
}
```

Also, there is a `foreach`-like alternative:

```dart
const numbers = [12, 3, 14, 5]; 
for (var n in numbers) { 
    print(n); 
} 
```

## Java	

```java
String [] a = {"Java", "C#", "JavaScript", "…"};
  for (String b : a) {
  System.out.println(b);
}
```

## JavaScript

JavaScript has a C-like `for`-loop:

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
