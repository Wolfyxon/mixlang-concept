# MixLang concept
A imaginary programming language aiming at simplicity and strong type hinting, I'd like to make at some point.

It has *Mix* in the name because it's a mixture of multiple languages.
Specifically I want to combine:
- Type and class system of **Java**
- Simplicity and threading of **Lua**
- Utilities of **GDScript**

into a 1 perfect language with my extra additions.

## Short examples
### Hello world
```js
print("Hello World")
printc("!")
// Together will print "Hello Wold!"
```
### Variables & consts
```js
var anything = "Hi"
anything = 2

String onlyStrings = "Aaa"
onlyStrings = 1 // error
onlyStrings = "bbbb"

const appVersion = "1.0"
const String betterAppVersion = "1.0"

final username
username = "Wolfyxon"
username = "Not Wolfyxon" // error
```
