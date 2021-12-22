# Comments

We can’t always be there in person to explain to the next developer (or even our future self) what our code does or what our intentions were when writing it. That’s where comments come in.

Comments are ignored by the compiler and helpful for many things. We can use comments to explain our code, or thought process, and even to comment out code to debug (fix errors).

Go also encourages the use of comments for describing what functions do, it gets used by Go’s documentation tool. In fact, it started on their Github Wiki page!

There are two types of comments in Go. A line comment is created using //:

```go
// This entire line is ignored by the compiler
// fmt.Println("Does NOT print")
fmt.Println("This gets printed!") // This part gets ignored
```

Notice that line comments out the content to the right of //.

There are also block comments that can span multiple lines— it starts with /_, ends with a _/ and envelopes everything inside (including new lines):

```go
/*
This is ignored.
This is also ignored.
fmt.Println("This WON'T print!")
*/
```

In the example above we’ve commented out all three lines using a block comment.

Let’s use some comments in our own code!
