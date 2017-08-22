# 目录

## 0、[前言](https://github.com/oopsguy/microservices-from-design-to-deployment-chinese/blob/master/0-foreword.md)

## [1、微服务简介](https://github.com/oopsguy/microservices-from-design-to-deployment-chinese/blob/master/1-introduction-to-microservices.md#1微服务简介)
- [1.1、构建单体应用](https://github.com/oopsguy/microservices-from-design-to-deployment-chinese/blob/master/1-introduction-to-microservices.md#11构建单体应用)
- [1.2、走向单体地狱](https://github.com/oopsguy/microservices-from-design-to-deployment-chinese/blob/master/1-introduction-to-microservices.md#12走向单体地狱)
- 1.3、微服务——解决复杂问题
- 1.4、微服务的优点
- 1.5、微服务的缺点
- 1.6、总结
- 1.7、微服务实战：NGINX作为反向代理服务器

## 2、使用API网关
- 2.1、简介
- 2.2、客户端与微服务直接通信
- 2.3、使用API网关
- 2.4、API网关的优点和缺点
- 2.5、实现API网关
- 2.6、性能与扩展
- 2.7、使用响应式编程模型
- 2.8、服务调用
- 2.9、服务发现
- 2.10、处理部分失败
- 2.11、总结
- 2.12、微服务实战：NGINX作为API网关

## 3、进程间通信
- 3.1、简介
- 3.2、交互风格
- 3.3、定义API
- 3.4、演变API
- 3.5、处理部分失败
- 3.6、IPC技术
- 3.7、异步，基于消息通信
- 3.8、同步，请求/响应 IPC
- 3.9、REST
- 3.10、Thrift
- 3.11、消息格式
- 3.12、总结
- 3.13、微服务实战：NGINX和应用架构

## 4、服务发现
- 4.1、为什么使用服务发现
- 4.2、客户端发现模式
- 4.3、服务端发现模式
- 4.4、服务注册表
- 4.5、服务注册选项
- 4.6、自注册模式
- 4.7、第三方注册模式
- 4.8、总结
- 4.9、微服务实战：NGINX的灵活性

## 5、微服务的事件驱动数据管理
- 5.1、微服务与分布式数据管理问题
- 5.2、事件驱动架构
- 5.3、实现原子性
- 5.4、使用本地事务发布事件
- 5.5、挖掘数据库事务日志
- 5.6、使用事件溯源
- 5.7、总结
- 5.8、微服务实战：NGINX与存储优化

## 6、选择微服务部署策略
- 6.1、动机
- 6.2、单主机多服务实例模式
- 6.3、单主机服务实例模式
- 6.4、单虚拟机服务实例模式
- 6.5、单容器服务实例模式
- 6.6、无服务部署
- 6.7、总结
- 6.8、微服务实战：部署微服务

## 7、用NGINX跨越不同的主机
- 7.1、重构单体为微服务
- 7.2、微服务重构概述
- 7.3、策略1：停止挖掘
- 7.4、策略2：分离前后端
- 7.5、策略3：提取服务
- 7.6、优先将哪些模块转为微服务
- 7.7、怎样提取模块
- 7.8、总结
- 7.9、微服务实战：用NGINX驯服单体应用
- 7.10、微服务与NGINX的相关资源