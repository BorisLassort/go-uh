go-uh: Micro Helper
===================

Package uhelpers (micro helpers) provides very tiny and simple helpers functions

## Examples

```go
package main

import (
	"fmt"
	uh "github.com/borislassort/go-uhelpers"
)

func main() {
	// Download
	err := uh.DownloadFile("file.zip", "https://the.u.r.l/file.zip")
	if err != nil {
		fmt.Println(err)
	}
	// Unzip
	err := uh.Unzip("file.zip", "dir/")
	if err != nil {
		fmt.Println(err)
	}
}
```
