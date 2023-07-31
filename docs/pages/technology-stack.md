### 模块

| 项目                       | 说明                         |
| -------------------------- | ---------------------------- |
| `rheinlaser-dependencies`  | Maven 依赖版本管理           |
| `rheinlaser-framework`     | Java 框架拓展                |
| `rheinlaser-server`        | 管理后台服务端(系统启动入口) |
| `rheinlaser-module-system` | 系统功能的 Module 模块       |
| `rheinlaser-module-infra`  | 基础设施的 Module 模块       |

### 框架

| 框架                                                         | 说明                  | 版本        |
| ------------------------------------------------------------ | --------------------- | ----------- |
| [Spring Boot](https://gitee.com/link?target=https%3A%2F%2Fspring.io%2Fprojects%2Fspring-boot) | 应用开发框架          | 3.0.5       |
| [MySQL](https://gitee.com/link?target=https%3A%2F%2Fwww.mysql.com%2Fcn%2F) | 数据库服务器          | 8.0.32      |
| [Druid](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Falibaba%2Fdruid) | JDBC 连接池、监控组件 | 1.2.18      |
| [MyBatis Plus](https://gitee.com/link?target=https%3A%2F%2Fmp.baomidou.com%2F) | MyBatis 增强工具包    | 3.5.3.1     |
| [Dynamic Datasource](https://gitee.com/link?target=https%3A%2F%2Fdynamic-datasource.com%2F) | 动态数据源            | 3.6.1       |
| [Redis](https://gitee.com/link?target=https%3A%2F%2Fredis.io%2F) | key-value 数据库      | 5.0 / 6.0   |
| [Redisson](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Fredisson%2Fredisson) | Redis 客户端          | 3.18.0      |
| [Spring MVC](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Fspring-projects%2Fspring-framework%2Ftree%2Fmaster%2Fspring-webmvc) | MVC 框架              | 5.3.24      |
| [Spring Security](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Fspring-projects%2Fspring-security) | Spring 安全框架       | 5.7.6       |
| [Hibernate Validator](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Fhibernate%2Fhibernate-validator) | 参数校验组件          | 6.2.5       |
| [Springdoc](https://gitee.com/link?target=https%3A%2F%2Fspringdoc.org%2F) | Swagger 文档          | 1.6.15      |
| [Resilience4j](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Fresilience4j%2Fresilience4j) | 服务保障组件          | 1.7.1       |
| [SkyWalking](https://gitee.com/link?target=https%3A%2F%2Fskywalking.apache.org%2F) | 分布式应用追踪系统    | 8.12.0      |
| [Spring Boot Admin](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Fcodecentric%2Fspring-boot-admin) | Spring Boot 监控平台  | 2.7.10      |
| [Jackson](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2FFasterXML%2Fjackson) | JSON 工具库           | 2.13.3      |
| [MapStruct](https://gitee.com/link?target=https%3A%2F%2Fmapstruct.org%2F) | Java Bean 转换        | 1.5.5.Final |
| [Lombok](https://gitee.com/link?target=https%3A%2F%2Fprojectlombok.org%2F) | 消除冗长的 Java 代码  | 1.18.28     |

### 系统功能

| 功能       | 描述                                                         |
| ---------- | ------------------------------------------------------------ |
| 用户管理   | 用户是系统操作者，该功能主要完成系统用户配置                 |
| 在线用户   | 当前系统中活跃用户状态监控，支持手动踢下线                   |
| 角色管理   | 角色菜单权限分配、设置角色按机构进行数据范围权限划分         |
| 菜单管理   | 配置系统菜单、操作权限、按钮权限标识等，本地缓存提供性能     |
| 部门管理   | 配置系统组织机构（公司、部门、小组），树结构展现支持数据权限 |
| 岗位管理   | 配置系统用户所属担任职务                                     |
| 字典管理   | 对系统中经常使用的一些较为固定的数据进行维护                 |
| 短信管理   | 短信渠道、短息模板、短信日志，对接阿里云、腾讯云等主流短信平台 |
| 邮件管理   | 邮箱账号、邮件模版、邮件发送日志，支持所有邮件平台           |
| 站内信     | 系统内的消息通知，提供站内信模版、站内信消息                 |
| 操作日志   | 系统正常操作日志记录和查询，集成 Swagger 生成日志内容        |
| 登录日志   | 系统登录日志记录查询，包含登录异常                           |
| 错误码管理 | 系统所有错误码的管理，可在线修改错误提示，无需重启服务       |
| 通知公告   | 系统通知公告信息发布维护                                     |
| 敏感词     | 配置系统敏感词，支持标签分组                                 |
| 地区管理   | 展示省份、城市、区镇等城市信息，支持 IP 对应城市             |

### 基础设施

| 功能       | 描述                                                         |
| ---------- | ------------------------------------------------------------ |
| 代码生成   | 前后端代码的生成（Java、Vue、SQL、单元测试），支持 CRUD 下载 |
| 系统接口   | 基于 Swagger 自动生成相关的 RESTful API 接口文档             |
| 数据库文档 | 基于 Screw 自动生成数据库文档，支持导出 Word、HTML、MD 格式  |
| 配置管理   | 对系统动态配置常用参数，支持 SpringBoot 加载                 |
| 定时任务   | 在线（添加、修改、删除)任务调度包含执行结果日志              |
| 文件服务   | 支持将文件存储到 S3（MinIO、阿里云、腾讯云、七牛云）、本地、FTP、数据库等 |
| API 日志   | 包括 RESTful API 访问日志、异常日志两部分，方便排查 API 相关的问题 |
| MySQL 监控 | 监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈  |
| Redis 监控 | 监控 Redis 数据库的使用情况，使用的 Redis Key 管理           |
| 消息队列   | 基于 Redis 实现消息队列，Stream 提供集群消费，Pub/Sub 提供广播消费 |
| Java 监控  | 基于 Spring Boot Admin 实现 Java 应用的监控                  |
| 链路追踪   | 接入 SkyWalking 组件，实现链路追踪                           |
| 日志中心   | 接入 SkyWalking 组件，实现日志中心                           |
| 分布式锁   | 基于 Redis 实现分布式锁，满足并发场景                        |
| 幂等组件   | 基于 Redis 实现幂等组件，解决重复请求问题                    |
| 服务保障   | 基于 Resilience4j 实现服务的稳定性，包括限流、熔断等功能     |
| 日志服务   | 轻量级日志中心，查看远程服务器的日志                         |
| 单元测试   | 基于 JUnit + Mockito 实现单元测试，保证功能的正确性、代码的质量等 |