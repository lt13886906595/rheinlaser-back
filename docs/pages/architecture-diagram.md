### RheinLaser管理系统架构图

![架构图](../assets/png1.jpg)

### 系统架构说明

1. 系统采用主流技术栈，SpringBoot、SpringSecurity、MyBatisPlus、Validation等技术栈
2. 系统采用模块化分层架构，按照功能进行拆分多个Maven Module，单一职责，开发效率高，易于维护，便于扩展
3. 系统采用前后端分离，前端基于Vue+ElementUI界面，后端基于Spring MVC提供的RestFul API接口
4. 系统支持RBAC功能权限、数据权限、操作日志/API日志、邮件、短信等