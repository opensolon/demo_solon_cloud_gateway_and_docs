
# 示例2

###  模块服务（有 server.contextPath）

* 运行 src/min/...App
* 文档地址：http://localhost:8080/doc.html
  * 打开接口 demo/hello ，可调试
* 测试接口地址：http://localhost:8080/demo-app/hello?name=ddd

### 网关服务

配置时，会加 contextPath; 用于识别 service

* 运行 src/test/labs/...GatewayApp
* 文档地址：http://localhost:8090/doc.html
  * 打开接口 demo/hello ，可调试
* 测试接口地址：http://localhost:8090/demo-app/hello?name=ddd