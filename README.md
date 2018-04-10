Eureka服务注册中心
启动命令：
    java -jar xxx.jar --spring.profiles.active=peer1
    java -jar xxx.jar --spring.profiles.active=peer2
执行两条命令，会启动两个注册中心，并且相互注册，端口分别是：1111,2222
