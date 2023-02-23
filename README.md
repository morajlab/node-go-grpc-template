# node-go-grpc-template

Node.js-Go [gRPC](https://github.com/grpc/grpc) template

### Prerequisites

- `protoc`: [version 3](https://protobuf.dev/programming-guides/proto3)
- `node`: Node 0.12.x or greater
- `go`: any one of the three latest major [releases of Go](https://golang.org/doc/devel/release.html)

### Install

1. Install all dependencies:
   `npm i`
1. Update your `PATH` so that the `protoc` compiler can find the plugins:
   `export PATH="$PATH:$(go env GOPATH)/bin"`

### Run the example

1. `npm run helloworld:server &`
1. `npm run helloworld:client`

> Note: Every time you change `*.proto` files, you must run the `npm run proto:compile` command
