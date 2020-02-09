# Pi-live-server-service pb服务描述

foreground.proto 定义C端用户需要调用的和无安全需求的rpc

admin.proto 管理端rpc一般对安全要求比较高


## 备注
1. 实现登录，将token放入grpc头
2. 微服务生成对服务名包含-兼容
3. 微服务生成项目读取.env为配置