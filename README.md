# grpc-demo

使用Python3和Go实现的一个grpc的demo

## 自动生成代码

`python3 -m grpc_tools.protoc -I protobuf/ --python_out=./protobuf --grpc_python_out=./protobuf protobuf/auth.proto`