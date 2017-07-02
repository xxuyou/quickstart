# quickstart

本仓库旨在帮助您快速熟悉 [荆秀网-实时数据推送](https://xxuyou.com) 服务。

效果如下：

[![荆秀网-实时数据推送](https://xxuyou.com/static/screenshot/demo-quickstart.jpg)](https://xxuyou.com)

## 实现目标

本仓库实现了作为一个合法客户端，来实时接收服务端向外广播的一个名为 `words:update` 的事件所包含的全部数据。

## 准备工作

确保您的网络连接正常。

## 已有参数

本仓库以一个固定 uid 的用户，和一个较长生命周期的 JWT 密钥串（JWT 详细介绍参见：[WSS 客户端接入](https://github.com/xxuyou/wss#客户端接入)）来实现监听服务端数据广播，请不要运用于您的实际业务。
