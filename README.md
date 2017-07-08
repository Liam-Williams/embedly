# extract

A go client for the embedly Extract API.

### Usage

```go
package main

import (
  "github.com/Liam-Williams/embedly.go/extract"
)

func main() {
  c := extract.NewClient(key)
  urls := []string{}
  options = extract.Options{}
  responses, err := extract.Extract(urls, options)
}
```

### Install

    go get github.com/Liam-Williams/embedly

### License

MIT
