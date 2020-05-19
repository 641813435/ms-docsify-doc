#  文档说明

#### 本节包含以下几部分内容。
1. [微服务架构技术文档说明](#微服务技术架构文档说明)
1. [文档体系](#文档体系)
1. [解决问题的途径](#解决问题的途径)


##  微服务架构技术文档说明
#### 此帮助文档主要有如下目标。
1. 帮助开发人员快速入门，降低学习成本，提供了快速入门学习文档。
1. 支持开发人员在具体项目开发中快速解决问题，提供了常用开发参考和和典型开发场景。
1. 提供了全面的详细的《快速开发指南》供开发人员在开发过程中提供参考。
1. 本文档适合以下人员阅读。

#### 本文档适合以下人员阅读。
- 项目经理 
- 设计人员 
- 开发人员 
- 平台管理员  

##  文档体系
#### 微服务技术架构文档由以下文档组成。
- [文档说明](README.md)
- [框架简介](doc/frame-desc.md)
- [框架安装指南](doc/install-desc)
  - [数据库](doc/install-desc?id=数据库安装) 
  - [注册/配置中心组件](doc/install-desc?id=注册/配置中心组件安装)
  - [限流降级组件](doc/install-desc?id=限流降级组件安装)
  - [分布式事务组件](doc/install-desc?id=分布式事务组件安装)
  - [服务监控组件](doc/install-desc?id=服务监控组件安装)
  - [调用链组件](doc/install-desc?id=调用链组件安装)
  - [分布式日志中间件](doc/install-desc?id=分布式日志中间件安装)
  - [大数据中间件](doc/install-desc?id=大数据中间件安装)
- [快速开发指南](doc/develop-desc.md)
  - [微服务API开发](doc/develop-desc.md?id=微服务API开发)
  - [WebService开发](doc/develop-desc.md?id=WebService开发)
  - [工作流开发](doc/develop-desc.md?id=工作流开发)
  - [大数据API开发](doc/develop-desc.md?id=大数据API开发)
  - [网关路由配置](doc/develop-desc.md?id=网关路由配置)
  - [限流降级配置](doc/develop-desc.md?id=限流降级配置)
  - [分布式事务配置](doc/develop-desc.md?id=分布式事务配置)
  - [多租户配置](doc/develop-desc.md?id=多租户配置)
  - [单点登录服务配置](doc/develop-desc.md?id=单点登录服务配置)
- [案例参考](doc/example-desc.md)
  - [接口清单](doc/example-desc.md?id=接口清单)
  - [jwt登录](doc/example-desc.md?id=jwt登录)
  - [熔断降级样例](doc/example-desc.md?id=熔断降级样例)
  - [远程调用样例](doc/example-desc.md?id=远程调用样例)
  - [分布式事务样例](doc/example-desc.md?id=分布式事务样例)
  - [读取配置中心样例](doc/example-desc.md?id=读取配置中心样例)
- [FAQ](doc/faq-desc.md)

##  解决问题的途径
#### 在使用此套微服务技术架构开发过程中，遇到问题可以遵循下面的途径进行解决。
1. 如果是SpringCloud Alibaba使用上的问题，到https://github.com/alibaba/spring-cloud-alibaba/blob/master/README-zh.md
的使用文档中找帮助。
1. 如果是工作流设计开发的使用问题，到https://www.activiti.org/userguide/的使用文档中找帮助，
或者下载中文离线版文档链接：https://pan.baidu.com/s/1qzK6_c4JGFiM0vgGcVn1Pw 提取码：4qts。
1. 如果遇到非本平台提供的中间件安装上的问题，请自行百度、博客搜索安装部署方案。
1. 如果遇到本文档中未记录的组件的使用方式或其他问题，也可自行百度、博客搜索。
