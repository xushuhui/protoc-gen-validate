# protoc-gen-validate
go validate for protobuf，support for customization of validation error messages 

```proto
string a=1 [(validate.rules).string = {in: ["1","2","3"],error_msg: "this is custom errormsg"}];
```
