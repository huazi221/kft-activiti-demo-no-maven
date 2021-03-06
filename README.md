# 简介--(no-maven分支)

本项目旨在让初学者快速入门Activiti。

**作者**：[咖啡兔|http://www.kafeitu.me]

# 框架版本

* Activiti: **5.12.1**

* Spring: **3.1.1.RELEASE**

# 下载源码

* [zip格式](https://github.com/henryyan/kft-activiti-demo/zipball/no-maven)
* [tar.gz格式](https://github.com/henryyan/kft-activiti-demo/tarball/no-maven)

# 演示说明文档

* [配置说明](https://github.com/henryyan/kft-activiti-demo/wiki/%E9%85%8D%E7%BD%AE%E8%AF%B4%E6%98%8E)
* [功能演示](https://github.com/henryyan/kft-activiti-demo/wiki/%E5%8A%9F%E8%83%BD%E6%BC%94%E7%A4%BA)
 
![kft-activiti-demo截图](http://www.kafeitu.me/files/2012/05/kft-activiti-demo.png)

## Changelog

### 1.7.0（2013-03-10）
1. 添加分页查询演示
2. 添加流程定义对象(ProcessDefinition)缓存演示, see: [Tweaking the process definition cache in Activiti 5.12](http://www.jorambarrez.be/blog/2012/12/20/tweaking-process-definition-cache/)
3. 添加activityFontName属性配置，可以解决流程图中包含中文导致生成的流程图乱码问题
4. 整合Activiti Modeler，可以在线设计流程

> 特别说明：5.12.1不是官方提供，是我自己打包的一个版本（支持Native Query分页查询功能，5.13将会直接提供此功能）

### 1.6.0（2013-01-06）
1. 添加多实例（发文）演示
2. 添加自动部署流程定义演示

### 1.5.0 (2012-12-16)
1. 13fc350 添加对流程定义状态的控制功能
2. c50ec09 添加流程实例状态控制功能
3. 9a97cda formkey查询任务时使用native query
4. 3e8ab24 清理垃圾
5. 9035e56 动态表单和外置表单的运行中列表显示的当前节点的英文名称，并在查询流程数据时区分动态、外置表单
6. 7f955c4 重写JuelFormEngine，解决windows平台读取表单内容乱码问题
7. d72778b 升级portlet插件为1.1.1
8. 5e4007c 升级初始化sql的activiti版本为5.11
9. 684c8a0 解决jsp文件中出现两个head问题
10. 3bcbd56 菜单的传统改为普通，外部改为外置
11. 645347c 移除不需要的依赖版本号

### 1.4.1 (2012-12-01)

1.升级jquery.portlet.js解决把一列的portlet拖走后不能再拖回问题

2.升级:jquery -> 1.83，jquery ui -> 1.9.2, jquery.layout -> 1.3，html头部声明用html标准代替xhtml

### 1.4 (2012-11-27)

1.表单名称重构，portlet添加关于作者和表单概念模块

2.首页用jquery.portlet插件显示信息，并添加一个待办任务列表的portlet

2. c50ec09 添加流程实例状态控制功能
3. 9a97cda formkey查询任务时使用native query
4. 3e8ab24 清理垃圾
5. 9035e56 动态表单和外置表单的运行中列表显示的当前节点的英文名称，并在查询流程数据时区分动态、外置表单
6. 7f955c4 重写JuelFormEngine，解决windows平台读取表单内容乱码问题
7. d72778b 升级portlet插件为1.1.1
8. 5e4007c 升级初始化sql的activiti版本为5.11
9. 684c8a0 解决jsp文件中出现两个head问题
10. 3bcbd56 菜单的传统改为普通，外部改为外置
11. 645347c 移除不需要的依赖版本号

### 1.4.1 (2012-12-01)

1.升级jquery.portlet.js解决把一列的portlet拖走后不能再拖回问题

2.升级:jquery -> 1.83，jquery ui -> 1.9.2, jquery.layout -> 1.3，html头部声明用html标准代替xhtml

### 1.4 (2012-11-27)

1.表单名称重构，portlet添加关于作者和表单概念模块

2.首页用jquery.portlet插件显示信息，并添加一个待办任务列表的portlet
