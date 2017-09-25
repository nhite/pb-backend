[![](https://godoc.org/github.com/nhite/pb-backend?status.svg)](http://godoc.org/github.com/nhite/pb-backend)

This is the grpc/go/protobug definition for the nhite engine

Please do not try to edit the go file that has been generated with:

`protoc --go_out=plugins=grpc:. backend.proto`

To use it with a client implementation, please use 

```go
import pb "github.com/nhite/pb-backend"
```
