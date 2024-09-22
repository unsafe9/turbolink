# rpc
copy from : https://github.com/googleapis/googleapis/tree/master/google/rpc

```bash
cd /path/to/Plugins/TurboLink/Source/TurboLinkGrpc/Private/ThirdParty/google/rpc
../../../../../ThirdParty/protobuf/bin/protoc --proto_path=./ --cpp_out=./ *.proto
```

```bash
../../../protoc --proto_path=./ --cpp_out=. *.proto
```