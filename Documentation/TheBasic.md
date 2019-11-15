# The Basics

* __Swift__는 iOS, macOS, watchOS, tvOS App을 개발하기 위한 __새로운 프로그래밍 언어__
* Number Type: `Int`, `Double`, `Float`
* Bool Type: `Bool`
* Textual Dtat: `String`
* Collection Type: `Array`, `Set`, `Dictionary`
* Tuple Type
* Optional
* Type Safe Language

## Constants and Variables

* constant: 변하지 않음
* variable: 변할수 있음

### Declaring Constants and Variables

#### 선언

```Swift
let maximumNumberOfLoginAttempts = 10
var currentLoginAttempt = 0
```

- `maximumNumberOfLoginAttempts`라는 새로운 상수를 선언하고, 10이란 값을 줌
- `currentLoginAttempt`란 변수를 선언하고, 0을 할당함.

#### 한줄에 여러 변수 선언

```Swift
var x = 0.0, y = 0.0, z = 0.0
```
### Type Annotations

변수 또는 상수를 선언할 때, 이름 뒤에 `:`을 넣고, 형식명을 지정함.
명시적으로 변수 또는 상수의 형식을 지정 선언함.

> The colon in the declaration meas 
> ...of type...,"

```Swift
var welcomeMessage: String
```

### Naming Constants and Variables

영문자, 한글 등 unicode도 지원함
일반적으론 영문자가 좋음.

```Swift
let π = 3.14159
let 你好 = "你好世界"
let 🐶🐮 = "dogcow"
let 성적 = "A+"
```

keyword를 선언할 경우엔 `를 사용함. (예: `default`)

그러나 keyword 사용은 권장하지 않음

### Printing Constants and Variables

`print` function 사용함.

```Swift
print(friendlyWelcome)
print("The current value of friendlyWelcome is \(friendlyWelcome)"
```

## Comments

### 한줄 주석

```Swift
// This is a comment
```

### 여러 줄 주석

```Swift

/* This is also a comment
but is written over multiple lines. */
```

### 주석안의 주석 가능함.

```Swift
/* This is the start of the first multiline comment.
	/* This is the second, nested multiline comment. */
This is the end of the first multiline comment. */
```

## Semicolons

생략 가능함.
한줄에 여러개의 문장을 구성할 경우엔 사용함.

```Swift
let cat = ""; print(cat)
```

## Integers

### Integer Bounds

### Int

### UInt

## Floating-Point Numbers

## Type Safety and Type Inference

## Numeric Literals

## Numeric Type Conversion

### Integer Conversion

### Integer and Floating-Point Conversion

## Type Aliases

## Booleans

## Tuples

## Optionals

### nil

### If Statements and Forced Unwrapping

### Optional Binding

### Implicityly Unwrapped Optionals

## Error Handling

## Assertions and Preconditions

### Debugging with Assertions

### Enforcing Preconditions







