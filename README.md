# Console

Console is a library written in pure Go providing a set of functions that allow you to print messages to a terminal using color-coded outputs.

The library's functions extends the standard `log` library, thereby giving each logger access to all of it's internal functions.

## Basic Usage

### Installation

```bash
go get github.com/rrandall91/console
```

### Example Usage

```go
package main

import (
    "github.com/rrandall91/console"
)

func main() {
    // Print in blue
    Info.Println("I am an informative message")

    // Print in yellow
    Warning.Println("I am a warning")

    // Print in red
    Error.Println("I am an error")

    // Print in cyan
    Debug.Println("I am a debug message")
}
```