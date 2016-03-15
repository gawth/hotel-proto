# hotel-proto

Protocol Buffer schema for use in performance eval of alternatives to JSON over the wire.  The predominant success criteria is speed.

There are a number of Github repositories:

* [Golang benchmark tests and primary write up of results](https://github.com/gawth/go-proto)
* [Node.js server implementation](https://github.com/gawth/protosrv)
* [.Net server implementation](https://github.com/gawth/proto-service)
* [Protocol Buffer schema](https://github.com/gawth/hotel-proto)
* [Node.js consumer plus benchmarking](https://github.com/gawth/node_proto)

## What's This

Protocol Buffers use a schema defined in a .proto file.  The [Protocol Buffers Site](https://developers.google.com/protocol-buffers/docs/proto3) has a full explanation of the schema language.

This hotel.proto file is intended to be a non-trivial message definition for use in the evaluation.  It is loosely based on message structures used by Laterooms.com


