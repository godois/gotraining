## Constants

Constants are a way to create a named identifier whose value can never change. They also provide an incredible amount of flexibility to the language. The way constants are implemented in Go is very unique.

## Notes

* Constants are not variables.
* They existing only at compilation.
* Untyped constants can be implictly converted where typed constants and variables can't.
* Think of untyped constants as having a Kind, not a Type.
* Learn about explicit and implicit conversions.
* See the power of constants and their use in the standard library.

## Links

https://golang.org/ref/spec#Constants  
http://blog.golang.org/constants  
http://www.goinggo.net/2014/04/introduction-to-numeric-constants-in-go.html

## Code Review

[Declare and initialize constants](example1/example1.go) ([Go Playground](https://play.golang.org/p/dIJb3S6CIb))  
[Parallel type system (Kind)](example2/example2.go) ([Go Playground](https://play.golang.org/p/-DUJAVsTMp))  
[iota](example3/example3.go) ([Go Playground](https://play.golang.org/p/1Y9qjOuPt0))  
[Implicit conversion](example4/example4.go) ([Go Playground](https://play.golang.org/p/QzVFcMdU5S))  

## Exercises

### Exercise 1

**Part A:** Declare an untyped and typed constant and display their values.

**Part B:** Multiply two literal constants into a typed variable and display the value.

[Template](exercises/template1/template1.go) ([Go Playground](https://play.golang.org/p/QMrOCsHjcC)) | 
[Answer](exercises/exercise1/exercise1.go) ([Go Playground](https://play.golang.org/p/aUZ-7VPb9H))
___
All material is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/LICENSE-2.0).
