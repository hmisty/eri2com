title: GitBucket——你自己的github
date: 2014-02-11 23:09:30
categories: scm
---

GitBucket是一个比较适合小团队自用的源码管理工具，高仿github。使用Scala语言写就，以一个war包的形式发布，可以很方便的部署到tomcat/jetty/glassfish容器中，开箱即用。

目前已经实现的功能有：

* 公开和私有的git仓库（http访问）
* 仓库查看（不含在线编辑代码等高级功能）
* 仓库搜索（代码和issue）
* wiki
* issue
* 分支和合并请求
* 邮件提醒
* 用户管理
* 群组（类似github的组织）
* LDAP整合
* Gravatar头像支持

目前尚未实现但日后会加入的功能：

* 查看器中的文件编辑
* 对变更集进行注释
* 网路图谱
* 统计
* 关注和标记

[项目地址](https://github.com/takezoe/gitbucket)
