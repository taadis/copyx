# CopyX

Keep Copy Simple Stupid

## Supports:

- Copy
- CopyFile
- CopyMode
- CopyTree

## Usage

Get the package and import.

```
go get github.com/taadis/copyx
```

```go
package main

import "github.com/taadis/copyx"

func main() {
	copyx.Copy("source", "dest", false)
}

```
