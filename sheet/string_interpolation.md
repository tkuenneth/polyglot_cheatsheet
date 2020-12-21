# String interpolation

String interpolation or variable substitution means replacing placeholders with corresponding variable content. 

- C# prefixes the string with `$`. Variables and expressions are put inside `{}`.
- Dart and Kotlin also do string interpolation by prefixing variable names with `$`. To evaluate expressions, put them inside `{ }`.
- Java has no string interpolation. Still, there certainly is powerful `String.format(...)`.
- JavaScript uses `` `...${}...` ``. The curly braces can contain expressions, too.
- Swift likes `"...\()..."`. So, variables or expressions are put in round braces. The prefix is `\`.

## C#

```csharp
var a = 1;
var b = 2;
Func<int, int> c = x => x * x;
Console.WriteLine($"a={a} b={b} c={c(3)}");
``` 

## Dart

```dart
var a = 1;
var b = 2;
var c = (int a) => a * a;
print("a=$a b=$b c=${c(3)}");
```

## Java

```java
var a = 1;
var b = 2;
UnaryOperator<Integer> c = (x) -> x * x;
System.out.println(String.format("a=%d b=%d c=%d",
        a, b, c.apply(3)));
```

## JavaScript

```javascript
var a = 1
var b = 2
var c = (a) => a * a
console.log(`a=${a} b=${b} c=${c(3)}`)
```

## Kotlin

```kotlin
val a = 1
val b = 2
val c = fun (a: Int) : Int = a * a
println("a=$a b=$b c=${c(3)}")
```

## Swift

```swift
let a = 1
let b = 2
let c = { (a) -> Int in a * a}
print("a=\(a) b=\(b) c=\(c(3))") 
```

---
[Back](/README.md) to main page