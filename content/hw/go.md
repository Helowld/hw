---
title: "Go"
date: 2021-10-02T18:46:05+05:30
draft: true
author: Robert Griesemer, Rob Pike, Ken Thompson
website: https://golang.org
First_appeared: November 10, 2009
---

```go {linenos=table, linenostart=1}
package main

// import "fmt" - The fmt package is imported and it will be used inside the main function to print text to the standard output.
import "fmt"

// func main() - The main is a special function. The program execution starts from the main function.
// The main function should always reside in the main package. The { and } indicate the start and end of the main function.
func main() {
	// fmt.Println("Hello World") - The Println function of the fmt package is used to write text to the standard output.
	fmt.Println("Hello, World!")
}
```

### About language
Go is a statically typed, compiled programming language designed at Google by Robert Griesemer, Rob Pike, and Ken Thompson. Go is syntactically similar to C, but with memory safety, garbage collection, structural typing, and CSP-style concurrency.