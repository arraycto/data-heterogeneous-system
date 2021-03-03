# 微服务数据异构系统（后端）
![Spring Boot 2.2](https://img.shields.io/badge/Spring%20Boot-2.2-brightgreen.svg)
![Spring cloud 2.2](https://img.shields.io/badge/springcloud%20alibaba-2.2.0-brightgreen)
![Mysql 5.7](https://img.shields.io/badge/Mysql-5.7-blue.svg)
![JDK 1.8](https://img.shields.io/badge/JDK-1.8-brightgreen.svg)
![Maven](https://img.shields.io/badge/Maven-3.6.2-yellowgreen.svg)

## 项目简介


## 项目部署


## 项目技术
- Spring Cloud Hoxton & Alibaba：微服务框架
- Spring Boot 2.3：spring容器+MVC+devtools等等
- JWT、Spring Security Oauth2：权限相关
- Sentinel：熔断限流降级 
- Seata：分布式事务
- OpenFeign：服务间调用
- RabbitMq：消息队列
- logback：日志持久化
- ELK(Elasticsearch、Logstash、Kibana)：日志分析
- knife4j+swagger：文档工具
- Spring cloud gateway：网关
- MyBatis、pagehelper、MyBatisGenerator、Lombok：数据库操作
- MySql、Redis、MongoDB、influxdb：数据库
- Presto：异构数据源同步

![](数据异构系统.png)

## 项目介绍
采用基于服务的数据整合平台。可以在源系统较小改动的情况，有效整合数据，实现各数据源的逻辑整合


## 项目结构
```
data-heterogeneous-system
 ├── README.md
 ├── 数据异构系统.drawio 使用draw.io打开
 ├── log 日志文件夹
 ├── pom.xml 父模块pom文件
 ├── sys-sms 短信微服务
 ├── sys-monitors 微服务集群监控
 ├── sys-mybatisgen dao代码生成
 ├── sys-user 用户微服务
 ├── sys-auth 鉴权微服务：
 ├── sys-gateway 网关微服务
 ├── sys-common 通用模块
 └── data-heterogeneous-system.iml idea文件
```
## 参考链接
https://blog.csdn.net/liukai31415926/article/details/67669123

https://blog.csdn.net/weixin_34015860/article/details/91439856
