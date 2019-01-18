# activity-platform 活动平台

## 项目介绍
### 功能点
1. 营销活动平台的基础架构实现，具有良好的扩展性
2. 提供营销活动的参与，后台创建，发布等操作模板
3. 对于新活动的接入开发，只需要按照规范新加几个类，实现对应的方法即可

### 技术点
- 活动平台设计开发解决方案
- 采用设计模式抽象出一套完整的活动调用流程和规则引擎
- 工程采用spring-boot框架搭建，核心bean管理通过自定义了一个Bean工厂处理，包含一个内部容器类



## 工程目录模块说明
**activity-platform** 活动平台根目录<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|—— **activity-platform-client**[module] : 活动平台client包，对外提供调用方法<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|—— **activity-platform-provider**[module]: 活动平台具体实现模块 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|—— **activity-platform-document**: 设计和接入开发文档 <br>


## 作者介绍
供职于杭州某互联网创业公司，喜欢总结业务技术架构，提供业务解决技术方案

## 架构图
![活动平台组件化](https://github.com/caisl/activity-platform/blob/master/activity-platform-document/src/main/document/image/%E6%B4%BB%E5%8A%A8%E5%B9%B3%E5%8F%B0%E7%BB%84%E4%BB%B6%E5%8C%96.png)

## 核心UML图
![](https://github.com/caisl/activity-platform/blob/master/activity-platform-document/src/main/document/image/活动平台UML.png)

## 传送门
[01业务功能设计](https://github.com/caisl/activity-platform/blob/master/activity-platform-document/src/main/document/01%E4%B8%9A%E5%8A%A1%E5%8A%9F%E8%83%BD%E8%AE%BE%E8%AE%A1.md)







