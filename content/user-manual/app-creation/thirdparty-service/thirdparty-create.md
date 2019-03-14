---
title: 第三方服务创建
Description: 讲解Rainbond支持第三方服务的创建方式和流程
Weight: 3
Hidden: true

---

### 第三方服务创建

第三方服务创建依然存在两个入口，分别是平台左侧导航的 创建应用-添加第三方服务 和应用Dashboard页面的添加第三方服务按钮，创建流程一致。

#### 创建静态第三方服务

* 选择服务注册访问为静态注册

* 填写服务的通信地址

  比如服务有两个运行实例，IP地址分别是192.168.0.1 192.168.0.2，为了设置方便，我们可以填写第一个实例时携带上端口配置，即提供如下的数据，告知Rainbond服务的监听端口是8080，且都一致。

  > 192.168.0.1:8080
  >
  > 192.168.0.2

* 提交创建，进入到服务的Dashboard页面对服务端口、连接信息、健康检查属性进行配置。 [参考第三方服务管理](/user-manual/app-service-manage/thirdparty-manage/)


#### 创建动态第三方服务

主要描述etcd注册的方式

#### 创建基于API注册的第三方服务

主要描述API使用方式