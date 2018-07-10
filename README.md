# HRM

#### 项目介绍
&emsp;&emsp;个人空闲时间用来学习新技术的一个可进化型项目，后台使用SpringBoot搭建的一套框架，用MyBatis进行数据库操作。数据库主要是用MySQL，同时项目整合Shiro实现权限管理，Quartz实现定时任务的配置，Spring AOP实现操作日志的收集，同时使用redis做Shiro权限框架的缓存管理机制和Session共享；前台使用thymeleaf模板引擎,H-ui前端框架，使用layer弹出层实现页面的跳转，ztree权限信息的展示，Echarts柱状图展示考勤信息。

#### 软件架构
项目演示地址!(点击这里)[http://47.96.112.160:9000]，用户名：admin,密码admin123


#### 安装教程

1. 下载本项目
2. 将db文件夹中的sql文件导入到本地，并修改配置文件中数据库连接信息
3. 打开本地redis，将项目配置文件中redis的连接信息修改为本地redis信息
4. 将项目导入idea中，启动项目即可。

#### 使用说明
1. 项目分为七个模块--个人信息管理、权限管理（用户管理、授权管理、角色管理、菜单管理）、部门管理、职位管理、日志管理、员工管理、考勤管理。
2. 员工信息和用户信息已关联，插入一条员工信息，用户中也会出现这条信息，只是自动把这个用户对应角色定义为员工。插入一条用户信息，员工中也会出现这条信息，只是员工对应的部门为HR部门，当然职位可以修改。
3. 系统对权限进行很细的划分，例如权限管理员无法修改系统管理员信息。
4. 流程审批正在开发中，待后期完善。。。。。


#### 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [http://git.mydoc.io/](http://git.mydoc.io/)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)