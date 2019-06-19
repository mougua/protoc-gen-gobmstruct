通过.proto文件生成对应struct（只生成struct），用于b站 [kratos](https://github.com/bilibili/kratos/) 通过 `--proto` 参数生成的项目，有时只想提供http接口，不想有多余的gRPC接口代码。

代码主要由 [gogo/protobuf](https://github.com/gogo/protobuf) 的代码删减而来。主要是自用。
