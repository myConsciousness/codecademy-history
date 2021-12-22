# Running Files

Great, we were able to compile our program into an executable file that will always print out “Hello World”. If we want our program to run again, we don’t have to compile the program again, we simply run the executable file. Therefore, if we want fast code that users interact with, we’d compile a program once and use the executable file.

But what happens if we ever wanted to change our program? We would have to compile another executable file and then run that file. Imagine having to do that every single time just to check a small change or fix an error! 😱

Thankfully, we have the `go run` command followed by the name of the Go program. The `go run` command combines both the compilation and execution of code for us. This allows us to quickly check the output of our code (and for any errors). Unlike go build, `go run` will NOT create executable file in our current folder.
