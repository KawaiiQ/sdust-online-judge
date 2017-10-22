# SDUST Online Judge

毕设项目，基于Django的程序在线评测系统。

**此处已停止继续开发，请移步https://github.com/HeerKirov/sdust-online-judge**

## 功能 & 特点

* 整体分为用户端与评测端。

* 评测端对外以RESTful API的形式提供题库使用以及题目评测服务，可为多个用户端提供服务。可以此API灵活定制开发不同用户端满足不同机构需求而无需重新开发部署评测后台和维护题库。（用户端尚在开发中）

* 题目进一步分解出题元的概念，可更加方便灵活地维护相似题目。

* 提交状态按测试数据分组记录，获得更加全面的评测信息。

* 分布式评测，更灵活地配置评测机。

## 软件环境

所有能够运行以下软件的环境均可，但建议使用Debian系统。

* Python 3.4+，所依赖的包参见各端及评测机的文档说明。

* PostgreSQL 9.6+

* Redis 3.2.7+


License: The Star And Thank Author License
