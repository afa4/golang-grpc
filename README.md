# Go lang gRPC client and server

## Dependencies

### protoc v3
https://developers.google.com/protocol-buffers/docs/proto3

### Go lang protobuf plugins
```shell
$ go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.28
$ go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.2
```

## Generating server.proto go lang client and server

```shell
./generate_protos.sh
```