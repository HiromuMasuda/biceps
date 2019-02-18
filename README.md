# biceps
Golang gRPC examle

## Setup

Install gRPC and Protocol Buffers.

```
go get -u google.golang.org/grpc
go get -u github.com/golang/protobuf/protoc-gen-go
```

## Run server

```
go run server/main.go
```

## Run client and send gRPC request

```
go run client/main.go <arg>
```

## References
- [Go Quick Start | gRPC](https://grpc.io/docs/quickstart/go.html)
- [gRPC go example | gitHub](https://github.com/grpc/grpc-go/tree/master/examples/helloworld)
