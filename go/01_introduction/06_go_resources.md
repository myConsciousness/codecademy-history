# Go Resources

Learning a new language like Go involves learning the accompanying rules and syntax. But, we don’t have to commit everything to memory! It’s ok to search things up, in fact, that’s what all good programmers do!

In addition to online resources, Go also has it’s own built-in documentation system. To use it, in the command line, use the command go doc followed by a package name. For instance, to find out more information on the fmt package, you can use the command:

```terminal
go doc fmt
```

In the terminal, you’ll see at the top:

```terminal
package fmt // import "fmt"

Package fmt implements formatted I/O with functions analogous to C's printf
and scanf. The format 'verbs' are derived from C's but are simpler.
```

The information returned actually spans quite a few lines, the example above is truncated. To get more specific information about a function in a package (like fmt‘s Println function) append .Println (or .println, the capitalization of the function doesn’t matter to go doc) to the command:

```terminal
go doc fmt.Println
```

The go doc command is also very helpful when you’re interacting with new libraries and packages. Try it out yourself!
