[![Build Status](https://travis-ci.com/shellimsi/proto.svg?branch=master)](https://travis-ci.com/shellimsi/proto)
# Proto
This repo includes proto files for Shellimsi.


## Dependencies
* [gRPC](https://grpc.io/docs/quickstart/go.html)
* [Protocol Buffers](https://developers.google.com/protocol-buffers/)
* Golang >=1.11
* Any POSIX environment

## How create or update proto file(s)
```sh
$ protoc -I hub/ hub/hub.proto --go_out=plugins=grpc:hub
```

