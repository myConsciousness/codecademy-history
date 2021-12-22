# Basic main

Continuing on with our program, we have:

```go
func main() {
    fmt.Println("Hello World")
}
```

There are a few things happening in our main function. We’re introduced to how functions (reusable blocks of code) are defined/created in Go. The basic syntax being:

The func keyword denotes the start of a function declaration.
func is followed by the name of the function.
After name is a pair of parentheses () and a set of curly braces {}.
Inside the function block {}, we indent the code inside using a tab. Then we access the fmt package and call its Println (stands for print line) function to print the message "Hello World" to the terminal.

Now let’s take a second and realize that while we defined our main function, we never explicitly told main to run its block of code. In other programming languages, functions have to be called, i.e. told to run its code. However, a main function is special, a file that has a package main declaration will automatically run the main function!

This nuance becomes more important as we build more complex programs. In the meanwhile, let’s finish up our program!
