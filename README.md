# 智慧租赁管理系统 / Intelligent Leasing Management

![SpringBoot](https://img.shields.io/badge/SpringBoot-2.x-brightgreen)
![MyBatisPlus](https://img.shields.io/badge/MyBatisPlus-2.3-orange)
![Shiro](https://img.shields.io/badge/Shiro-1.3.2-blue)
![Vue](https://img.shields.io/badge/Vue-2.x-4fc08d)

# 项目简介  
基于 SpringBoot + MyBatis Plus + Shiro 的全栈式租赁管理系统，集成多数据库支持、百度AI能力和企业级权限控制，包含房源管理、订单处理和信息审批等核心业务模块。

# 特征介绍  
- ​**多端分离架构**：后台管理采用 Vue + ElementUI 技术栈，前台展示系统支持 Layui 混合开发模式。
- ​**智能鉴权体系**：基于 Shiro 实现动态权限管理，支持用户角色与接口权限的细粒度控制。
- ​**混合数据库支持**：同时兼容 MySQL 和 SQL Server 数据库，支持 JDBC 连接池监控。
- ​**AI能力集成**：整合百度 AI SDK 实现图像识别等智能功能，扩展业务场景应用。
- ​**高效开发实践**：MyBatisPlus 实现零 SQL 基础 CRUD，配合 Hutool 工具集提升开发效率。

# 代码结构 
```
src/
├── main/
│   ├── java/
│   │   ├── com/
│   │   │   ├── annotation/          # 自定义注解
│   │   │   ├── config/              # 全局配置
│   │   │   ├── controller/          # 接口层
│   │   │   │   ├── CommonController.java
│   │   │   ├── dao/                 # 数据访问层
│   │   │   ├── entity/              # 数据模型
│   │   │   │   ├── model/           # 业务模型(DingdanxinxiModel)
│   │   │   ├── interceptor/         # 权限拦截器
│   │   │   ├── service/             # 服务层
│   │   │   │   ├── impl/            # 服务实现类
│   │   │   ├── utils/               # 工具类
│   ├── resources/
│   │   ├── admin/                   # 后台管理系统
│   │   │   ├── src/
│   │   │   │   ├── assets/          # 静态资源
│   │   │   │   ├── components/      # Vue组件
│   │   │   │   ├── router/          # 路由配置
│   │   │   │   ├── store/           # 状态管理
│   │   │   │   ├── views/           # 业务页面模块
│   │   ├── application.yml          # 主配置文件
│   │   ├── mapper/                  # MyBatis映射文件
```
# 使用说明
- 开发环境：JDK8+、MySQL5.7+、Node.js14+
- 后台地址：http://localhost:8080/springbootjeb55/admin/dist/index.html
- 测试账号：abo / abo
- 数据库配置：  
  url: jdbc:mysql://127.0.0.1:3306/springbootjeb55
  username: root
  password: [实际密码]

# 技术文档
* 核心框架：[Spring Boot](https://spring.io/projects/spring-boot)
* 持久层框架：[MyBatis-Plus](https://mybatis.plus)
* 权限认证：[Apache Shiro](https://shiro.apache.org/)
* 前端框架: [Vue2](https://v2.vuejs.org/) + [ElementUI](https://element.eleme.io/#/zh-CN)
* 工具组件：[Hutool](https://www.hutool.cn/) + [Fastjson](https://github.com/alibaba/fastjson)
* AI能力支持：[百度AI开放平台](https://ai.baidu.com/)

# 捐赠
> 博主将持续更新Java全栈开发项目，包含ssm，springboot，前后端分离系统等项目。
> 此外如果您够宽裕，请博主喝杯咖啡吧！捐赠将用于服务器维护与开源社区建设，感谢您的认可！
> 如需更多Java相关项目毕设3000+，sql文件可联系博主v:xq-lucky311
![输入图片说明](%E7%91%9E%E5%B9%B8%EF%BC%81%E7%91%9E%E5%B9%B8%EF%BC%81.png)