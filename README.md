[![Build Status](https://travis-ci.com/shellimsi/proto.svg?branch=master)](https://travis-ci.com/shellimsi/proto)
# Proto
This repo includes proto files for Shellimsi.


## How create or update proto file(s)
```sh
$ protoc -I hub/ hub/hub.proto --go_out=plugins=grpc:hub
```

