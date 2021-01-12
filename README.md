# springcloud-config
微服务配置中心

github 上修改配置文件后，需要cmd 执行 curl -X POST "http://localhost:3355/actuator/refresh" ,3355客户端才能动态获取配置文件内容。
