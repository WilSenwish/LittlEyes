# **<center> 个人简历 - 陈俊兵 </center>**


# 联系方式

- 手 机：186 **** 2114 （佛山号码）
- Email：<142****351@qq.com>
- 微 信 / Q Q：186 **** 2114 / 142****351


# 个人信息

 - 陈俊兵 / 男 / 1991
 - 政治面貌：党员
 - 本 科 / 北京信息科技大学 - 计算机学院 - 软件工程专业
 - 工作年限：4 年
 - GitHub：<https://github.com/WilSenwish>
 - 期望职位：Java 中 / 高级工程师
 - 期望城市：北京


# 工作经历

## 智控国际 - 小付钱包技术（北京）有限公司 （ 2015年7月 ~ 2018年5月 ）

### 1. 吉林市互联网政务项目 
我在此项目主要负责用户中心和工作流功能模块的开发。
- 作为核心研发人员，我负责了 用户、组织机构、应用与权限 等二级模块的接口拓展与维护；整合了系统中的普通登录、手机+验证码登录、扫码登录和 OAuth 授权登录，去除了重复的登录代码逻辑；还整合了 PC/WAP 与 APP 端的接口（将两个项目合为一个），并做了接口的细化拆分，以适应多端的不一致页面逻辑，减少了接口与页面逻辑的耦合程度并提升了关键代码的可维护性。
- 最大的挑战是基于 **Activiti** 开源工作流框架，独立设计并实现了审批流程的配置化（项目框架搭建整合、设计流程配置数据库表及流程运行处理逻辑与接口编码实现），并在 Node 端进行业务接口包装；此外，项目还有多部门联合审批流程的配置化初步实现，其中遇到了 Activiti 并发操作失败从而导致流程中断无法继续的情况，最后以定时任务处理替代运行时直接调用，变相的把并发操作改为串行操作来解决问题。
- 随着项目部署的环境越来越多，我在 Maven 项目中加入了多 Profile 配置，以适应多环境的编译打包部署；还引进了持续集成工具 - Jenkins，Jenkins 的引进简化了项目的多环境部署并节省了项目部署的时间，同时把项目的部署纳入了管理体系、而且还便于项目的发版测试。
 

### 2. 企业钱包（统一用户中心、手机动态口令）
我在此项目负责登录、(用户、组织机构、应用与权限) 管理、支付和动态口令功能模块的开发。
- 梳理原有 PC 登录逻辑并完善应用授权跳转逻辑，拆分并重新设计逻辑后开发 APP 端登录逻辑，同时编码实现 APP 端 (用户、组织机构、岗位、应用与角色) 查询接口。
- 透彻理解系统的组织机构、用户、应用与权限的关系并熟记于心，不断完善这一复杂关系的数据库表设计，并维护这一关系的管理接口，且在有需要时为团队其他成员提供相关解答。
- 集成微信与支付宝的扫码支付和 Wap 支付接口，完成用户账户的支付逻辑实现，并对接口进行二次包装整合。
- 实现手机动态口令服务端接口。


# 开源项目和作品

## 开源项目

- [java-classical](https://github.com/WilSenwish/java-classical)：设计模式的 Java 代码实现与详细解析以及模式之间的对比解析

## 技术文章

- [设计模式 之 独一无二的单例模式](https://github.com/WilSenwish/java-classical/blob/master/design-patterns/docs/singleton.md)
- [设计模式 之 控制对象访问的代理模式](https://github.com/WilSenwish/java-classical/blob/master/design-patterns/docs/proxy.md)
- [设计模式 之 让你的对象知悉现况的观察者模式](https://github.com/WilSenwish/java-classical/blob/master/design-patterns/docs/observer.md)


# 技能清单

- 基础：Java / JVM / MVC / AOP / 设计模式 / 多线程 / Node
- 框架：Spring / SpringMVC / MyBatis / Activiti / Sping-Data / Express
- 数据库：SQL / MySQL / Redis / MongoDB / Sequelize
- 开发、构建和部署：Git / Eclipse / WebStorm / Maven / Swagger / Jenkins
- 其他：Linux / Nginx / MQ / UML / Restful


---      
# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。

_简历网络地址： <http://www.wilsenwish.com/>_


