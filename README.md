# gRPC samples

```shell
mvn clean package
```
如果是通过 IDEA 编译运行项目，注意需要重新加载相关 Maven 工程 `Reload Maven Projects`， 否则找不到依赖。

## Java Maven Modules

### Service Sample

grpc-service: service 与 message 定义 (protobuf)

### Server Sample

grpc-server: server listening on 50051 (VehicleServer)

### Client Sample

grpc-client: client call (VehicleClient)

## Nodejs Client Sample

grpc-client-nodejs: client call

```shell
cd grpc-client-nodejs
npm install
node vehicle-client.js
```