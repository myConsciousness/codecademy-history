# Basic Packages

Now that we understand how to compile and run Go programs, let’s take a detailed look at the structure of Go’s program, specifically its packages:

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello World")
}
```

Go programs are read from top to down, left to right, so let’s focus on the first line package main. This line is called a package declaration and every Go program starts with one. The package declaration informs the compiler whether to create an executable or library. In contrast to an executable, a library doesn’t outright run/execute code — it is a collection of code that can be used in other programs. Programs that have the package declaration package main (like ours) will create an executable file.

Next is a blank line. Go generally ignores these blank lines, they’re considered whitespace (new lines, spaces, and tabs). While our program doesn’t need the line break, it makes our code easier to read, or increases the program’s readability.

Then we have an import statement, import "fmt". The import keyword allows us to bring in and use code from other packages. We should also note that the package name is enclosed with double quotes ", otherwise our program will get an error and not compile/run.

Packages serve important roles in Go. They group related code together, allow code to be reusable, and make it easier to maintain. We only import the packages we need. In turn, our programs run faster because it’s not bogged down by extra code/packages!

Now that we have a general idea of how a Go program is written. Let’s start to write our own from scratch!
