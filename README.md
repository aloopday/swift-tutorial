# swift-tutorial

## swift language
[Swift Language](https://www.swift.org/install/macos/)

## Learn Swift
[Learn Swift](https://www.w3schools.com/swift/default.asp)

## Apple developer
[Apple Developer](https://developer.apple.com/swift/)

# Swift Get Started
[swift get started](https://www.w3schools.com/swift/swift_getstarted.asp)

Install the Swift toolchain and run your first "Hello Swift!" program from the terminal or Xcode.

main.swift:A Swift file; the top-level `print ` executes when run.
## Print: Writes text to standard output.Strings use double quotes.

Swift in Xcode
Create a new IOS app project(App template) in Xcode, choose 
Swift as the language, and run on  the simulator.
You can also use a Playground for quick experiments.

Note:Unlike some other languages, in Swift
`let` is used for `constants` and `var` for  variables.

Example explained:
- `let` creates an immutable constant: `var` creates a mutable variable
- `Type annotation` is optional; here we annotate `Double` and `Int`.
- `String interpolation`:`\(expr)`inserts values into strings.

## String Interpolation

In swift interpolation is done using `\(expr)`.
The most common and simple way to use string interpolation is to embed variable
names inside string literals.

# Swift Statements
## swift Statements
Swift code is built from statements such as 
`declarations`
`expressions`
`control flow`
Expression & Declaration Statements

- Declarations introduce names (like variables and constants)
- Expression statements evaluate an expression, such as a function call.
```
let  x = 2 // declaration
print(x) // expression statements

```
## Semicolons and Blocks
Semicolons are optional at line ends;
use them only to separate multiple statements on 
one line.
Braces group statements into a block.

Swift does not require semicolons at the end of each line.
Use them only when writing more than one statement on the same line.
Braces{ ... } from blocks that group statements.

## Swift Text Output
[Swift Text Output](https://www.w3schools.com/swift/swift_output.asp)

## Swift Text Output
Use `Print()` to write text and values to output.
Use string interpolation to combine values.

## Print Text
Use `Print() ` to write text.
interpolate values with `\(expr)`.
## Print Without Newline
Use the `terminator` parameter to avoid a trailing newline.

```
for n in 1...3{
    print(n,terminator: " ")//prints on one line 
}
print("done")
```

This example prints numbers on a single line by setting `terminator` to a space , then 
prints `done` on the next line.
## Tip :
```
print() ends with a newline. Pass terminator:"" to avoid a newline.
```

## Math Functions
Common functions like `abs`, `min`, and `max` help compute 
numeric results.
- `abs(x)` returns the absolute value of `x`
- `min(x,y)` returns the smaller of `x` and `y`.
- `max(x,y)` returns the larger of `x` and `y`.
```


