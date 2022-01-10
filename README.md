fork from "https://github.com/koderover/zadig/blob/main/pkg/tool/log/log.go"



example: 

```go
package main

import "github.com/zou2699/log"

func main() {
    // init first
    log.Init(&log.Config{
        Level:       "debug",
        SendToFile:  false,
        Development: true,
    })

    log.Info("hub server start...")
}
```

