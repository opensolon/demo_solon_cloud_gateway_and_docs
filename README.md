
本示例演示，分布式网关与接口文档聚合协同工作（参考时，可以把接口文档相关的去掉）


* demo1

功能模块，无 server.contextPath （不方便 service 识别）；请求时要加个前缀，转发时去掉这个前缀


* demo2

功能模块，有 server.contextPath （已经方便 service 识别）