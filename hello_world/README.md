# 環境構築(Hello, World!まで)

```sh
mkdir hello_world
cd hello_world
go mod init hello_world
touch main.go
```

```go:main.go
package main

import "fmt"

func main() {
 fmt.Println("Hello, World!")
}

```

```sh
# 実行
go run main.go
```
