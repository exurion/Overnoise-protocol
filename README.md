# Overnoise-protocol
This repository contains the Protocol buffers definitions of the Overnoise chat protocol.

Simply add it as a submodule to your implementation of Overnoise and generate your sources using `protoc`.

##### Swift example:

```
$ git clone https://github.com/apple/swift-protobuf.git
$ cd swift-protobuf && swift build -c release
$ cp .build/x86_64_macosx/release/protoc-gen-swift /usr/local/bin
$ protoc --swift_out="." *.proto
```
