# Importing Multiple Packages

Previously, we imported a single package, fmt. But, we can import so many more! Go has an extensive list of packages that we can take advantage of. Here’s a list of Go’s standard packages

To import multiple packages we can add multiple import statements, like so:

```go
import "package1"
import "package2"
```

Or we can use a single import with a pair of parentheses that contain our packages:

```go
import (
    "package1"
    "package2"
)
```

Notice, when using an import with parentheses, we’re not separating each package with a comma. Instead, each package is on a different line.

We can also provide an alias to a package by including the alias name before the file. Including an alias will make it easier to refer to the package without typing out the full package name:

```go
import (
    p1 "package1"
    "package2"
)
```

In the example above we’ve aliased package1 as p1 and now we can call functions from package1 by using p1 like:

```go
p1.SampleFunc()
```

Instead of:

```go
package1.SampleFunc()
```
