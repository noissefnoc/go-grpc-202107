# Golang gRPC 2021-07

2021年7月段階での Golang gRPC の最新のライブラリや


## 利用したモジュールとバージョン

### protoc プラグイン

|用途|ライブラリ|バージョン|
|:-:|:--------:|:------:|
|protocolbuf|[protocolbuffers/protobuf-go](https://github.com/protocolbuffers/protobuf-go)|1.27.1|
|gRPC|[grpc/grpc-go](https://github.com/grpc/grpc-go)|1.39.0|
|gPRC ※このバージョンでdeprecate|[golang/protobuf](https://github.com/golang/protobuf)|1.5.2|
|protoファイルからのバリデーション作成|[envoyproxy/protoc-gen-validate](https://github.com/envoyproxy/protoc-gen-validate)|0.6.1|

### gPRC ライブラリ

|用途|ライブラリ|バージョン|
|:-:|:--------:|:------:|
|Golang middleware|[grpc-ecosystem/go-grpc-middleware](https://github.com/grpc-ecosystem/go-grpc-middleware)|1.3.0|
