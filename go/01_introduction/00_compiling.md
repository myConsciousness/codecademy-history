# Compiling

When we write Go code, we’re writing it to be readable for ourselves and other developers. We’re able to make sense of the code and its intentions. Computers, on the other hand, do NOT understand Go code and thus have no direct idea what our code means/does. What computers do understand are a series of 0’s and 1’s (or binary). To translate Go code to binary, Go has a compiler, a piece of software that converts Go code into a program that the computer understands. This translated code is called an executable or a binary file. We can then run the executable which will do what our Go program was written to do.

To tell the compiler to compile a Go program, we first navigate to our Terminal (on Mac), or Command Prompt (on Windows). Then, type in go build followed by the name of our file and press Enter. If we wanted to run a file called greet.go, the command will look like:

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello World")
}
```

```terminal
go build greet.go
```

While nothing obvious is shown after we run our command, if we type in the command ls, we’ll see our original Go program and executable file.

```terminal
ls
greet greet.go
```

To execute the file, we call ./greet

```terminal
./greet
```

Note: If the Go compiler finds that our Go code isn’t written correctly, then it will throw an error and our Go program won’t compile. We’ll need to fix the error before the compiler can properly do its job.

Now let’s go one step further and actually do it!
